![IRD logo](../../../Images/IRlogo.gif)
![Software Dev](../../../Images/SoftwareDev.png)

# Payday filing through myIR File Upload Services

#### Release - 2020 tax year

## About the services

Payday filing through our myIR file upload services lets employers:
* send changes to employee details (ED) for new, existing and departing employees.
* file employment information (EI) to us each pay cycle instead of monthly.
* send employment information amendments (EIA).

-----------------
## Key documentation

- Business use cases
	* [Download and view](Paydayfiling_myIR_Fileupload_business_use_cases_2020.pdf) the payday filing business use cases
	
- Technical Specifications 
	* [Download the Payday filing specifications for file upload](PaydayFilingFileUploadSpecification2020v11.pdf) for the period April 2019 to March 2020. This incorporates
		* employee details file transfer (csv format) for HED version
		* employee details file upload (Excel format) services 
		* employment information file transfer service (csv format) for HEI version
		* employment information amendments file transfer service (csv format) for EIA version
		* EMS and EDF payroll filing (csv format) - filing amendments to payroll schedules submitted before 1 April 2019
		
- Case book
    * [Download the Employment Information Casebook Release 2020](PaydaySoftwareDevelopersCasebook2020v12.pdf) to view scenarios and examples that support the content in the payday filing file upload specification
		* Use the examples in this document to compare with the output from your software package
	
## Sample files
    * [View and download](#ED-sample-files) employee details (ED) csv sample file and Excel template
	* [View and download](#EI-sample-files) employment information (EI) csv casebook (input and filing) and sample files
	* [View and download](#EIA-sample-files) employment information amendments (EIA) csv sample file
	
- Excel template
	* [Download employee details Excel template](New-and-departing-employee-details-template_R2020.xlsx)
	
## Testing and support for file upload service

We provide support for development and testing of the payday filing myIR file upload services.

* Please register your organisation in our developer portal to access support and to keep up to date with the latest release.
* Once registered you request access to our Test a file services.

	* [Register for the developer portal](https://developerportal.ird.govt.nz/?Link=SIGNUP)

* Alternatively, if you do not need support you can submit files to us to validate their compatibility with our payday filing specification.

	* [View the Test a file services](#Test-a-file-services)

## Supporting information

* [Download and view the Payroll calculations and business rules specifications 2021 Release](Payroll_calculations _business_rules_specifications_2021_V1.0.pdf) - for the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes
* Find out how to make employee deduction payments [on the IR website](https://www.ird.govt.nz/payroll-employers/returns-payments/payday-filing/)

## Supporting services

* Service: [Multi-payment option](../Service%20-%20Multi-Payment%20ption/)

----
## Sample files

### ED sample files

* employee details csv sample file - [2020 HED version](./Sample%20files/ED_Test_HED_2020_example.csv)

### EI sample files

* employment information csv sample file - [2020 HEI version](./Sample%20files/EI_Test_HEI_2020_example.csv)
* employment information csv casebook input file - [2020 HEI version](./Sample%20files/Casebook_EI_Input_HEI_2020_v11.csv)
* employment information csv casebook upload file - [2020 HEI version](./Sample%20files/Casebook_EI_Upload_HEI_2020_v12.csv)

	
### EIA sample files

* employment information amendment csv sample file - [2020 EIA version](./Sample%20files/EIA_Test_EIA_2020_example.csv)

----
## Test a file services

* [Employee Details CSV - Release 2020](https://myir.ird.govt.nz/eservices/home?link=TSTEMP)
* [Employee Details Excel Release 2020](https://myir.ird.govt.nz/eservices/home?link=TSTFIL)
* [Employment Information CSV Release 2020](https://myir.ird.govt.nz/eservices/home?link=PSOEITEST)
* [Employment Information Amendment CSV Release 2020](https://myir.ird.govt.nz/eservices/home?link=PSOEIATEST)
