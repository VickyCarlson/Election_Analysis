# Election_Analysis

## Overview of Election Audit

A Colorado Board of Elections employee gave the following tasks to complete the election audit of a recent local congressional election. This project evaluates these tasks to assist the Board of Elections in determining the list of candidates, the winner of the election, and voter turnout statistics.

1. Calculate the total number of votes cast in the congressional election.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate won.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total count.
8. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.60.2

## Election Audit Results
The analysis of the election show that:
- There were **369,711** total votes cast in the election.
- The candidates were:
	- 1 Charles Casper Stockham
	- 2 Diana DeGette
	- 3 Raymon Anthony Doane
- The candidate results were:
	- Candidate 1 received **23.0%** of the vote and **85,213** number of votes.
	- Candidate 2 received **73.8%** of the vote and **272,892** number of votes.
	- Candidate 3 received **3.1%** of the vote and **11,606** number of votes.
- The winner of the election was:
	- Candidate 1, **Diana Degette**, with **73.8%** of the vote and **272,892** number of votes.
- The counties were:
	- 1 Jefferson
	- 2 Denver
	- 3 Arapahoe
- The county results were:
	- County 1 (Jefferson) received **10.5%** of the total number of votes, with **38,855** votes.
	- County 2 (Denver) received **82.8%** of the total number of votes, with **306,055** votes.
	- County 3 (Arapahoe) received **6.7%** of the total number of votes, with **24,801** votes.
- The largest number of votes were cast in:
	- Denver county, with **82.8%** of the total vote and **306,055** votes.

## Challenge Overview

This challenge uses Python in Visual Studio to calculate the results of an election in Colorado. The .csv file contains candidate, county and ballot data. A list and a dictionary were created in Python for both the candidate and the county data. Utilizing a for loop, the values for each county and candidate were summarized as the file was read. As a new county or candidate was read in the file, it was added to the list and votes were summarized. At the end of the file, the results were printed both to the screen and to a text file, showing the data from the *Election Audit Results* above.

## Challenge Summary

 This analysis could be used for a variety of elections with slight modifications. Utilizing a file with results from a different election, the system could calculate the results simply by directing the name of the file to laod in the intial statement to the new results folder. The audit could cover not only a state congressional election like this one, but would also be useful in a national congressional election. The current audit covers the specific counties voting in a state congressional election, but the numbers for the national election for Congress would be larger and the number of counties would include every county in the state. This analysis could be run for a smaller, city-wide election where the precinct would be substituted for the county information. The audit could even be run for a Presidential election with alterations to include each state's vote in addition to (or instead of) the county vote. Please contact our office if you would like to discuss pricing for these various scenarios.