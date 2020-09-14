# Module 2 Final Project - Predicting NYC Public School Graduation Rates
Numen Rubino and Yasir Karim

Sources: NYC Open Data
## Introduction
We set out to use linear regression to solve a certain problem. Our approach was driven by our desire to work on an education sector related problem. Our search for suitable datasets was conducted keeping that goal in mind. We selected to work with data extracted from the website New York City Open Data. We setteld on predicting graduation rates based on the collected High School data.
## Data Exploration and Cleaning
We found two datasets fit for this project. One of them had graduation rate, class size and test results related to High School in New York City. However, we needed more appropriate features to work with. The second dataset provided us wuth demographic information about aforementioned schools. Therefore, the question arises, how does different demographics influence graduation rate of public schools in New York? We proceeded to clean these datasets in order to merge them and have our train and test sets ready.

For analysis and cleaning on the csv files from NYC Open Data website :

`see:` [Data_Cleaning_v1.ipynb](https://github.com/Mycotic/graduation-regression/blob/master/Data_Cleaning_v1.ipynb)

For the modelling process on the train data and final prediction on the holdout :

`see:` [Regression-on-full-train.ipynb](https://github.com/Mycotic/graduation-regression/blob/master/Regression-on-full-train.ipynb)

For the final presentation detailing our project :

`see:` [Regression_presentation.pdf](https://github.com/Mycotic/graduation-regression/blob/master/Regression_presentation.pdf)

### Queries:

```
1. How do different demographics effect graduation rates in NYC High School?
2. Do minority students graduate at a lesser rate than White students?
3. Do certain groups of students perform better when they are in an isolated environment?

```


## Conclusion
* Specialized students groups such English Language learners and Special Ed. students have lower graduation rates.

* Minority Groups such as Asians and Black students also graduate at a lower rate.

* However, as the absolute number of a group of students increase in a school, their graduation rate decreases at a much lower rate and eventually begins to increase again.

### Applications
* Graduation requirements might need to be revised for specialized groups.

* Further assistance needs to be provided to minority students like the SEEK program of CUNY

* Revise acceptance policies or affirmative action policies.


### Further Analysis
- We can use financial information like household income to analyze its effect on graduation rate on top
of the demographics.

- How does the geographic location factor into getting into certain schools for minority groups?

- Use population graduation rates of minorities as a balancing feature

