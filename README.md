# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has tasked me with performing an election audit for a recent local congressional election and determining the following information:

1. Determine the total number of votes that were cast in the election
2. Get a complete list of all the candidates who participated in the election
3. Determine the number of votes cast for each candidate
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on which candidate won the largest number and percentage of votes

Additionally, the Challenge Assignment required to me to perform a county-level analysis to determine the following information about the election:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total votes cast in the election
3. The county that had the largest turnout for this election

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.5, Visual Studio Code 1.56.2

## Election Audit Results
The analysis of the election showed the following:
- There were 369,711 total votes cast
- The candidates were:
   -   Charles Casper Stockham
   -   Diana DeGette
   -   Raymon Anthony Doane
- The candidate results were:
   -   Charles Casper Stockham received 23.0% of the vote and 85,213 votes
   -   Diana DeGette received 73.8% of the vote and 272,892 votes
   -   Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was:
   - Diana DeGette who received 73.8% of the vote and 272,892 votes

Additionally, for the county-level analysis, the election results showed the following:
- The counties involved in the election were:
   - Jefferson 
   - Denver
   - Arapahoe
- The percent of total votes for each county were:
   - Jefferson had 10.5% of the votes and 38,855 votes
   - Denver had 82.8% of the votes and 306,055 votes
   - Arapahoe had 6.7% of the votes and 24,801 votes
- The county with the largest turnout was Denver

Below are the results of the text file and the command terminal produced via Print statements

Text File:

![Election Results Text File](https://github.com/SethBoswell/Election_Analysis/blob/main/analysis/election_results_notepad.png)

Terminal Output:

![Election Results Terminal Output](https://github.com/SethBoswell/Election_Analysis/blob/main/analysis/election_results_terminal.png)

## Election Audit Summary
If the Election Commission wanted to use this script for any election, they could perform the following modifications on my script. First, they would need to upload a new dataset into my script that contains the information on a different election. Second, they would need to change the name of the output file so that it wouldn't overlap these election results. Specifically, consider the below lines of code from my script:

![Election Results Example Code](https://github.com/SethBoswell/Election_Analysis/blob/main/Resources/example_code.png)

If the Election Comission wanted to run an analysis on an Illinois election, they would upload a new dataset, perhaps named "illinois_election_results.csv" and adjust the first line of code accordingly. If the dataset was formatted in a different way, they would need to modify the scrips to adjust for any formatting differences. Then, they would need to change the second line of code to be a different text file name such as "illinois_election_results.txt".

