![IRD logo](../Images/IRlogo.gif)
![Software Dev](../Images/SoftwareDev.png)

# Payday Filing through myIR File Upload Services

#### Release 2024 tax year - [view details](#Release2024updatedetails)
#### Release 2023 tax year - [view details](#Release2023updatedetails)

#### Archive

* [Payday Filing - Archives](./Archive/)

## About the services

Payday Filing through our myIR file upload services lets employers:

* send changes to employee details (ED) for new, existing and departing employees.
* file employment information (EI) to us each pay cycle instead of monthly.
* send employment information amendments (EIA).

-----------------
## Key documentation

- Business use cases
	* [Download and view the Payday Filing business use cases](Paydayfiling_myIR_Fileupload_business_use_cases_2021.pdf)

- Technical Specifications  
  * [Download the Payday Filing File Upload Specification 2024 v1.0](2024/Payday%20Filing%20File%20Upload%20Specification%202024%20V1.0.pdf) for the period April 2023 to March 2024.	
  * [Download the Payday Filing File Upload Specification 2023 v1.0](2023/Payday%20Filing%20File%20Upload%20Specification%202023%20V1.0.pdf) for the period April 2022 to March 2023.	

- Casebooks 
    * [Download the Payday Software Developers Casebook 2024 V1.0](2024/Payday%20Software%20Developers%20Casebook%202024%20V1.0.pdf) to view scenarios and examples that support the content in the Payday Filing file upload specification
    * [Download the Payday Software Developers Casebook 2023 v1.1](2023/Payday%20Software%20Developers%20Casebook%202023%20V1.1.pdf) to view scenarios and examples that support the content in the Payday Filing file upload specification

## Sample files
* [View and download](#ED-sample-files) employee details (ED) sample files for HED2 version
* [View and download](#EI-sample-and-casebook-files) employment information (EI) casebook and sample files for HEI2 and HEI versions
* [View and download](#EIA-sample-files) employment information amendments (EIA) sample files for EIA2 version

- Excel template 
    * [Download employee details Excel template 2022+](./Sample%20files/New_and_departing_Employee_Details_template_R2022.xls)
	
	
## Testing and support for file upload service

We provide support for development and testing of the Payday Filing myIR file upload services.

* Please register your organisation in our developer portal to access support and to keep up to date with the latest release.
* Once registered you request access to our Test a file services.

	* [Register for the developer portal](https://developerportal.ird.govt.nz/?Link=SIGNUP)

* Alternatively, if you do not need support you can submit files to us to validate their compatibility with our Payday Filing specification.

	* [Access the Test a file services](#Test-a-file-services)

## Supporting information

* [Download and view the Payroll calculations and business rules specifications **2024** Release](Payroll%20Calculations%20%26%20Business%20Rules%20Spec%202024%20V1.0.pdf) - for the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes
* [Download and view the Payroll calculations and business rules specifications **2023** Release](Payroll%20Calculations%20%26%20Business%20Rules%20Spec%202023%20V1.0.pdf) - for the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes
* Find out how to make employee deduction payments [on the IR website](https://www.ird.govt.nz/employing-staff/payday-filing)

## Supporting services

* Service: [Multi-payment option](../Service%20-%20Multi-Payment%20ption/)

---

## Release 2024 update details <a name="Release2024updatedetails"></a>

### Employee Details file upload service

Summary of major document updates for 2023/24 Year 
The following changes have been made to the relevant sections throughout the document and noted in the Change Log.  A summary is provided here for increased visibility of the updates. 

The 'Payroll services filing' section has been removed from the 2023/24 version of the Payday Filing File Upload Specification as this information is no longer relevant. The information contained in this section was retained for those employers needing to file an 
IR348 EMS for periods prior to 1 April 2019, or an IR345 Employer Deductions or SCF Electronic Subsidy Claim Form for periods prior to 1 April 2020. 

---

## Release 2023 update details <a name="Release2023updatedetails"></a>

### Employee Details file upload service

Summary of major document updates for 2022/23 Year 
The following changes have been made to the relevant sections throughout the document 
and noted in the Change Log.  A summary is provided here for increased visibility of the 
updates. 

Negative Prior Period Adjustments 
From the date of Inland Revenue's final Business Transformation release (currently 
scheduled for late October 2021), the prior period adjustment fields in the EI ('Prior period 
gross adjustments' and 'Prior period PAYE adjustments') will accept negative values.  
However, any negative amounts entered cannot be more than the corresponding amounts 
in the 'Gross earnings and/or schedular payments' field and 'PAYE / tax' field for the line 
item.  I.e. The line can be reduced to zero, but not below. 




## Sample files

### ED sample files

* employee details csv sample file - [2021+ HED2 version](./Sample%20files/ED_Test_HED2_2021_example.csv)

### EI sample and casebook files

* employment information csv casebook input file - [2024 HEI2 version](./Sample%20files/Casebook%20Payday%20Filing%20Input%202024%20V1.0.csv)
* employment information csv casebook upload file - [2024 HEI2 version](./Sample%20files/Casebook%20Payday%20Filing%20Upload%202024%20V1.0.csv)
* employment information csv sample file - [2021+ HEI2 version](./Sample%20files/EI_Test_HEI2_2021_example.csv)
* employment information csv casebook input file - [2021+ HEI2 version](./Sample%20files/Casebook_EI_Input_HEI2_2021_V1.0.csv)
* employment information csv casebook upload file - [2021+ HEI2 version](./Sample%20files/Casebook_EI_Upload_HEI2_2021_V1.0.csv)
* employment information csv casebook input file - [2021+ HEI version](./Sample%20files/Casebook_EI_Input_HEI_2021_v11.csv)
* employment information csv casebook upload file - [2021+ HEI version](./Sample%20files/Casebook_EI_Upload_HEI_2021_v11.csv)
	
### EIA sample files

* employment information amendment csv sample file - [2021+ EIA2 version](./Sample%20files/EIA_Test_EIA2_2021_example.csv)

----
## Test a file services

* <a href="https://myir.ird.govt.nz/eservices/home?link=TSTEMP2" target="_blank">Employee Details CSV - Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=TSTLNK" target="_blank">Employee Details Excel Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=PSOEI2TEST" target="_blank">Employment Information CSV Release 2021</a>
* <a href="https://myir.ird.govt.nz/eservices/home?link=PSOEIATEST2" target="_blank">Employment Information Amend CSV Release 2021</a>
