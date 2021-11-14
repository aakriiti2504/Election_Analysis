# Election_Analysis

## Overview of Election Audit: 
Tom and I are going to go over the tasks the need to be completed for the election audit and discus the information that is needed by the Colorado Board of Elections. After discussing the goals in detail, Tom is going to show a technique commonly used by programmers to write steps of their code also known as 'Pseudocode'. Pseudocode will make the audit easier to presesnt to nontechnical colleagues and stakeholders.

### Background:
In this project i will be assisting Colorado Board Of elections employee Tom, in an election audit of the tabulated results for US Congressional precinct in Colorado. I am tasked with reporting the total number of votes cast, the total no of votes from each candidate, the percentage of votes for each candidate and the winner of the election based on the popular vote. There are 3 primary voting methods that Tom and I will take into account: Mail-in ballots, punch cards and direct recording electronic or DRE counting machines. mail-in ballots are typically hand counted at the central office. Punch cards are collected and then fed into a machine that tabulates vote totals and sends the results to the central office. The memory cards from the DRE machines are sent to the central office and read by a computer. Altogether the votes cast by these 3 methods will determine the final results. After the votes are counted, my job is to generate a vote count report to certify the US Congressional race.

### Tools Used:

This task is usually done in Excel but Tom's manager wants to know if there is a way to automate the process using Python. If this audit is done successfully with Python then the code written would be used to audit not only other congressional districts but also senatorial districts and local elections. We will be using Python to write algorithms that will assist the confirmation and analysis of election results. Python is one of the most popular programming languages. It's the newest power tool among programming languages. Although it is not new to the programming world, it is quickly becoming the "go-to" language for first-time programmers. The popularity of Python is due to the fact that it emulates the way a human thinks, which facilitates the process of writing code.  


### Resources:

election_results.csv file is an Excel file with given data.

### Goals:

In this project, the Python script will need to deliver the following information:
1.Total number of votes cast
2.A complete list of candidates who received votes
3.Total number of votes each candidate received
4.Percentage of votes each candidate won
5.The winner of the election based on popular vote.

### Procedure:
1) Before you open the CSV it was needed to make a connection to th efile by using computer's directory "path" to that file. once th efil eis connected, the contents of the file can be accessed. A programming tool such as "  " can be used for this specific purpose.

2) Since the file election_results.csv is in the Resources folder, the path to the CSV can be written as

Resources\election_results.csv

3) After connecting to our election_results.csv file, we can now read, process and parse or analyze the data in the file. For this purpose we will use packages or modules, also called as 'Dependencies'. Dependencies help in increasing the functional programming of the ocde or speed and efficiency.
4) The steps to count the votes of an election like this:
- Open the data file.
- Write down the names of all the candidates.
- Add a vote count for each candidate.
- Get the total votes for each candidate.
- Get the total votes cast for the election.


## Election-Audit Results: 
#### Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

### 1)How many votes were cast in this congressional election?
### 2)Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
### 3)Which county had the largest number of votes?
### 4)Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
### 5)Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

## Election-Audit Summary: 
#### In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.





















