# PyALIENVAULT /Central 
This script allows you to fetch the data from Alienvault  Central using the API. The outcome can be stored in CSV or Excel format.  It creates a graph for top 10 clients events for given days. This can be changed as per your requirement based on output needed. All the data can be represented as PPT at end. 

Packages used:


        	Requests 
 
        	Json
 
        	Collections
 
        	Matplotlib
 
        	Time
 
        	Csv
 
        	Datetime
 
        	Pptx
 
        	Onfigparser
 
        	Os
 

Config File: Before using the script open the config file 

Script Execution:

Open the config file and give the required credencials,URL’s, required paths
Open the script in CMD and run the file Av_Central. 
The output can be saved in CAV, exel format.
Graphs can also be represented in this.
Finally  a report with PPT is shown for top 10 of all fields 
Standard HTTP status codes and descriptions
Status Code	Generalized Description
200	Request completed successfully.
201	Create request completed successfully.
400	Request error. See response body for details.
401	Authentication failure, invalid access credentials.
403	Insufficient permission.
404	Requested endpoint does not exist.
409	Invalid operation for this endpoint. See response body for details.
429	Rate limit for this operation has been reached.
500	Unspecified internal server error. See response body for details.


For more details please ref:

[https://cybersecurity.att.com/documentation/api/usm-central-api.htm?tocpath=API%7CAlienVault%C2%AE%20APIs%7C_____2#type-alarmssearchrequest]()
 
[https://cybersecurity.att.com/documentation/api/alienvault-apis.htm]()
