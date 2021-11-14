# Election_Analysis

## Overview of Election Audit: 
Tom and I are going to go over the tasks the need to be completed for the election audit and discus the information that is needed by the Colorado Board of Elections. After discussing the goals in detail, Tom is going to show a technique commonly used by programmers to write steps of their code also known as 'Pseudocode'. Pseudocode will make the audit easier to presesnt to nontechnical colleagues and stakeholders.

![1](https://user-images.githubusercontent.com/23488019/141696918-28a6de87-bae7-403c-b6b8-0998a763bcde.PNG)

PicCourtesy: https://courses.bootcampspot.com/courses/791/pages/3-dot-0-4-welcome-to-pypoll?module_item_id=299561

### Background:
In this project i will be assisting Colorado Board Of elections employee Tom, in an election audit of the tabulated results for US Congressional precinct in Colorado. I am tasked with reporting the total number of votes cast, the total no of votes from each candidate, the percentage of votes for each candidate and the winner of the election based on the popular vote. There are 3 primary voting methods that Tom and I will take into account: Mail-in ballots, punch cards and direct recording electronic or DRE counting machines. mail-in ballots are typically hand counted at the central office. Punch cards are collected and then fed into a machine that tabulates vote totals and sends the results to the central office. The memory cards from the DRE machines are sent to the central office and read by a computer. Altogether the votes cast by these 3 methods will determine the final results. After the votes are counted, my job is to generate a vote count report to certify the US Congressional race.


![3](https://user-images.githubusercontent.com/23488019/141696967-f6cfccab-556a-47d4-824c-98557eb5e3dc.PNG)

PicCourtesy: https://courses.bootcampspot.com/courses/791/pages/3-dot-0-4-welcome-to-pypoll?module_item_id=299561

### Tools Used:

This task is usually done in Excel but Tom's manager wants to know if there is a way to automate the process using Python. If this audit is done successfully with Python then the code written would be used to audit not only other congressional districts but also senatorial districts and local elections. We will be using Python to write algorithms that will assist the confirmation and analysis of election results. Python is one of the most popular programming languages. It's the newest power tool among programming languages. Although it is not new to the programming world, it is quickly becoming the "go-to" language for first-time programmers. The popularity of Python is due to the fact that it emulates the way a human thinks, which facilitates the process of writing code.  
Before opening the CSV it was needed to make a connection to the file by using computer's directory "path" to that file. Once th file is connected, the contents of the file can be accessed. Gitbash and Github were used to add, commit and push our analysis.


### Resources:

- Data source - election_results.csv file is an Excel file with given data.
- Software - Python 3.7.8, Visual Studio Code
- Output - election_results.txt.
- Add,commit,push - GitBash and GitHub
        

### Purpose and Goals:
The purpose of this project is to analyze the data from voters so that we can complete an election audit for a State Representive election for the election commission.
In this project, the Python script will need to deliver the following information:
1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote.
In addition, the following was requested from the Election Commission:
6. Calculate the voter turnout for each county.
7. Calculate percentage of votes from each county of the total counts of votes.
8. The county with highest voter turnout.

### Procedure:
1) Before you open the CSV it was needed to make a connection to the file by using computer's directory "path" to that file. once th file is connected, the contents of the file can be accessed. 

2) Since the file election_results.csv is in the Resources folder, the path to the CSV can be written as

Resources\election_results.csv

3) After connecting to our election_results.csv file, we can now read, process and parse or analyze the data in the file. For this purpose we will use packages or modules, also called as 'Dependencies'. Dependencies help in increasing the functional programming of the ocde or speed and efficiency. The next stpes are discussed in the following sections.

### Analysis of Election Audit:
This analysis of the election audit could show how we could get the election results out of the csv file contatining the data. We were able to find out the candidate winning the election, most turnout for a county and the specific date as percentage of the poll. Also the specific votes according to each candidate could be found.

- The analysis started by adding the dependencies. We assigned a variable to load the file from a path. A variable was assigned to save the file to the path.

