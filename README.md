# Kickstarting with Excel

## Overview of Project

Louise’s play, "Fever", came close to its fundraising goal in a short amount of time. Now, Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose

Using the initial Kickstarter dataset, provided by Louise, we should be able visualize and recommend campaign outcomes based on their launch dates and their funding goals.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The first analysis was to create a pivot table to analyze success, failure and cancellations based on Louise's desire for Theaters.  To help narrow a starting point, we took the data over the course of many years, and summarized it by the twelve months to ascertain seasonality success.  Adding the filters, for other parent categories and years, if we desire to utilize for other projects.  The line graph, Theater_Outcomes_Based_on_Launch_Date, is a visual representation of the below pivot table.

<img width="323" alt="Screen Shot 2021-12-18 at 12 09 21 PM" src="https://user-images.githubusercontent.com/91889241/146651491-d4ec2dd0-5a33-4bcb-bd3b-aae33b46c1a7.png">

### Analysis of Outcomes Based on Goals

The second analysis is meant to refine this table to include the sub category plays and to see the optimum dollar amount for successful goals.  By breaking the funding goals into groups of $5k and applying that over the entire population of Theaters/Plays, we derived a percentage success, failure, and cancelled.  The Outcomes_vs_Goals.png line graph provides a visual information based on the following pivot table results.

<img width="706" alt="Screen Shot 2021-12-18 at 12 09 45 PM" src="https://user-images.githubusercontent.com/91889241/146651503-5be84fb4-f095-4313-83b8-f2321ff5ed49.png">

### Challenges and Difficulties Encountered

There were no noted challenges while assimilating this data set.  However, potential error that can influence undesirable outcomes would be duplicate information, which can skew the results.  Also, any spelling errors in the categories or in goal and pledged amounts where our formulas are based to derive the pivot tables can cause loss or misinformation in the data set.

## Results

- Two conclusions we can draw form the first analysis is;
  1) The winter holiday season tends to have a higher failure rate to success as a group than other times of the year.  It would be best to not start or expect to finish a fundraier during this period.
  2) The beginning of spring into summer produces the highest rate of success to failure.  It would be best to start at spring and end prior to the winter season to achieve the best success.

- From the second analysis, we can conclude that the best success rate hits a desirable of less than $5,000 and ~73% and greater.  The $35,000 to $40,000 also has a ~67% success rate but the sample size is too small to make it a comfortable attempt to try.

- There are some limitations to this data set.  One being, data is only as good as its source.  We don't know how complete or honest people were when submitting this data to be compiled.  There is always room for error and misinformation.

- The data set itself, is relatively small overall and when factoring in country, the numbers get squeezed even more.  The less data may not reflect a true trend in the population and we did not apply any statistcal factors to adjust one way or the other.

- We could also enhance our visual presentation with stacked bar graphs to give a sense of each category into istelf amongst the other categories.

- We could also apply statistics to examine our standard deviation of the population and plot out a box graph to represent it.
