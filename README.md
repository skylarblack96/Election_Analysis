# Election_Analysis

## Election-Audit Overview
The purpose of this election audit analysis is to aid the Colorado Board of Elections with their election results. A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Calculate the voter turnout for each county
3. Calculate the percentage of votes from each county out of the total count
4. Determine the county with the highest turnout
5. Get a complete list of candidates who recieved votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The counties were:
    - Jefferson
    - Denver
    - Arapahoe
- The county results were:
    - Jefferson county with 10.5% of the vote and 38,855 number of votes.
    - Denver county with 82.8% of the vote and 306,055 number of votes.
    - Arapahoe county with 6.7% of the vote and 24,801 number of votes.
- The largest county turnout was:
    - Denver county, receiving 82.8% of the vote and 306,055 number of votes.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham with 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette with 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane with 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette, receiving 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
The script written for this analysis can be easily manipulated to fit any future election that needs analysis. At the top of the script is where the data is imported. To upload the new data come a new election, replace the current file name, "election_results.csv", with the new election data file name and path. Additionally to save the new results, a new file name will have to be created in place of, "election_results.txt." Overall, the script is easy to reuse because of the variables assigned to different rows and columns in any csv file you choose to upload.
