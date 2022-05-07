# Election_Analysis

## Overview of Election Audit 

This report has the complete election audit results of a recent local congressional election for Colorado Board of Elections. 
The election analysis audit is to create a report of the total number of votes cast, the list of candidates, counties, total votes received by each candidate, percentage of the votes received by each candidate,  the winning candidate and extract the same information by the county.



## Election-Audit Results

Total Number of votes cast is 369,711

The analysis of the election shows that:

- There were 369,711 votes cast in the election

- The counties were:
	- Jefferson
	- Denver
	- Arapahoe

- The county results were
	- Jefferson received 10.5% of the vote and 38,855 number of votes. 
	- Denver received 82.8% of the vote and 306,055 number of votes. 
	- Arapahoe received 6.7% of the vote and 24,801 number of votes. 

- The Largest county turnout was:
	- Denver

- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane

- The candidate results were
	- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 
	- Diana DeGette received 73.8% of the vote and 272,892 number of votes. 
	- Raymon Anthony Doane received 3.1% of the vote and 11,686 number of votes. 
- The winner of the election was:
	- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Summary

We would like to propose giving out this script as a generic script that can be used for any election with some minor modifications.
The current script reads the data source csv file with fields Ballot ID, County and Candidate. 

- The csv source can have an additional field of State, so we can determine the winner of per county. The output can contain total number of votes cast in the state with a county specific results, candidate specific results

- With the same source, an option can be given to the user running this script to provide the data for the specific state and / or country they would like to create the election audit


