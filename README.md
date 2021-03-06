# Election_Analysis

## Project Overview
In this analysis, we examine election data in order to automate the process of analyzing the data. The aim of this project, given by a Colorado Board of Elections employee, is to accomplish the following:

1. Calculate the total number of votes cast.
2. Compile a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate won.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote. 

## Resources
- Data sourced from election_results.csv
- Software utilized: Python 3.7.6, Visual Studio 1.68.1

## Summary
From our analysis, we have determined that:
 - There were 369,711 total votes cast.
 - The Candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
 - The results of the election are as follows:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
  - The winner of the elections was:
     - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.


## Challenge Overview
The goal of this part of the analysis was to acheive the following:

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes from each county and the total count.
3. Find the county with the highest turnout.

## Challenge Results
From the analysis, we found:
- The voter turnout for each of the counties are as follows:
  - Jefferson: with 38,855 votes cast, 10.5% of the overall turnout.
  - Denver: with 306,055 votes cast, 82.8% of the overall turnout.
  - Arapahoe: with 24,801 votes cast,  6.7% the of overall turnout.
- The county with the highest voter turnout was found to be Denver

The summary of the voter analysis can be seen in the election_analysis text file within the analysis folder [here](https://github.com/chichi-ugo/election_analysis/blob/main/analysis/election_analysis.txt), and is also depicted below.

![Election Results Summary](https://github.com/chichi-ugo/election_analysis/blob/main/Resources/election_results_txt.png?raw=true)

## Challenge Summary
Overall, the script was able to acheive the goals of this analysis and has the potential to be modified to be used for any election.
- One modification that would need to be made is to review the headers of your unique csv file and change the index numbers as needed to ensure that the correct information is being stored. This is in relation to this section near the begining of the script:
```
    # Get candidate's name from each row
    candidate_name = row[2]
    # 3: Extract the county name from each row.
    county_name = row[1]
```
- Another modification to be made in the script is in changing some of the variables (adding new ones or taking away some) to accomdate for elections at varying levels of goverenment. Where here we looked particularly between counties, it can be modifed to accommodate state wide elections as well.
