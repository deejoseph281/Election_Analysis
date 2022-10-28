# Election_Analysis
 
 A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 
 1. Calculate the total number of vottes cast.
 2. Get a complete list of candidates who received votes. 
 3. Calculate the total number of votes each candidate received. 
 4. Calculate the percentage of votes each candidate won. 
 5. Determine the winner of the election based on popular vote.

 ## Resources
* Data Source: election_results.csv
* Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary

The analysis of the election show that:
* There were 369,711 votes cast in the election. The code used to calculate the total votes required initializing the total voter counter to 0 and then add the total vote count. We begin tracking tthe votes by candidate and county. 
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


## Challenge Overview

The challenge requires an analysis of the votes cast for each candidate in the local election. We need to understand the output for unique candidate names, iterations of the votes counted for each candidate, and the calculation to provide the percentage of total votes for each candidate. 

## Challenge Summary
The challenge requires the use of open() statements, saving files to github through gitbash, dictionary creation, document creation via Python, and variables to be used during if() functions and mathematical equations.
