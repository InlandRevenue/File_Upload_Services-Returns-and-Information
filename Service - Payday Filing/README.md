![IRD logo](../Images/IRlogo.gif)
![Software Dev](../Images/SoftwareDev.png)

# Payday filing through myIR File Upload Services

Payday filing through our myIR file upload services lets employers:
* send changes to employee details (ED) for new, existing and departing employees.
* file employment information (EI) to us each pay cycle instead of monthly.
* send employment information amendments (EIA).

### Latest Release - 2021 tax year - [view details](#Release-2021-update-details)

### Archive 
* [Payday Filing - 2020 tax year](./Archive/Release2020/)

## Key documentation

- Business use cases
	* [Download and view](../Payday%20filing%20-%20ED%20and%20EI%20GWS%20business%20use%20cases.pdf)
	
- Technical Specifications 
	* [Download the Payday filing specifications for file upload](Payday%20filing%20file%20upload%20specification%202021%20V1.1.pdf) for the period April 2020 to March 2021. This incorporates
		* employee details file transfer (CSV format) for HED2 and HED versions
		* employee details file upload (Excel format) services 
		* employment information file transfer service (CSV format) for HEI2 and HEI versions
		* employment information amendments file transfer service (CSV format) for EIA2 and EIA versions
		* EMS and EDF payroll filing (CSV format) - filing amendments to payroll schedules submitted before 1 April 2019. 
	
- Sample files
    * [View and download](#ED-sample-files)employee details (ED) sample files for HED2 and HED versions
	* [View and download](#EI-sample-files)employment information (EI) sample files for HEI2 and HEI versions
	* [View and download](#EIA-sample-files)employment information amendments (EIA) sample files for EIA2 and EIA versions

## Supporting information

Find out about:
* the defined tax rates and thresholds, tax types business rules, and calculations required for specific tax codes [on the IR website](https://www.ird.govt.nz/digital-service-providers/services-catalogue/returns-and-information/payday-filing/payroll-calculations-and-business-rules)
* how to make employee deduction payments [on the IR website](https://www.ird.govt.nz/payroll-employers/returns-payments/payday-filing/)

## Supporting services

* [Service: Multi-payment option](../Service%20-%20Multi-Payment%20ption/)

-----------------
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

### Employment Information and Employment Information Amendment file upload services

* new fields for hours paid, prior period adjustments (gross and PAYE)
* new fields for SLCIR, SLBOR and ESS deductions
* updated field length in the employee name field.

> Note: The provision of hours paid information by employers is not compulsory. It’s requested under the same terms as employee date of birth, in that if the employer holds the information in their payroll system, they must send it to us. 
> * Employers do not have to obtain this information if they do not already hold it. However, it will help us and potentially their own employees if they are able to gain the information and send it to us.

> Prior period adjustment fields
> * If you already have a functioning amendment process, you do not have to use the prior period adjustment fields. You may continue to amend the incorrect returns.

-----------------
## Message samples

### ED sample files

	* employee details csv sample file - HED2 version
	* employee details csv sample file - HED version

### EI sample files

	* employment information csv sample file - HEI2 version
	* employment information csv sample file - HEI version
	
### EIA sample files

	* employment information amendment csv sample file - EIA2 version
	* employment information amendment csv sample file - EIA version