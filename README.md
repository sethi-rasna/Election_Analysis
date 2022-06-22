# PyPoll Election Analysis
## Overview of Election Audit
The purpose of this election analysis was to use Python to determine the outcome of this precinct's election. We were able to determine not only who won the election but we also determined the turnout of each county in the precinct and determined which county had the best turn out. 
  
## Election-Audit Results
  - How many votes were cast in this congressional election?
    - There was a total of 368,711 votes cast in this election. 
  - Provide a breakdown of the number of votes and the percentages of total votes for each county in the precinct.
    - Here is a breakdown of the number of votes and percentages of total votes for each county:
      - Jefferson County: 10.5% (38,855)
      - Denver County: 82.5% (306,055)
      - Arapahoe County: 6.7% (24,801)
  - Which county had the largest number of votes?
      - Denver had the largest number of votes
  - Provide a breakdown of number of votes and the percentage of total votes each candidate received.
    - Here is a breakdown of the number of votes and the percentages of the total votes each candidate received:
      - Charles Casper Stockham: 23.0% (85,213)
      - Diana DeGette: 73.8% (272,892)
      - Raymon Anthony Doane: 3.1% (11,606)
  - Which candidate won the election, what was their vote count, and what was their percentage of total votes?
    - Diana DeGette won the election with 272,892 votes and 73.8% of the total vote count.
 
## Election-Audit Summary
As long as the CSV file for additional elections follows a similar format, this script can be used for just about any election. Of course, if the format is different, the labels for the categories must be assigned to the right columns in the CSV file. For instance, right now:
        
        # Get the candidate name from each row.
        
        candidate_name = row[2]

        # 3: Extract the county name from each row.

        county_name = row[1]  

However, if the county name and candidate name were a different item in each row, it would have to be labelled accordingly. Additionally, other categories can be added to this list, including states for instance, if a national election was to be considered. While we did not have the ability in this capacity to do so, it would also be interesting to look at the analysis of how each candidate did in each county.
