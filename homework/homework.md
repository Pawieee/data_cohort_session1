# Module 1 Homework: Data Analysis with Pandas

In this homework we'll prepare the environment and practice data manipulation and analysis using Pandas

When submitting your homework, you will also need to include
a link to your GitHub repository or other public code-hosting
site.

A `homework.ipynb` is initialized for you as well to write your solution.

When your solution has shell commands and not code
(e.g. python files) file format, include them directly in
the README file of your repository.


## Part 1: Data Cleaning and Preparation 

Perform data cleaning and preparation on the following datasets `population.csv`, `housing_data.csv`, and `state_info.csv`

Here's what the following datasets should look like after calling `info()` on the respective dataframes:

1. `population.info()`

| Column              | Non-Null Count | Dtype |
| ---------------- | ------ | ---- |
| id             	| 51 non-null    	| int64  	|
| region         	| 51 non-null    	| object 	|
| state          	| 51 non-null    	| object 	|
| individuals    	| 51 non-null    	| int64  	|
| family_members 	| 51 non-null    	| int64  	|
| state_pop      	| 51 non-null    	| int64  	|

2. `housing_data.info()`

| Column              | Non-Null Count | Dtype |
| ---------------- | ------ | ---- |
| state             	| 51 non-null    	| object  	|
| housing_units     	| 51 non-null    	| int64   	|
| shelters          	| 51 non-null    	| int64   	|
| vacancy_rate      	| 51 non-null    	| float64 	|
| rent_median       	| 51 non-null    	| int64   	|
| overcrowding_flag 	| 51 non-null    	| bool    	|

3. `state_data.info()`

| Column              | Non-Null Count | Dtype |
| ---------------- | ------ | ---- |
| state             	| 51 non-null    	| object  	|
| housing_units     	| 51 non-null    	| int64   	|
| shelters          	| 51 non-null    	| int64   	|
| vacancy_rate      	| 51 non-null    	| float64 	|
| rent_median       	| 51 non-null    	| int64   	|
| overcrowding_flag 	| 51 non-null    	| bool    	|


## Part 2: Data Analysis

## Question 1. Basic Exploration
What are the top 5 states based on average number of individuals per state in the dataset?

- Wyoming, North Dakota, Delaware, Rhode Island, New Hampshire
- California, New York, Florida, Texas, Washington
- Alabama, Alaska, Arizona, Arkansas, California
- New York, California, Texas, Washington, Pennsylvania


## Question 2. Aggregation
What region has a sum of total individuals of 56263, sum of family_members of 20873, and mean state population of 7.247736e+06?

- Pacific
- East North Central
- New England
- South Atlantic

## Question 3.  Merging DataFrames
What is the Pacific region's average rent?

- 2014.25
- 1744.83
- 2081.2
- 2072.3


## Question 4. Merging + Filtering + Aggregation
Which state has the highest housing pressure based on cities where the rent exceeds $2000, the vacancy rate is below 6%, and the population is over 500,000?"

`Housing pressure = rent_median / vacancy_rate`


- North Dakota
- New Hampshire
- Kansas
- Hawaii


## Question 5. Merging + Logical Conditions + Advanced Filtering
Which regions have the highest average rent among states that face both overcrowding and lack of government aid, and have an above-median individual population? List the top 4.
 
 Tip: After filtering for the initial conditions, try using an aggregate function to find the average rent per region and reserve it for later...
- West North Central, Mid-Atlantic, West East Central, Pacific
- New England, Pacific, Mountain, South Atlantic, Mid-Atlantic
- Mountain, East North Central, West North Central, Pacific
- Pacific, Mid-Atlantic, West South Central, East North Central





## Submitting the solutions

* Form for submitting: **`TBD`**