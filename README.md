# Election_Analysis1
Repository for holding Module 3 classwork code

The PyPoll.py file contains code for Module 3 coursework. Module 3 introduced us to Python's basic functions and reading and writing to a file. 

PsudoCode for PyPoll.py

Add dependencies by importing CSV and OS
Assign a variable to load the election results csv file into memory. 
Assign a variable and the path to write the analysis back to the text file called election_analysis.txt.

Initialize a total vote counter so percentages by candidate can be calculated. 
Initialize 2 candidate list variables for 1)any candidate receiving votes (candidate_options) and 2) vote totals (vote_totals)
Initialize variables for winning candidate (string variable)
Initialize variable for winning candidate vote count
Initialize variable for winning candidate percentage of the vote

Open the election results file and read the file
Read headers first and write the headers to file
Read file to determine candidates name and add to candidate options if not already in the file -- and then increment their vote count. 
continue until all votes counted. 

Save results to the text file election_analysis.txt and write:
  Election Results
  Total Votes (total votes)
  
Compute final vote count per candiate and percentage based on total votes cast. 
write to file
Compare each candidate's vote count to previous candidate and save if higher
Print final results as winning results. 

Save the results to the election_analysis.txt file. 


  
