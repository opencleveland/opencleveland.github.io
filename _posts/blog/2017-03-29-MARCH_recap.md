---
layout: blog
published: true
categories: blog
title: March 15th 2017 Meeting recap
author: Will 
---
Here's our notes from our most recent meeting/hack night on March 15, 2017. 

## What we're doing/Did: 
We're processing the [Campaign Finance Contributions of Cuyhoaga County](http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx)
into open, machine-readable format. 

These campaign contributions received by the politician can be used by the politican for their next election or re-election campaign including but not limited to: buying advertisements, purchase food for campaign and hiring consultants,
[Campaign Finance contributions (and expenditures) to politicians in Cuyahoga County are available](http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx) 
However, they are not [machine-readable](https://opengovdata.io/2014/analyzable-data-in-open-formats/) 
and greatly impedes any analysis and research.  

*At our meeting on the 15th, we:*
1. OCR'ed the text from the PDFs using Acrobat, 
1. used Tabula (http://tabula.technology/) to extract the text from the PDFs and transformed them into CSV files, 
1. then uploaded the CSVs into google sheets which is flexible (and machine-readable), easily viewable, and
1. lastly, reviewed each year's data with the original PDFs, correcting any spelling mistakes or formatting errors that were introduced in the ETL process. 

With the data in machine-readable format, You can begin to analyze and research the campaign contributions. Questions that can be answered with the data: How many people who live outside of Cleveland gave money to a particular politician ? Who are the biggest campaign contributors? How many PACs have given him money? Where do most of his donations come from? the west side? the south side? east side? 

### Frank Jackson's 2013-2016 Campaign Finance Contributions in Machine Readable format: 

[2013 Campaign Finance Contributions for Frank Jackson](https://docs.google.com/spreadsheets/d/11xJo1SIAeKdcikaVwf4eX56w44xBNqCWn4j_Z5kipg8/edit#gid=643476145
) (does not include 2013_F_Jackson_SemiAnnual.pdf)

[2014 Campaign Finance Contributions for Frank Jackson](https://docs.google.com/spreadsheets/d/1qrbzsysJkC8-W9-mhVj2_mov365_BjkaoINUzSGuHIc/edit#gid=0)

[2015 Campaign Finance Contributions for Frank Jackson](https://docs.google.com/spreadsheets/d/1fL6zdkw33xeKUlfiSeIS-qdDC6gpYQPvTTrBrVtFAVY/edit#gid=1499468696)

[2016 Campaign Finance Contributions for Frank Jackson](https://docs.google.com/spreadsheets/d/1yASJW3C-Dg4-klOAOIwrjzHVMsLKb-ETmULT9_9rrxU/edit#gid=1449833507)

**Want to help :**
1. Email us at opencleveland@gmail.com

You
http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx  

Thanks to our this meeting's participants - Ron J, Kevin, Rob, and Will for assisting in this process! 

Additional campaign contributions to Cuyahoga county politicians are available at the [Cuyahoga County board of elections](http://boe.cuyahogacounty.us/en-US/campaign-finance-reports.aspx)

Other news, data sources: 
Ron J has access to data from the 29 rain stations that record how much rain falls (not sure if they also collect the winter precipitation) that's collected by the NEO Sewer District
suggested we ask the NEO Sewer District to request the data.  


http://www.meetup.com/open-cleveland - Meetup group where our meetings are scheduled.

https://opencleveland.slack.com - Slack slack where our discussions happen in between meetings (need an invite? email opencleveland at gmail dot com)

https://github.com/orgs/opencleveland - code repository



