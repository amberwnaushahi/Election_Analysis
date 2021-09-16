# Election_Analysis

## Overview of Election-Audit

The purpose of the election audit was to assist the Colorado Board of Elections to tabulate results for US Congressional precinct in Colorado. The task encompassed calculating the total number of votes cast, total number of votes for each candidate, the percentage of votes for each candidate and the winner of the election based on popular vote and subsequently generating a vote count report certifying the results. The aim was to automate the process using Python and determine its usability in the future for audit of congressional, senatorial and local elections.

## Election-Audit Result

Using repetition statements, conditional statements with logical operators, and print statements in Python along with reading in the CSV election data set, I created a code in VS Code. The results were written to a text file called election_results.txt. The image below shows the code for initializing variables for the file paths to be read from and written on. These variables were subsequently used to actually read from and write on.  

![image](https://github.com/amberwnaushahi/Election_Analysis/blob/main/Resources/files_read_write.png)

The election audit result revealed the following:

* Total number of votes cast was **369,711**.

* The precinct comprised of three counties, appearing below along with their results:
   * Jefferson had *38,855* votes cast, accounting for *10.5%* of total votes.
   * Denver had had *306,055* votes cast, accounting for *82.8%* of total votes.
   * Arapahoe had *24,801* votes cast, accounting for *6.7%* of total votes. 

* **Denver** had the largest number of votes cast in the entire precinct. 

* There were three candidates running in the elections and received the following votes count and percentage: 
    * Charles Casper Stockham received *85,213* votes, representing *23.0%* of total vote count.
    * Diana DeGette received *272,892* votes, representing *73.8%* of total vote count.
    * Raymon Anthony Doane received *11,606* votes representing *3.1%* of total vote count.
 
* **Diana DeGette** won the election with a total of 272,892 votes which was 73.8% of the total vote count

![image](https://github.com/amberwnaushahi/Election_Analysis/blob/main/Resources/Election_results.png)

## Election-Audit Summary

The script can be used to tabulate and analyze other election results as well by making small modifications to the code.
* If we want to see the candidate who got the most votes in each county, we can modify the code by assigning a new variable such as winner_county and tabulating the result by each candidate name within the loop where county votes are being counted. 
* If we have information regarding total registered voters and total votes that were cast, an analysis can be carried out to understand the voter turn out.




