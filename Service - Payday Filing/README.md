![IRD logo](../Images/IRlogo.gif)
![Software Dev](../Images/SoftwareDev.png)

# Payday filing through myIR File Upload Services


#### Release 2022 tax year - [view details](#Release-2022-update-details)
#### Release 2021 tax year - [view details](#Release-2021-update-details)

#### Archive
* [Payday Filing - 2020 tax year](./Archive/Release2020/)
* [Payday Filing - 2021 tax year](./Archive/Release2021/)

## About the services

Payday filing through our myIR file upload services lets employers:

* send changes to employee details (ED) for new, existing and departing employees.
* file employment information (EI) to us each pay cycle instead of monthly.
* send employment information amendments (EIA).

-----------------
## Key documentation

- Business use cases
	* [Download and view the Payday filing business use cases](Paydayfiling_myIR_Fileupload_business_use_cases_2021.pdf)
	

- Technical Specifications 2022
    * [Download the Payday Filing File Upload Specification 2022 v1.0](Payday%20Filing%20File%20Upload%20Specification%202022%20V1.0.pdf) for the period April 2021 to March 2022.

- Technical Specifications 2021
	* [Download the Payday filing specifications for file upload v 1.4](PaydayFiling_FileUpload_Specification_2021_V1.4.pdf) for the period April 2020 to March 2021. This incorporates
		* employee details file transfer (CSV format) for HED2 and HED versions
		* employee details file upload (Excel format) services 
		* employment information file transfer service (CSV format) for HEI2 and HEI versions
		* employment information amendments file transfer service (CSV format) for EIA2 and EIA versions
		* EMS and EDF payroll filing (CSV format) - filing amendments to payroll schedules submitted before 1 April 2019. 


	
- Casebooks
    * [Download the Employment Information Casebook 2021 tax year (HEI2) v 1.0](Payday_EI_Casebook_2021_HEI2_V1.0.pdf) to view scenarios and examples that support the content in the payday filing file upload specification
	* [Download the Employment Information Casebook 2021 tax year (HEI) v 11](Payday_EI_Casebook_2021_HEI_V11.pdf) to view scenarios and examples that support the content in the payday filing file upload specification
	* Use the examples to compare with the output from your software package.
	
