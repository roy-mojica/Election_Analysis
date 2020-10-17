# Election_Analysis

<img src="https://github.com/roy-mojica/Election_Analysis/blob/main/Resources/CO_Sec_of_State_logo.png" heigth="125" width="125">

## Project Overview

The Colorado Board of Elections has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. The voter turnout for each county.
3. The percentage of votes from each county out fo the total votes cast.
4. The county with the highest turnout. 
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received. 
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote. 

## Resources

- Data Source: election_results.csv
- Software: Python 3.6.7, Visual studio Code, 1.50.1
- CO Logo from [Link](https://www.google.com/url?sa=i&url=https%3A%2F%2Fbrady.jeffcopublicschools.org%2Fnews%2Fnews%2Fcolorado_voter_registration_information&psig=AOvVaw3TiraYJ1tsTYOnhQbvOEQ0&ust=1602976581361000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCICJwqKfuuwCFQAAAAAdAAAAABAD)

## Election-Audit Results

The analysis of the elction show that:

- There were 369,711 votes cast in the election. 
- The County results were
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
-The county with the largest votes was:
  - Denver
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were 
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was:
  - Diana Degette
 
## Election-Audit Summary

This script works well for a single congressional district. However, this could be modified so that we can see the same results across all districts state-wide. We could acomplish this by also adding a "district" list/dictionary in the code. Where right now we only can go up to county. 



We could also update this could to show the method of voting people utilize across the state to get a betting understanidng of voting preferneces and address any potential lack of access to vote. We would need to capture that data in the data file in ordert add this to the scipt. 



## Challenge Summary
