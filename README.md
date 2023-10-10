# Cyclistic Case Study
The purpose of this script is to consolidate downloaded Divvy data into a single dataframe and then conduct simple analysis to help answer the key question: “In what ways do members and casual riders use Divvy bikes differently?”

## Report

The Cyclistic.pdf contains the entire report


## Task 

Our task will be to understand and draw conclusions based on the customers' choice of plans. Since there are customers who opt for the member plan and customers who use the casual plan. Our role will be to identify what this choice entails.

## Tools and processes

I am using the R programming language in this process, as it is a great language for processing large data. Data integrity was maintained through data anonymity. Data cleaning was done using R, cleaning incongruent data (non-standard column names) and formatting dates. Checking data integrity can be done in comparison to the new Divvy Data Cyclits standard, and can also be checked using R's own tools, such as the str() function. The entire cleaning process was documented, as well as each step by step, and the plots.

## Analysis

I organized my data in a data frame, formatted the data according to the columns and their purposes. One of the big surprises was that the average time (in seconds) that a casual member spends on the bike is greater than the average time that an annual member spends on the bike. Therefore, the number of annual members is greater than the number of casual members. And, the customer maximum in seconds is almost 3x more than the annual member maximum.
There is a relationship between the annual customer and the days of the week, leading us to believe that the annual customer uses the bicycle more for daily activities. However, the average time spent using the bike drops drastically when comparing annual members with casual members. Casual members average up to 2x more time on the bike on Saturday.

## What were the insights?

The data shows greater time spent using bicycles by casual members. This finding answers the original question, as it shows that member customers use bicycles more for everyday events. While casual members use them with a higher average on weekends, and for a longer period of time (even on weekdays). My target audience would be those people who spend a lot of their time on bicycles on a casual basis. The data visualizations clearly show a tendency for the casual customer to use the bicycle more depending on time. This can be easily seen by anyone.

## Next steps and conclusions

Therefore, it is possible to conclude that casual customers use bicycles with a greater focus on weekends, and for longer periods of time. While annual customers use bicycles with a greater focus on daily life, and for less time, but in greater quantity (there are more annual users riding bicycles on a daily basis).
With this data, it is possible to create campaigns focusing on casual customers, bringing them greater adherence to the annual plan. The next steps would be to try to find out whether casual customers use bicycles for leisure or work. And, repeat the same question for annual customers. Some other additional data would be to check the routes taken by each customer and see if the routes are close to companies or parks and then draw conclusions.

## The s file contains all the code done in the report and analysis

s.Rmd

### [Data source](https://divvy-tripdata.s3.amazonaws.com/index.html)
### [Data License Agreement](https://divvybikes.com/data-license-agreement)