## Sample files
* [View and download](#ED-sample-files) employee details (ED) sample files for HED2 version
* [View and download](#EI-sample-and-casebook-files) employment information (EI) casebook and sample files for HEI2 and HEI versions
* [View and download](#EIA-sample-files) employment information amendments (EIA) sample files for EIA2 version

- Excel template
	* [Download employee details Excel template](New_and_departing_Employee_Details_template_R2021.xls)
	
## Testing and support for file upload service

We provide support for development and testing of the payday filing myIR file upload services.

* Please register your organisation in our developer portal to access support and to keep up to date with the latest release.
* Once registered you request access to our Test a file services.

	* [Register for the developer portal](https://developerportal.ird.govt.nz/?Link=SIGNUP)

* Alternatively, if you do not need support you can submit files to us to validate their compatibility with our payday filing specification.

	* [Access the Test a file services](#Test-a-file-services)

## Supporting information

* [Download and view the Payroll calculations and business rules specifications **2022** Release](Payroll%20Calculations%20&amp;%20Business%20Rules%20Spec%202022%20V1.0.pdf) - for the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes
* [Download and view the Payroll calculations and business rules specifications **2021** Release](Payroll_calculations%20_business_rules_specifications_2021_V1.0.pdf) - for the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes
* Find out how to make employee deduction payments [on the IR website](https://www.ird.govt.nz/employing-staff/payday-filing)

## Supporting services

* Service: [Multi-payment option](../Service%20-%20Multi-Payment%20ption/)

---

## Release 2022 update details

### Employee Details file upload service

File Formats no longer available for use 
With the introduction of the new ED and EI file versions in April 2020, the following file 
formats will no longer be accepted: 
*  From 1 April 2021, the Employee Details file format with the header record indicator 
of **HED** will no longer be accepted.  The updated version of the Employee Details file 
format (header record indicator HED2) must be used. 
*  For files with a **payday** of 1 April 2021 or later, the Employment Information file 
format with the header record indicator of **HEI** will not be accepted.  The updated 
version of the Employment Information file format (header record indicator HEI2) 
must be used. 
*  From 1 April 2021, the KiwiSaver Employment Details (**KS1**) form will no longer be 
accepted.  All details previously provided via this form should now be provided by 
using the HED2 version of the Employee Details file. 
>**Note:** The original EI Amendment file (header record indicator EIA) will still be available, as 
previously filed EI files with the header record indicator of HEI can only be amended with an 
EIA.  

### Tax threshold and rate change 

Proposed is a new tax threshold/rate of 39% for income over $180,000.  There are some 
consequential amendments which would impact payroll including: 
*  A new secondary tax code 
*  New rate for extra pays 
*  A new ESCT rate 
*  New rate and threshold for FBT calculations 

Refer to the Payroll Business Rules & Calculations Specification for further details of the 
impacts.

The impacted areas of this specification have been indicated and will be confirmed once this 
change becomes legislation. 

---

## Release 2021 update details

### Employee Details file upload service

* Updated employeeNameOnEILine to allow 255 characters, previously this was 20
* Updated ‘KiwiSaverStatus’, changed valid options to: AK, OK, NK, CT, AE(Removed: OT, NM, CH)
* Added new fields for KiwiSaver Eligibility, Employee Exempt Income
* Added tax codes table to show valid tax codes. ESS, SLCIR, and SLBOR are no longer valid tax codes
* Added 10 new fields for KiwiSaver opt-out information
* the addition of the KiwiSaver fields means a separate KiwiSaver Employment Details (KED) form will no longer need to be filed
* mobile phone area code field merged into mobile phone number field
* added 4 new, optional address fields.
	
> Note: The previous version of the ED csv file may still be used for reporting of employee details for now, however only the new version of the file will be accepted from 1 April 2021.  
> * If the previous version of the ED CSV file is still being used, then the current KED file may be used for providing KiwiSaver details, however the KED will not be accepted from 1 April 2021. 
> * The new version of the Excel ED file must always be used from the R4 release in April 2020

### Specification 1.2 Update to Employee Details

* ED excel and csv files - State field - description - this is an optional field that should be left blank for NZ addresses.
* ED excel file filed description updates
	* KiwiSaver Status - changed valid options to be used
	* Daytime phone extension 
	* Employee’s Exempt income reason - changed valid options to be used
	* Employee’s reason for late opt-out - changed valid options to be used
	* Other late opt-out reason
	* Updated the term contributions holiday to savings suspension.

### Employment Information and Employment Information Amendment file upload services

* new fields for hours paid, prior period adjustments (gross and PAYE)
* new fields for SLCIR, SLBOR and ESS deductions
* updated field length in the employee name field.

> **Note:** The provision of hours paid information by employers is not compulsory. It’s requested under the same terms as employee date of birth, in that if the employer holds the information in their payroll system, they must send it to us. 
> * Employers do not have to obtain this information if they do not already hold it. However, it will help us and potentially their own employees if they are able to gain the information and send it to us.

> Prior period adjustment fields
> * If you already have a functioning amendment process, you do not have to use the prior period adjustment fields. You may continue to amend the incorrect returns.

---



## Sample files

### ED sample files

* employee details csv sample file - [2021 HED2 version](./Sample%20files/ED_Test_HED2_2021_example.csv)

### EI sample and casebook files

* employment information csv sample file - [2021 HEI2 version](./Sample%20files/EI_Test_HEI2_2021_example.csv)
* employment information csv casebook input file - [2021 HEI2 version](./Sample%20files/Casebook_EI_Input_HEI2_2021_V1.0.csv)
* employment information csv casebook upload file - [2021 HEI2 version](./Sample%20files/Casebook_EI_Upload_HEI2_2021_V1.0.csv)
* employment information csv casebook input file - [2021 HEI version](./Sample%20files/Casebook_EI_Input_HEI_2021_v11.csv)
* employment information csv casebook upload file - [2021 HEI version](./Sample%20files/Casebook_EI_Upload_HEI_2021_v11.csv)

	
### EIA sample files

* employment information amendment csv sample file - [2021 EIA2 version](./Sample%20files/EIA_Test_EIA2_2021_example.csv)

----
## Test a file services

* <a href="https://myir.ird.govt.nz/eservices/home?link=TSTEMP2" target="_blank">Employee Details CSV - Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=TSTLNK" target="_blank">Employee Details Excel Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=PSOEI2TEST" target="_blank">Employment Information CSV Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=PSOEIATEST2" target="_blank">Employment Information Amend CSV Release 2021</a>
