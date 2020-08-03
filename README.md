# Election Analysis
## Overview of Election Audit
### Purpose
The purpose of this exercise was to create an election audit using Python and submit results to two clients, Tom & Seth. The clients provided a .csv data file of election results including Ballot ID, County, and Candidate. My task was to consolidate the results and present my findings on the items below:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout
## Election-Audit Results & Summary
### Overall Results
The audit was performed swiftly using python to extract data from the CSV file, consolidate information and run key equations including percent of total vote, votes by candidate, votes by county, and others to successfully audit the election.

### Key Audit Questions
*(Reference Results Below)*
- How many votes were cast in this congressional election? 
  - There were 369,711 total votes cast.
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Dianna DeGette won w/ 73.8% of the total vote. 272,892 people voted for Dianna.

***Results***

![](/Resources/Screenshots/Results.png)


### Election-Audit Summary
This Election Audit script can be adapted and use to maintain efficacy of any election results. The script is designed to take all rows of voting data, summarize and organize by all candidates voted for and all counties voted in in the raw data source. The script can be adapted to summarize details based on other parameters such as demographics, age, or any other data type provided. Using this script instead of calculating by hand minimizes user error, and prevents fraud.