![51](https://user-images.githubusercontent.com/23488019/141694921-a8ee6051-09f7-414b-8e06-d1a7ddd09ffe.PNG)

- We then initialized the total votes counter. Alist was created in order to identify all the candidate names and a dictionary was created for candidate votes. a separate list was created in order to identify all the counties and a dictionary for county votes.

![52](https://user-images.githubusercontent.com/23488019/141695078-0ec78cb3-b9a3-45d8-b8d1-0c26a1cbbccd.PNG)

- For tracking the winning candidate, vote count and percentage, various variables were created. Variables were also created to track the largest county and county voter turnout.

![53](https://user-images.githubusercontent.com/23488019/141695144-5693fc11-9a2f-4eb6-b13b-ecae57baa481.PNG)

- In order to begin interpreting the data, we first needed to use Visual Studio Code to read the csv and convert it into a list of dictionaries. We then opened the data source (election_data). Here, we created total_votes variable and started counting the total number of votes within the data source.

![54](https://user-images.githubusercontent.com/23488019/141695225-77a5dd2b-1d2d-41c8-91fb-c6b29665ff03.PNG)

- From each row, candidate names were taken and by using if statement, a list of candidate names was made to start tracking their voter count and thevotes were also being checked.

![55](https://user-images.githubusercontent.com/23488019/141695338-301278ae-8e97-49b0-a6e8-be1e80ef35a5.PNG)

- If statement was used to identify each county and their votes
![56](https://user-images.githubusercontent.com/23488019/141695424-12bfaf58-7bd3-46f8-bcce-5a72541e5032.PNG)

- A text file was opened and the results were written in it.

![57](https://user-images.githubusercontent.com/23488019/141695461-1f97639e-b046-40f2-9af0-fe8f3d94884e.PNG)

- Now, a for loop was created so that we can retrieve the county vote count. we can also calculate the percentage of votes for each county. These calculations were printed to the terminal and the results were saved to the text file. An if statement was  used to determine the winning county. Following that the winning county was printed to the terminal and saved to the text file.

![58](https://user-images.githubusercontent.com/23488019/141695566-154af2b9-ee51-4ee6-b082-a332c072b36d.PNG)

- Similarly, vote count and percentage for each candidate was retrieved so that we can get the winner and we could print the data in the text file.

![59](https://user-images.githubusercontent.com/23488019/141695632-0bdbf1e2-768a-41d7-bec3-a0b7fdd4764f.PNG)


## Election-Audit Results: 
#### Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

### 1)How many votes were cast in this congressional election?
There were 369,711 total votes cast.

![19](https://user-images.githubusercontent.com/23488019/141694453-f16edc87-7e5b-4cde-9edf-271a990f5010.PNG)

### 2)Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
There were total 38,855 votes casted from the Jefferson county. 306,055 votes were casted in Denver and 24,801 in Arapahoe.

![countyvotes](https://user-images.githubusercontent.com/23488019/141695992-30197e14-458d-4404-95e4-1b353f1d2e31.PNG)


### 3)Which county had the largest number of votes?
Denver had the largest turnout of voters, total number of votes coming from Denver were 306,055. 

![denver](https://user-images.githubusercontent.com/23488019/141696002-f688e567-e8a3-494b-87ed-f74a957d7903.PNG)

### 4)Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Charles Casper Stockham received 85,213 votes which was 23.0% of the total votes casted. Diane DeGette received 272,892 votes which was 73.8% of the votes casted. Raymon Anthony Doane received 11,606 votes which was 3.1% of the votes casted.

![23](https://user-images.githubusercontent.com/23488019/141694871-a82d8258-7cf0-4a53-bbf2-7ac728f759a0.PNG)

### 5)Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
The winner of the election was Diana DeGette with 272,892 votes. It was 73.8% of the total votes.

![17](https://user-images.githubusercontent.com/23488019/141694514-e0d28e83-549e-4541-87c1-969fc54895df.PNG)

The snapshot of the final results can be seen below:

![final result](https://user-images.githubusercontent.com/23488019/141695981-a936f24d-a73d-42f8-a5b7-f6b98eef9da8.PNG)

Also, the snapshot of the text file where the results were stored can be seen below:

![text result](https://user-images.githubusercontent.com/23488019/141696071-5a89d65a-0a2e-4937-977e-5f231ecb9c61.PNG)

## Election-Audit Summary: 
#### In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

In this project we handled the election data and calculated a number of results based on th egiven data in the csv file. The results generated were then saved to a text file. Use of VS code was extremely helpful in finding quick errors because of the color coding.it was easier to use the tabs as well as I could keep track of missing tabs. The script written in this project can be used in a number of other election analysis. The data like number of votes cast by county and candidate, total number of votes and winners could be easily retrieved. Most of the elections might have more than 3 candidates. Hence the code can be modified accordingly. This feature will make the code adaptable to any election and can be used for the analysis. There can be a number of modifications done on this script. A few that can be incorporated are discussed below:

- The script should deal with the case of a tie, as in when two candidates have same vote counts. That would trigger a need to have re election.

- This script can also be used to load an excel file instead of a .csv file. This can be done by editing the filename used in the code above. An extension of .xlsx should be used instead.
- 
![66](https://user-images.githubusercontent.com/23488019/141696762-48d82d6c-60d2-4d5c-a2da-3d228e6c0783.PNG)
Here we can change the file format.

- As we found the winners for the election, modifications could be made to get the loosing counts as well. Instead of using the greater than sign, a less than sign could be used for this purpose.

![67](https://user-images.githubusercontent.com/23488019/141696802-95f5c5ec-a7ef-4b34-98a5-d28352d4704e.PNG)

Here, we could change to '<' and get the losing county data.











