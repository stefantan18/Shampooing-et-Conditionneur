Team Shampooing et Conditionneur (Cheryl Qian, Stefan Tan, Lynne Wang)
APCS2 pd1
L00 -- But What Does the Data Say?
2018-02-08

## Hypothesis
For an n x n 2D array of ints, the worst-case execution of our search algorithm is O(n).

## Background
  For an assignment we were asked if it was possible to make an O(n) search algorithm for an n x n 2D array of ints, wherein numbers increase across any row (L-> R) and down any column. If we thought it was possible then we were told to make either a flowchart, pseudocode, or step-by-step recipe/procedure. If not, we were told to clearly state your case that it cannot be done by justifying/explaining it and using examples. When we came back the next day, all of us came up with a search algorithm that we believed has O(n) runtime. However, we were told that the only way to know for sure was through an experiment with a conclusive result. The goal of this lab is to prove that our search algorithm runs in linear time.   

## Experiment Methodology
  We already have a search algorithm that we coded from a previous assignment and we were then given some methods to help us. We decided to use the System.currentTimeMillis() which returns the time elapsed since epoch. Since the computer runs the search algorithm quickly on small 2D arrays, such as 5 x 5 and 10 x 10 2D arrays, we decided to use 1000 x 1000 2D arrays to 10000 x 10000 2D arrays for a total of 10 2D arrays, incrementing the row and column of the 2D array by a 100 to have usuable results. We also decided to do 20 trials of the search algorithm to make sure outliers don't affect our conclusions. We also decided for all the 2D arrays to search for the worst-case, which for our code is the element at the top right. We created a for loop to create the 2D arrays and also another for loop to run the search algorithm 20 times. We inserted the System.currentTimeMillis() right before the search and right after the search to make sure no other processes affect our data. We subtracted the time we got after the search and before the search to find out how long the search took.  

## Results


## Conclusions
