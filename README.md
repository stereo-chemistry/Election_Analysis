# Election_Analysis
Module 3
# Analysis of Election Results with Python in VS Code
## Overview of Project
This project is an analysis of election results across 3 different counties and 3 different candidates. The analysis is coded in Python language in VS Code. The csv file of raw data contains 3 columns and 369,712 rows of data. The analysis is conducted with several different variables, lists and dictionaries. For loops and if statements are used to solve for these objects and host their calculations.
### Purpose
The purpose of this project is to generate a working Python script in VS Code that can form election results from a csv file of the election data. Additionally, the purpose of this project is to provide an easy to read output in the form of a text file to communicate these results to any reader. The goal for the Python script is to run through any election data csv file and give output of total votes, votes and percentage of total votes per county, report the county with greatest voter turnout, report each candidate with their percentage of total votes and votes received, report the winning candidate with their vote count and percentage of total votes received.
## Results
* 369,711 votes were cast in this election
* Three Counties were eligible to vote in this election
  * Jefferson County: 38,855 votes: 10.5% of total vote
  * Denver County: 306,055 votes: 82.8% of the total vote
  * Arapahoe County: 24,801 votes: 6.7% of the total vote
* Denver County had the largest number of votes
* Three eligible candidates participated in this election
  *  Charles Casper Stockham: 83,213 votes received: 23.0% of the total vote received
  *  Diana Degette: 272,892 votes received: 73.8% of the total vote received
  *  Raymon Anthony Doane: 11,606 votes received: 3.1% of the total vote
* The winning candidate was Diana Degette with 272,892 votes received; 73.8% of the total vote
## Summary
Given this Python script's successful output and ease of use, I propose this script is reused to analyze any csv file of election data. The code itself can be reused, with some minor adjustments, to analyze any csv stock data. In order to reuse this code, follow the below steps:
* Download the Python script and open in VS Code.
* Move the downloaded Python script into a directory containing a folder of your election data csv files. Create a folder to contain the text file output of your election results. Take note of these folder names and csv file names for the next two steps
* Change file_to_load in line 9 of the code to: file_to_load = os.path.join("folder_name1", "election_data.csv")
* Change file_to_save in line 11 to file_to_save = os.path.join("folder_name2", "election_analysis.txt")
* Once you've run the code, the output will display in the terminal, and the text file of the election results will appear in folder_name2 from the previous step
