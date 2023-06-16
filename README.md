# Modelling-Uncertainty-for-Requirements-The-case-of-Surprise-Results

This is the GitHub repo for the results of "Modelling Uncertainty for Requirements: The case of Surprise"; there are four major files for the results, two for Bayesain surprise and two for confidence correct surprise. within the two groups the two files will be an "_avg" file and a "_classes" file, the former contains the average result for each scenario over 5 runs for the different techniques discussed in the paper, the later contains the classifications for each non-functional-requirement (NFR).

The classes file is the simplest, within this file results are broken down first by scenario and then by NFR, there are 5 classes labeled low to high risk, with 10 groupings each. The groups correspond to intervals of 0.1 for all values between 0 and 1, and are represented by their lower bound so group 0.2 represents the intervals 0.2 to 0.3.

The avg file contains the average result for each scenario over its 5 runs and is constructed as follows:
  The scenario number and title is given (latter is always avg)
  The average values for each groups membership are given for both the groups themselves and their subsets where failure occurs
  The average failure rate for an entire NFR is listed next
  After that is ratio 1, this gives the failure rate given as a decimal between 0 and 1 for each group, this will also apply to the next 2 ratios
  Ratio 2 gives the proportion of failure belonging to each group
  Ratio 3 gives the proportion of members belonging to each group
  Ratio 4 gives ratio 2 divided by ratio 3, and simply makes comparisons between the amounts slightly easier

  After this is the each groups breakdown, the specific NFR is listed followed by the interval number (given by its lower bound) and this is followed by relevant metrics
    The number of group members is given ("number of occurences")
    The failure rate is given ("Percentage of surprise")
    The proportion of failure is given ("Proportion of surprise")
    The proportion of group members is given ("Proportion of occurences")
    Lastly the sub-groupings for the other NFR chosen are given alonside the amount each sub-group has
    
    
