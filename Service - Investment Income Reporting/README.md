
![IRD logo](../Images/IRlogo.gif)
![Software Dev](../Images/SoftwareDev.png)

# Investment Income Reporting through myIR File Upload Services

## About the services

Investment income reporting through myIR file upload services lets organisations securely file investment income information and amend a previously filed return.
* It enables payers to send investment income information to us more frequently and with more detail on a specific reporting period. 
* It is available for the withholding tax product types - Approved issuer levy (AIL), Dividend withholding tax (DWT), Interest pay as you earn (IPS), Non-resident withholding tax (NRT), Resident withholding tax (RWT) and Portfolio investment entities (PIE) attributed income tax.

-----------------

## Key documentation

- Technical Specifications 
	* [Download the Investment Income Reporting filing specifications for file upload](IIR%20file%20upload%20specification%20V12.pdf). This incorporates:
		* Approved Issuer Levy (AIL) file transfer service (CSV format)
		* Dividend Withholding Tax (DWT) file transfer service (CSV format) for one and two shareholders
		* Interest Pay as you earn (IPS) file transfer service (CSV format)
		* Non-Resident withholding Tax (NRT) file transfer service (CSV format) for dividends, interest, and royalties
		* Resident Withholding Tax (RWT) file transfer service (CSV format) for dividends as interest and Maori Authority distributions
	* [Download the Portfolio Investment Entities (PIE) filing specifications for file upload](PIE%20file%20upload%20specification%20V10.pdf). This incorporates:
		* PIE Periodic Return file transfer service (CSV format)
		* Annual Reconciliation Return file transfer service (CSV format)
		* Investor Certificates file transfer service (CSV format)

-----------------

## Sample files

* Approved Issuer Levy (AIL) 
	* [CSV sample file](./Sample%20files/AIL%20example%20file.csv)
* Dividend Withholding Tax (DWT) 
	* [1 shareholder CSV sample file](./Sample%20files/DWT%201SH%20sample%20file.csv)
	* [2 shareholders joint AC CSV sample file](./Sample%20files/DWT%202SH%20JointAC%20sample%20file.csv)
* Interest Pay as you earn (IPS) 
	* [CSV sample file](./Sample%20files/IPS%20example%20file.csv)
* Non-Resident withholding Tax (NRT) 
	* [AU resident dividends CSV sample file](./Sample%20files/NRT%20AU%20resident%20Dividends%20example%20file.csv)
	* [AU resident interest CSV sample file](./Sample%20files/NRT%20AU%20resident%20Interest%20example%20file.csv)
	* [US resident royalties CSV sample file](./Sample%20files/NRT%20US%20resident%20Royalties%20example%20file.csv)
	* [CA resident copyright (cultural) royalties CSV sample file](./Sample%20files/NRT%20CA%20Resident%20copyright%20royalties%20example%20file.csv)
* Resident Withholding Tax (RWT) 
	* [Dividends as interest CSV sample file](./Sample%20files/RWT%20Dividends%20as%20Interest%20example%20file.csv)
	* [Maori Authority distributions CSV sample file](./Sample%20files/RWT%20Maori%20Authority%20Distributions%20example%20file.csv)
* Portfolio Investment Entities (PIE) 
	* PIE Periodic Return 
		* [One file, single IR852 return - PIEReturns-20100531-001.csv](./Sample%20files/PIEReturns-20100531-001.csv)
		* [One file, single IR852 return - PIEReturns-20200531-001.csv](./Sample%20files/PIEReturns-20200531-001.csv)
		* [One file, multiple PIEs - PIEReturns-20100531-002.csv](./Sample%20files/PIEReturns-20100531-002.csv)
		* [One file, multiple PIEs - PIEReturns-20200531-002.csv](./Sample%20files/PIEReturns-20200531-002.csv)
	* Annual Reconciliation Return
		* [One file, single IR853 return - PIEReturns-20200628-005.csv](./Sample%20files/PIEReturns-20200628-005.csv)
		* [One file, multiple IR853 returns, multiple PIEs - PIEReturns-202005031-002.csv](./Sample%20files/PIEReturns-202005031-002.csv)
	* Investor Certificates
		* [One file, multiple IR854 investor certificates - PIEReturns-20200331-001.csv](./Sample%20files/PIEReturns-20200331-001.csv)
	* Grouped file example
		* [Grouped file - PIEReturns-20200603-01.zip](./Sample%20files/PIEReturns-20200603-01.zip)

-----------------

## Testing and support for file upload service

We provide support for development and testing of the Investment income reporting myIR file upload services.

* Please register your organisation in our developer portal to access support and to keep up to date with the latest release.
* Once registered you request access to our Test a file services.

	* [Register for the developer portal](https://developerportal.ird.govt.nz/?Link=SIGNUP)

* Alternatively, if you do not need support you can submit files to us to validate their compatibility with our Investment income reporting specification.

	* [Access the Test a file services](#Test-a-file-services)

-----------------

## Test a file services

* [Approved Issuer Levy (AIL) – CSV format](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=AILTEST)
* [Dividend Withholding Tax (DWT) – CSV format](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=DWTTEST)
* [Interest Pay as you earn (IPS) – CSV format](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=IPSTEST)
* [Non-Resident withholding Tax (NRT) – CSV format](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=NRTTEST)
* [Resident Withholding Tax (RWT) – CSV format](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=RWTTEST)
* [Portfolio Investment Entities (PIE) CSV](https://eservices-test.npnsp.ird.govt.nz/eservices/home/?link=PIETEST)


