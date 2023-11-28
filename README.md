# Athletic sales analysis

Explore pandas functionality to combine aggregate and resample time serious data.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Functionality](#functionality)
   1. [Import Libraries and Dependencies](#import-libraries-and-dependencies)
   2. [Read Files](#read-files)
   3. [Show Head](#show-head)
   4. [Combine Three Separate CSV Files (Sales for Jan, Feb, and March)](#combine-three-separate-csv-files-sales-for-jan-feb-and-march)
   5. [Check for Missing Values After Combining](#check-for-missing-values-after-combining)
   6. [Convert Order Date to Date Time](#convert-order-date-to-date-time)
   7. [Show the Average Number of Items Ordered](#show-the-average-number-of-items-ordered)
   8. [Daily and Weekly Sales using Resample](#daily-and-weekly-sales-using-resample)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

In this project I will explore pandas functionality to aggregate using three types of aggregation functions
1. using group by 
2. using pivot table
3. resampling datetime.

## Installation

pandas is the only library required for this project.

```bash
pip install pandas

Functionality
Import pandas
pandas is required to get concat for combining multiple files, to groupby and and aggrigate

Read Files
read January, February and march 2019 data using pd.read_csv function.

Show Head
explore all three data frames using head() functionality.

Combine Three Separate CSV Files (Sales for Jan, Feb, and March)
use concat and inner join functionality to combine all three data frames

Check for Missing Values After Combining
use isna().sum()  functionality to explore missing values.

Convert Order Date to Date Time
conver order date from string to date time using to_datetime functionality.

Show the Average Number of Items Ordered
create a function to group by and aggregate given features and print top n using. 
   groupby and pivot_table functionality

Daily and Weekly Sales using Resample
use resample functionality to extract day, week and month and preform aggregation function such us sum and display.


