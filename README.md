# Election_Analysis

## Overview of Election Audit
After completion of the initial audit, the election commission has requested some additional data to complete the audit. The commission wants: 
the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout.

## Election Audit Results

-How many votes were cast in this congressional election?
Total Votes was 369,711, and I got this by adding votes from each row to total_votes.

-Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Jefferson: 10.5% (38,855), Denver: 82.8% (306,055), Arapahoe: 6.7% (24,801). I got these numbers from using a for loop to get the county votes by county_name from the county dictionary. Then calculate percentage of votes by taking county_votes and dividing by total_votes.
-Which county had the largest number of votes?
Denver had 306,055, 
-Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Diana DeGette received 272,892 votes, which is 73.8% of the total votes. Charles Casper Stockham got 85,213 votes which is 23% of the total votes, and Raymon Anthony Doane received 11,606 votes which is 3.1% of the total votes.
-Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette received 272,892 votes, which is 73.8% of the total votes.

### Election-Audit Summary: 
This proposal outlines a plan for the election commission to use my Election Audit for other elections. All I would need from the Election Commission
is a csv of election data to load into my program. The program will print out total votes, County Votes, Largest County Turnout, the candidates and their recieved votes, and the winner with vote count and winning percentage. All of this information will be printed out in txt file for you to use.   
