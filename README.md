# ELECTION ANALYSIS
--------------------------
The Colorado Board of Elections gave us the following tasks in which we were to do an audit of tthe recent congressional election
  1. Calculate total # of votes
  2. A list of candidates that received votes
  3. Calculate the total # of votes each candidate received
  4. Calculate the % of votes each candidate won
  5. Determine the winner of the election based on the popular vote
--------------------------
# RESOURCES
  1. election_results.csv
  2. VS Codem Python
--------------------------
# SUMMARY
After running our script, we find that there were 369,711 total votes cast in the election.
  
  - The candidates were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane
  - THEIR RESULTS:
    - Stockham had 23% of the total votes with 85,213
    - DeGette recieved an amazing 73.8% of the total votes with 272,892
    - Doane received just 3.1% of the votes with 11,606

The obvious winner was Diana DeGette with almost 3/4 the votes being in her favor.
---------------------------
# CHALLENGE OVERVIEW
  The commission also requested additional data for the audit 
    - Voter turnout per county
    - % of votes fromm each county out of the total count
    - The county with the highest turnout
    
----------------------------
# CHALLENGE SUMMARY
  The purpose of this election audit analysis was to determine the number of votes per county and which county had the highest turnout for voters. We can compare each county against the total number of votes collected to analyze which county had the most people engage in voting.
  
![Screen Shot 2022-07-21 at 11 47 52 AM](https://user-images.githubusercontent.com/107223178/180261494-0d9d4d3f-1096-4408-a4bf-c2ebb39dfd27.png)
  
   - 369,711 votes were cast in the election.
   
   - The counties were
     1. Jefferson
     2. Denver
     3. Arapahoe
   
   - The county results were
     1. Jefferson had 10.5% of the vote and 38,855 votes total
     2. Denver had 82.8% of the vote and 306,055 votes total
     3. Arapahoe. had 6.7% of the vote and 24,801 votes total
  
 # AUDIT SUMMARY
   This script can be modified to determine the relationship between turnout for counties and for counting candidate votes with any election by changing the contents of the dictionaries used here to represent which candidates were involved and which counties were involved. The script can also be modifed to change the way we can view the results displayed. Lastly, we can totally add more parameters for the script to call to such as sex, race, etc.
  
  
  
