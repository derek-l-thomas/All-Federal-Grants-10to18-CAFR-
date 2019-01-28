# All-Federal-Grants-10to18-CAFR-

## Data Scrape Steps

### 1) Data on federal grant revenues are sourced from [NYC's Comprehensive Annual Financial Reports (CAFR)](https://comptroller.nyc.gov/reports/comprehensive-annual-financial-reports/), FY 10-18
* Used Tabula to extract data from "Part II-F – General Fund – Schedule G3 Revenues vs. Budget by Agency"

### 2) Used OMB's ["Revenue Budget & Financial Plan -- Exec\Adpt\Prel"](https://data.cityofnewyork.us/City-Government/Revenue-Budget-Financial-Plan-Exec-Adpt-Prel/ugzk-a6x4) to match RSCs and Agency Codes with Revenue Source Names (RSN) and Agency Names 
   
### 3) Used OMB's [Revenue Financial Plan (RFP)](https://www1.nyc.gov/site/omb/publications/finplan11-18.page) to match RSCs with Catalog of Federal Domestic Assistance numbers (CFDA)

* Grants where we could not find matching CFDA3s are labeled as "CFDA not found"
* Most CFDA#s have multiple RSCs, but each RSC has one unique CFDA#
* Some CFDA#s documented when looked up cannot be found on the [U.S. Government's Assistance Listings](beta.sam.gov) despite being documented in the RFP
* [What is a CFDA number?](http://www.research.pitt.edu/what-cfda-number)

### 4) Determined the following RSCs are categorized as federal grants
* #900 – 16163; #50000 - #50008; #57000

### 5) Master table is found in tab 'CAFR 10-18'
    

## Attribution
*Please consider atrributing data citations to [FPWA](https://www.fpwa.org/)*
