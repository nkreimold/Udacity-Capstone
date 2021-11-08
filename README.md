# Starbucks Capstone Project


## Table of contents

- [Project Motivation](#project-motivation)
- [Libraries](#libraries)
- [Files included](#files-included)
- [Analysis Results](#analysis-results)
- [acknowledgements](#acknowledgements)


## Project Motivation

Starbucks is a very complex organization with lots of moving parts. One such hurdle they
must overcome is how best to attract customers. Using data provided, I went about analyzing
whether promotional offers could be better distributed to the customer base.

The Questions I was interested in answering:

- What is the distribution of offers made to customers?
- What defines whether someone is likely to respond to an offer?
- Can we better allocate offers based on customer information?

## Libraries

The following libraries are used in this analysis:
- numpy
- pandas
- matplotlib
- seaborn


## Files Included

- Starbucks_Capstone_notebook.ipynb: jupyter notebook with analysis

For each of Seattle and Boston:
- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
- profile.json - demographic data for each customer
- transcript.json - records for transactions, offers received, offers viewed, and offers completed


## Analysis

Initially I conducted exploratory analysis and did any necessary data preparation. At a high level,
I interpolated a few columns with missing data, create some dummy variables, and combined the three
data sets. I also aggregated the customers so we can have a clearer picture of how they repsond to offers.

Overall, our findings were that upon building a recommendation system, we can increase the possible
profit that Starbucks makes. This was evaluated with a hypothetical test set, but further analysis
would have to be done to truly validate it. 


## Acknowledgements

Thanks to Airbnb and Kaggle for the data in this analysis!
