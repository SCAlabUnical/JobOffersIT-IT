# JobOffersIT-IT
Job offers in the IT sector for the Italian market

Repo contains the entire dataset used for job analysis and classification.

The most important file is *job_offer JOIN job_data*, stored in different formats like: **CSV, JSON, SQL and XML**. 

This table contains more than **2000** job offers in the IT sector for Italian market, analyzed during the period from March to May in 2021, classified by:
* Job category;
* Job subcategory (if available);
* Type of submitted contract;
* Knowlege in terms of programming languages, frameworks, dbms and IDE;
* Job location.

It's present too, the entire description, of analized job offer, in HMTL formats, the original URL and an autogenerated key, that is primary key.

The rest of files, stored into *dataset* folder in **SQL** format, rapresente dataset; there are several tables that contains different data. The names of these tables
identify the information they contain.




Repo also contains software, represented by *software.zip* file developed in Java, that automated the process of download and analysis of job offers in the IT sector for Italian market. The use of this software, in particular classes and methods of *searchAndDownload* package, allow the download from the job offers sites: **Adecco, Randstad and Manpower**.
To start download phase, is necessary specify job category to be researched, software will research all offers with the same category.
**It's necessary to start 3 different classes, because of the different structure of sites consulted**.

Once raw data are stored, thanks to method and classes of *searchAndDownload* package, it's possible to start the analysis and classification phase. In this case it is sufficient to start *DataExtractionStarter* class of the package *dataExtraction* contained in *dataManagement*


In *analysis and results* are stored PNG files that illustrates result generated from job offers analisys.
