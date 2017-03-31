---
layout: blog
published: true
categories: blog
title: March 15th 2017 Meeting recap
author: Will 
---
Here's our notes from our most recent meeting/hack night on March 15, 2017. 



What we're doing/Did: 
We're processing the Campaign Finance Contributions of Cuyhoaga County - http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx
into open, machine-readable format. 

Contributions to politicians in Cuyahoga County are available at http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx 
Their availability does are not machine-readable (https://opengovdata.io/2014/analyzable-data-in-open-formats/). 
prevents any analysis. 
To enable research and analysis of campaign contributions, the data needs to be not just available in its current status in a machine-readable format. 

At our meeting on the 15th, we:
OCR'ed the text from the PDFs using Acrobat, 
then used Tabula (http://tabula.technology/) , to extract the text from the PDFs and transformed it into CSV files, 
then uploaded the CSV into google sheets which is flexible (and machine-readable),  easily viewable, and
lastly, reviewed each year with the original PDFs and corrected any spelling mistakes or formatting errors that were introduced in the ETL process. 

Now, questions that can be answered with the data: how many people who live outside of Cleveland gave money to a particular politician ? Who are the biggest campaign contributors? How many PACs have given him money? Where do most of his donations come from? the west side? the south side? east side? 

Frank Jackson's 2013-2016 Campaign Finance Contributions in Machine Readable format: 

Will added the 2013 documents; this does not include 2013_F_Jackson_SemiAnnual.pdf 
Available at: 
https://docs.google.com/spreadsheets/d/11xJo1SIAeKdcikaVwf4eX56w44xBNqCWn4j_Z5kipg8/edit#gid=643476145

Ron reviewed the 2014 entries and are available at 
https://docs.google.com/spreadsheets/d/1qrbzsysJkC8-W9-mhVj2_mov365_BjkaoINUzSGuHIc/edit#gid=0

Kevin and Rob reviewed the 2015 entries ; 
https://docs.google.com/spreadsheets/d/1fL6zdkw33xeKUlfiSeIS-qdDC6gpYQPvTTrBrVtFAVY/edit#gid=1499468696

2016 needs to be reviewed
https://docs.google.com/spreadsheets/d/1yASJW3C-Dg4-klOAOIwrjzHVMsLKb-ETmULT9_9rrxU/edit#gid=1449833507

(Want to help? Download the 2016 campaign finance reports for jackson, F at http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx  
then review each row in the spreadsheet 
(need more direction or help? email us at opencleveland@gmail.com)

Need to geocode (geocoding is the processing of taking addresses into longitude and latitude) which is needed for any geospatial analysis and to display locations on web maps? try https://geoservices.tamu.edu/ 
(requiring free signup)

Other news, data sources: 
Ron J has access to data from the 29 rain stations that record how much rain falls (not sure if they also collect the winter precipitation) that's collected by the NEO Sewer District
suggested we ask the NEO Sewer District to request the data.  


http://www.meetup.com/open-cleveland - Meetup group where our meetings are scheduled.
https://opencleveland.slack.com - Slack team site where our discussions happen
https://github.com/orgs/opencleveland - code repository 



