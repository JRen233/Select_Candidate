Read me CSCI 5801
Project Prepared by Team 5

# Team Members -

1. Pengyin Chen (chen6636)
2. Junren Huang (huan1852)
3. Jian Wang (wang8635)
4. Shuai Hao (hao00009)

# Purpose:
The purpose of this README is to describe the Voting System that is being
developed as a part of the class project for the class CSCI 5801 - Software
Engineering I at University of Minnesota (Twin Cities). The intended audience for
the document includes the instructor of the class, teaching assistants and
fellow classmates. Also this README would be used to explain various parts of
the project including the directory structure of the Project1 repository,
the various files used and their intention/work and also the various locations
these files are.


# Scope:
The Voting System software was developed for everyone, such as programmers,
testers, election officials and students who want to learn and use Voting System
software. This Voting System software focuses on two types of voting, such as
Plurality and Droop Quota. Voting System can handle prompt users for a filename, 
seats number, algorithm choice, shuffle option. It could provide functionalities like
export the output file, audit file, report and display winners, randome select winner
when tie, and share the election's result. The Voting System software will develop
in Java programming language by providing all the sources files, and the program
will run from the Eclipse. The system will read the input file, and it
will be comma-separated values for the ballots where each row is separated by a
new line. The system will assume that security needed.

# Overview:
The voting system would ask the user to select the appropriate voting algorithm
with the name of the input files and the number of seats that need to be filled 
in the interface. The voting system will be printing the results of the election 
to the interface and the user will also be able to see the result as a audit file.
The Audit is indicated at the end of the detail display of the interface. 

# Directory Structure:
/Project1
/src
Contains all the source code files and Junit test file for the project. The files includes:

	Candidate.java
    Ballot.java
    VotingType.java
    Plurality.java
    DroopQuota.java
    MyGui.java
    TextAreaOutputStream.java
    CandidateTest.java
    BallotTest.java
    VotingTypeTest.java
    PluralityTest.java
    DroopQuotaTest.java
/testing 
Contains all test file. The files includes: 

    Plurality_test_5000b_4c.cvs
    Plurality_test_100b_7c.cvs
    DQ_test_20b_7c.cvs 
    DQ_test_20b_6c.cvs 
    DQ_test_Invalid_1.cvs
    DQ_test_Invalid_small.cvs 
/documentaion
Contains all documentaion generated by Javadoc

- buglist
Contains all bug we discover so far 

- Readme.md 
COntains description and instrcution of this project

# Running the Voting System
To run the Voting System
users can downlaod form git hub as a jar file 
open as a Java project from Ecplise 
Run MyGui.java
Note: the file name should be its absolute path not just the file name
# Expected Working of Voting System
Assuming that the user is able to run the system as discussed in the previous
section, the Voting System will immediately shown on your screen and you can see
your option to input necessary info and button choice. Once all the user
input is processed the system will implement the voting algorithm and print the
results of the election back to the standard output.


# Assumptions Made
- All test file are well organized 
- If you wanna import multiple files, make sure the two files have the same candidates 
- No security issue 

# Testing Project1 (JUnit Test)
To run the Junit tests for different parts of the voting system users can
run different Junit test file in src dirtectory directly

# Testing Project1 (GUI)
Users can also run MyGui.java and import test file and turn shuffle option off so that 
you can have a constant result. Remember to restart every time you test a new file 
