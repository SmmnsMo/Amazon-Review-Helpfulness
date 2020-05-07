# Amazon Review Helpfulness
This project dives into what makes Amazon reviews helpful and creates a Natural Language classifier to predict if reviews are helpful or not.

## Data Acquisition and Cleaning
The data was downloaded from https://nijianmo.github.io/amazon/index.html

Data acquisition and cleaning are split up into two steps: Data Wrangling and Data Cleaning.
Data Wrangling a sample from each dataset and merges each sample with their respective metadata.
The Data Cleaning step takes the samples and consolidates all of them into a single file - cleaning and making all columns consistent with one another.

## Data Story
The Data Story takes the data that's been cleaned and translates them into insights. In this file I create a Naive Bayes classifier to the review text and summary text to uncover what words stand out as helpful and unhelpful. I also dive into the factors that make a review helpful. This includes the effect that time has on helpful reviews, length of review/summary, types of words and trends that emerge from the dataset. 

## Statistical Inference
In the statistical Inference I explore the differences between helpful and unhelpful reviews and summaries. I've created visualizations of the counts by buckets and tested whether the two groups are significantly different from one another. 
