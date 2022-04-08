# election-analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.66.0

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
  - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Challenge Overview
During the latest congressional election, the Colorado Board of Elections came to me requesting assistance in pulling together their election report to submit to the election commission. I was instructed to find and provide the following information from the raw election data provided by the Board:
```
1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote
```
After submitting the congressional election results, the election commission requested the below additional data to complete their audit: 
```
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout
```
Using Python and Visual Studio Code, I was able to quickly and easily find all of the information requested and submitted the final report below to the election commission:
```
Election Results
-------------------------
Total Votes: 369,711
-------------------------

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

-------------------------
Largest County Turnout: Denver
-------------------------
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------
```
## Challenge Summary
I would recommend the Colorado Board of Elections to continue using the code I created for future elections. The variables can easily be swapped to analyze data for any election. The board can also share this code with the county commissions for them to modify for local elections as well. Should the Board move from a popular vote system to an electoral college system, each county could be assigned a "weight" to reflect the number of votes represented by each county. These modifications can all be made by someone with almost any amount of Python experience.
