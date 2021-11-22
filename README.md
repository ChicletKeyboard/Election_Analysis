# Analyzing Election Data in Python

## Overview of Election Audit
This project was used to count ballots of a local congressional election. The analysis conducted included data on total votes, votes for each canidate, and voting by county. The end result was to calculate and display the winner of the election for others.

## Election Audit Results
Below is an image of the summarized election results.
![Election Results](https://github.com/ChicletKeyboard/Election_Analysis/blob/18a7d30f6be9ba3829455ca489e7404c804474cc/analysis/election_results.PNG)

In total, 369,711 votes were cast in the election. Denver was by far the most influential district in the election casting 306,055 votes for 82.8% of the total. Jefferson county with 38,855 votes was in distant second, and Arapahoe was the smallest voting contigent with 24,801 votes for 6.7% of the total.

Diane DeGette won the election with 73.8% of the votes with 272,892 constituents voting for her. Charles Casper Stockham received just over 85,000 votes for 23% of the votes, and Raymond Anthony Doane was a very distant third with just 3.1% at 11,606 votes.

## Election Audit Summary
The workflow outline in the code conducting the analysis can be applied to other elections as well. Data can be compiled by county to determine the winner of other races ranging from local councils, up to federal elections. The current implementation is not a secure way to count votes, as all it does is tally data from a chosen CSV file. In the future, I recommend that the code only be able to run for files from a secure server that the election commission runs.
