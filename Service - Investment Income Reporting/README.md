![IRD logo](../Images/IRlogo.gif)
![Software Dev](../Images/SoftwareDev.png)

# Investment Income Reporting through myIR File Upload Services

#### Release 2020 tax year

#### Archive
* [IIR specifications - 2020 tax year](./Archive/Release2020/)

## About the services

Investment income reporting through myIR file upload services lets organisations securely file investment income information and amend a previously filed return.
* It enables payers to send investment income information to us more frequently and with more detail on a specific reporting period. 
* It is available for the withholding tax product types - Approved issuer levy (AIL), Dividend withholding tax (DWT), Interest pay as you earn (IPS), Non-resident withholding tax (NRT), Resident withholding tax (RWT) and Portfolio investment entities (PIE) attributed income tax.

----
## Release 2023 update details

### Investment Income Reporting file upload service - updates in specification v1.5

* See build back for changes 

----
## Release 2020 update details

### Investment Income Reporting file upload service - updates in specification v1.4

* AIL File - updated AIL deducted and AIL rate fields - validation rules updated for custodians 
* DWT File - updated Shares field - validation rules updated for custodians
* NRT File - updated Shares and Bonus issue fields - validation rules updated for custodians
* Interest Pay as your Earn (IPS) - Renamed the service name to Resident Withholding Tax on Interest (IPS) - correct term for tax type

### IIR PIE file upload service - updates in specification v1.1

* Periodic return, Annual Reconciliation return, Investor Certificate return - updated sample file names for easier identification of return types

----
## Key documentation

- Technical Specifications

* [Download the Investment Income Reporting filing specifications for file upload v1.5](IIR_File_Upload_Specification_V1.5.pdf). 

* [Download the Portfolio Investment Entities (PIE) filing specifications for file upload v1.3](PIE%20File%20Upload%20Specification%20V1.3.pdf). This incorporates:
	* PIE Periodic Return file transfer service (CSV format)
	* Annual Reconciliation Return file transfer service (CSV format)
	* Investor Certificates file transfer service (CSV format)

- User guide
    * [Download the Investment Income Reporting file upload guide v 1.0](Investment_Income_Returns_file_upload_guide.pdf) to view guidelines on how to file for DWT, IPS and NRT that support the content in the Investment Income Reporting file upload specification.
	* [Download the IIR csv data template](csv_data_template.xlsx) to view specification example records for DWT, IPS and NRT to support the user guide.

## Sample files
* [View and download](#Approved-Issuer-Levy) Approved Issuer Levy (AIL) sample files
* [View and download](#Dividend-Withholding-Tax) Dividend Withholding Tax (DWT) sample files
* [View and download](#Resident-Withholding-Tax) Non-Resident Withholding Tax (NRT) sample files
* [View and download](#Resident-Withholding-Tax-on-Interest) Resident Withholding Tax on Interest (IPS) sample files
* [View and download](#Non-Resident-Withholding-Tax) Resident Withholding Tax (RWT) sample files
* [View and download](#Portfolio-Investment-Entities) Portfolio Investment Entities (PIE) sample files

## Testing and support for file upload service

We provide support for development and testing of the Investment income reporting myIR file upload services.

* Please register your organisation in our developer portal to access support and to keep up to date with the latest release.
* Once registered you request access to our Test a file services.

	* [Register for the developer portal](https://developerportal.ird.govt.nz/?Link=SIGNUP)

* Alternatively, if you do not need support you can submit files to us to validate their compatibility with our Investment income reporting specification.

	* [Access the Test a file services](#Test-a-file-services)

----
## Sample files

### Approved Issuer Levy

* [CSV sample file](./Sample%20files/AIL%20example%20file.csv)

### Dividend Withholding Tax

* [1 shareholder CSV sample file](./Sample%20files/DWT%201SH%20sample%20file.csv)
* [2 shareholders joint AC CSV sample file](./Sample%20files/DWT%202SH%20JointAC%20sample%20file.csv)

### Non-Resident Withholding Tax

* [AU resident dividends CSV sample file](./Sample%20files/NRT%20AU%20resident%20Dividends%20example%20file.csv)
* [AU resident interest CSV sample file](./Sample%20files/NRT%20AU%20resident%20Interest%20example%20file.csv)
* [US resident royalties CSV sample file](./Sample%20files/NRT%20US%20resident%20Royalties%20example%20file.csv)
* [CA resident copyright (cultural) royalties CSV sample file](./Sample%20files/NRT%20CA%20Resident%20copyright%20royalties%20example%20file.csv)

### Resident Withholding Tax on Interest

* [CSV sample file](./Sample%20files/IPS%20example%20file.csv)

### Resident Withholding Tax

* [Dividends as interest CSV sample file](./Sample%20files/RWT%20Dividends%20as%20Interest%20example%20file.csv)
* [Maori Authority distributions CSV sample file](./Sample%20files/RWT%20Maori%20Authority%20Distributions%20example%20file.csv)

### Portfolio Investment Entities

* PIE Periodic Return 
	* [One file, single IR852 return - PIE Prd return single PIE-20100531-001.csv](./Sample%20files/PIE%20Prd%20return%20single%20PIE-20100531-001.csv)
	* [One file, single IR852 return - PIE Prd return single PIE-20200531-001.csv](./Sample%20files/PIE%20Prd%20return%20single%20PIE-20200531-001.csv)
	* [One file, multiple PIEs - PIE Prd return multiple PIEs-20100531-002.csv](./Sample%20files/PIE%20Prd%20return%20multiple%20PIEs-20100531-002.csv)
	* [One file, multiple PIEs - PIE Prd return multiple PIEs-20200531-002.csv](./Sample%20files/PIE%20Prd%20return%20multiple%20PIEs-20200531-002.csv)
* Annual Reconciliation Return
	* [One file, single IR853 return - PIE AR return single PIE-20200628-005.csv](./Sample%20files/PIE%20AR%20return%20single%20PIE-20200628-005.csv)
	* [One file, multiple IR853 returns, multiple PIEs - PIE AR return multiple PIEs-202005031-002.csv](./Sample%20files/PIE%20AR%20return%20multiple%20PIEs-202005031-002.csv)
* Investor Certificates
	* [One file, multiple IR854 investor certificates - PIE IC return single PIE-20200331-001.csv](./Sample%20files/PIE%20IC%20return%20single%20PIE-20200331-001.csv)
* Grouped file example
	* [Grouped file - PIE Grouped Returns-20200603-01.zip](./Sample%20files/PIE%20Grouped%20Returns-20200603-01.zip)

----
## Test a file services

* [Approved Issuer Levy (AIL) - CSV format](https://myir.ird.govt.nz/eservices/home/?link=AILTEST)
* [Dividend Withholding Tax (DWT) - CSV format](https://myir.ird.govt.nz/eservices/home/?link=DWTTEST)
* [Interest Pay as you earn (IPS) - CSV format](https://myir.ird.govt.nz/eservices/home/?link=IPSTEST)
* [Non-Resident withholding Tax (NRT) - CSV format](https://myir.ird.govt.nz/eservices/home/?link=NRTTEST)
* [Resident Withholding Tax (RWT) - CSV format](https://myir.ird.govt.nz/eservices/home/?link=RWTTEST)
* [Portfolio Investment Entities (PIE) - CSV format - Investor Certificate returns only](https://myir.ird.govt.nz/eservices/home?link=PIETEST)
* Portfolio Investment Entities (PIE) - CSV format - Periodic and Annual Reconciliation returns coming soon
