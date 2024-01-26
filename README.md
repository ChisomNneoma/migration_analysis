# Migration Analysis
- [Project Overview](#project-overview)
- [Tools](#tools)
- [Data Cleaning and Preparations](#data-cleaning-and-preparations)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [View Report](#view-report)


### Project Overview

This report is about one of the Migration companies that assists Nigerian citizens to move to other countries for study or work.
I analyzed the various trends and patterns to better understand the insights relating to migration rate of citizens.

### Tools

- Excel
  - Data Cleaning and Preparations
  - Data Analysis
  - Visualization

### Data Cleaning and Preparations

1. I used ```text-to-column``` function to separate the gender from the name and created a new column for gender.

2. I made the date more understandable by changing the data format.

3. I changed the dataset format to a table by highlighting and Ctrl + T.

4. I created a new column and extracted the year of birth from date of birth, then I created another column and got the generation from the date of birth using the "IFS function".

``` Excel

=IFS([@Year]<=1980,"Gen X",[@Year]<=1996,"Millenials",[@Year]<=2012,"Gen Z")

```

### Exploratory Data Analysis

The analysis answered questions such as

1. Which generation has the highest migration rate?

2. What are the top 3 travel destinations based on education level?

3. Which states have the highest and lowest migration rate?


### Data Analysis

I used pivot table and charts for analysis and visualization.

1. The generation with the highest migration rate:
I did a count of generations on pivot table (drag Generation to row and values), and made a doughnut chart.

2. Top 10 states with the highest and lowest migration:
On a pivot table,
Drag state of origin to rows and values(count)
Sort top 10 and bottom 10.
I inserted a clustered chart to visualize.

3. Travel trends over the year:
On a pivot table,
Drag travel date to rows(select month) and drag month(travel date) to values(count).
In inserted a line chart to visualize.

4. Top 7 travel destinations by gender
On a pivot table,
Drag travel destinations to row and values (count).
Rename to countries(sort top 7).
Drag gender to filter
Insert slicer and bar chart to visualize.

5. Top travel destinations based on education level.
Drag Travel destinations to rows and values(count),
Drag highest level of education to filter.
Insert slicer and clustered chart for visualization.

Create new sheet, remove grid lines and bring in all the charts and slicers for visualization.


### Results and Findings

The Millennials generation has the highest migration rate with 280 migrants.

State with the highest migration rate is Lagos with 46 migrants.

States with the least migration rate are Kaduna, Adamawa, Enugu, Zamfara, Gombe and Jigawa with 7 migrants in each state.

Canada is the top travel destination by both genders(male and female) and also by level of education.

Migration rate is highest in January and lowest in October.


### Recommendations

To reduce migration in Nigeria, explore economic factors influencing migration, such as job opportunities, income differentials, and economic stability. Find out how these factors impact the decision-making of migrants and improve the economy by creating more jobs with reasonable pay and increase security level.


### View Report

To view the complete report which consists of the raw data, migration data(cleaned data), pivot table/charts and dashboard, [CLICK HERE.](https://onedrive.live.com/embed?resid=A3DA6CEAE335B59D%21416&authkey=%21ABHzR3ew6Pnc2FA&em=2&AllowTyping=True&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True)
