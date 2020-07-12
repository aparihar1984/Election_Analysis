# Election_Analysis
Learning how to use Python by creating a program that tabulated the voting data from three different counties in the state of Colorado during a congressional election.

## Overview of Project/Purpose
Using a given Excel worksheet which contained each voters Ballot ID, County, and Candidate they voted for, I created a program using Visual Studio Code featuring/linked with Python language.  This program tabulated all 369,711 votes in the worksheet to determine which of the three counties had the most votes and which candidate won the election.  This program was then able to write the election results to a text file.

The purpose of the module was to create a program that tabulated the voting data from the Excel worksheet to find out which of the three candidates won the election.  The program accomplished this by counting all the votes and determining the percentage of total votes each candidate received.

The 1st deliverable then added on to the program created in the module by writing code that counted all the votes in the Excel worksheet by county to determine which county had the most votes and the biggest vote percentage.

## Analysis and Challenges
I was able to successfully create a functioning program which determined the candidate that won the election, and which county had the most votes by studying the following module lessons: 

[3.2.2: Run a Python file in the command line of VS Code] (https://bootcampspot.instructure.com/courses/193/pages/3-dot-2-2-execute-python-files?module_item_id=56587)

[3.2.4: Perform Calculations] (https://bootcampspot.instructure.com/courses/193/pages/3-dot-2-4-perform-calculations-using-python?module_item_id=56589)

[3.5.2: Get the Candidates in the Election] (https://bootcampspot.instructure.com/courses/193/pages/3-dot-5-2-get-the-candidates-in-the-election?module_item_id=56609)

[3.5.5: Determine the Winning Candidate] (https://bootcampspot.instructure.com/courses/193/pages/3-dot-5-5-determine-the-winning-candidate?module_item_id=56612)

[3.6.3: Write the Winning Candidate 2019s Results to a Text File] (https://bootcampspot.instructure.com/courses/193/pages/3-dot-6-3-write-the-winning-candidate-2019s-results-to-a-text-file?module_item_id=56617)

The challenging part for me in this assignment was not so much with the actual coding itself, but with the code structuring in the program.  Unlike VBA or C++ which has declaration statements such as "Next i" to end loops (for-loops in that specific case), Python relies more on indentations with the coding itself to allow the program to start and end different loops/conditions etc...

As I was coding, there were many errors when attempting to run the program because of improper indentation.  Once the coding was indented properly, the program ran successfuly.  Because I had previously completed the module code that determined which candidate had won the election, I was able to use that code as a guide to properly write code for the deliverables that determined which county had the most votes, while writing the election results to a text file.

## Election-Audit Results
Here are the results of the election as found by the program:
    - How many votes were cast in this congressional election?
            Answer: 369,711
    - Voter breakdown for each county in the precinct?
            Answer: Jefferson: 10.5% (38,855 votes)
                    Denver: 82.8% (306,055 votes)
                    Arapahoe: 6.7% (24,801 votes)
    - Which county had the largest number of votes?
            Answer: Denver
    Voter breakdown for each candidate in the election?
            Answer: Charles Casper Stockham: 23.0% (85,213 votes)
                    Diana DeGette: 73.8% (272,892 votes)
                    Raymon Anthony Doane: 3.1% (11,606 votes)
    Which candidate won the election, what was their vote count and percentage?
            Answer: Diana DeGette: 73.8% (272,892 votes)

### Election-Audit Summary
One advantage of using a program like this is that it can be used to tabulate voting data from more than three regions.  Data from many regions in a specific state (Colorado in this case) can be added into the original Excel worksheet, and it will be tabulated by the program.  

We can also gather voting data from regions in all 50 states, not just the state of Colorado.  The for loops in this specific program run only for the state of Colorado, but we can add more loops so the program can read and tabulate voting data for regions in all 50 states, then display them separately in a text file if we needed it to.