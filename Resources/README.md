# Election_Analysis
 
 A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 
 1. Calculate the total number of votes cast.
 2. Get a complete list of candidates who received votes. 
 3. Calculate the total number of votes each candidate received. 
 4. Calculate the percentage of votes each candidate won. 
 5. Determine the winner of the election based on popular vote.

 ## Resources
* Data Source: election_results.csv
* Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary

###Election Audit Results
The analysis of the election show that:
* There were 369,711 votes cast in the election. 
* The breakdown of the number of votes and the percentage of total votes for each county in the precinct were:
* ![image](https://user-images.githubusercontent.com/115019829/198424809-dd43304b-a7cc-412b-9772-a841e433bbb8.png)
* The county with the largest number of votes was Denver. 
* ![image](https://user-images.githubusercontent.com/115019829/198425140-3b5768c9-71a4-44b5-86ed-26bc047d22e7.png)

* The code used to calculate the total votes required initializing the total voter counter to 0 and then add the total vote count. We begin tracking tthe votes by candidate and county. 
* ![image](https://user-images.githubusercontent.com/115019829/198423342-63923d26-85ed-4930-8c4d-90c508db1131.png)
![image](https://user-images.githubusercontent.com/115019829/198423395-cfa6a545-c52c-4e51-a6db-3f52516d6e14.png)
![image](https://user-images.githubusercontent.com/115019829/198423544-ffa92eaa-fc98-4e88-b1d4-0ab55ff0ce6a.png)

* The candidates were:
    * Charles Casper Stockham
    * Diana DeGette
    * Raymon Anthony Doane
* The candidate results used an IFstatement to retreive the candidate's name and total votes. We then utilized a division calculation to output the vote percentage. We then formatted the output to ensure that percentages were displayed as percentages and the votes were in number form with a comma to differentiate it as an integer value. 
    * Charles Casper Stockham received 23% of the vote and 85,213 votes.
    * Diana Degette received 73.8% of the vote and 272,892 votes.
    * Raymon Anthony Doane received 3.1% of the vote and 11,606 votes. 
![image](https://user-images.githubusercontent.com/115019829/198423829-48cafbb6-c99f-4dc6-af93-97f4f8475864.png)
* The candidate who won was Diana DeGette by a landslide of 73.8% of the votes.
* ![image](https://user-images.githubusercontent.com/115019829/198425582-af2d2f8f-6b33-4a56-bb80-8b6cae64a389.png)


## Challenge Overview

The challenge requires an analysis of the votes cast for each candidate in the local election. We need to understand the output for unique candidate names, iterations of the votes counted for each candidate, and the calculation to provide the percentage of total votes for each candidate.
![image](https://user-images.githubusercontent.com/115019829/198465659-1ff349d7-298c-4253-b720-d365b6292a38.png)

Then, we needed to establish the variable and types within an array or dictionary. 
![image](https://user-images.githubusercontent.com/115019829/198466702-df6a53ee-b5c0-4a1c-8cf9-13e57306a363.png)

Once the candidate name and county name was established within a list, each vote for the candidate was tallied. 
![image](https://user-images.githubusercontent.com/115019829/198467572-7427b9df-0422-475a-8cad-bd99c53bf3bc.png)

We then needed to write a for loop to get the county from the county dictionary. The county votes, county name, and county percentages were printed to provide us with the winning county, the number of votes per county, and the county with the largest voter turnout.
![image](https://user-images.githubusercontent.com/115019829/198468276-8b953ab6-e808-45bb-9cfb-e42af1b50329.png)

Finally, we needed to ensure the outputs were in a readable and succinct format that clearly stated the winner's name, the number of votes in number format, and winning percentage in % format.

## Challenge Summary
The challenge requires the use of open() statements, saving files to github through gitbash, dictionary creation, document creation via Python, and variables to be used during if() functions and mathematical equations.

First, we needed to import our data and add the variable to load the file from the path. 


The challenge required automating the process of counting votes and the ability to reuse the code for updated election results. 


### Proposal To Continue Utilizing Script for Future Elections
The script can be used for future elections with some modifications to allow for flexibility within the script. 
The script has advantages in being able to verify the votes by county and by candidate as well as largest voting county and winner of the election. 
We recommend modifications to allow for the script to include critical election results and data including but not limited to, candidate party name and percentage of votes to each party, voter demographic such as male/female and age, county results by candidate and party. 
The script also allows the robust capability of providing interim results based on number of votes cast during early-voting and during the voting day. The election committee can update the data sets as frequently as required to get real-time output of the election results. 
