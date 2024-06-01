# Home_Sales

## Project Description
In this project, SparkSQL was used to evaluate key metrics about home sales data. Spark was used to create temporary views, partition the data, cache, and uncache a temporary table, and verify that the table has been uncached. 

## Data
- [Home Sales dataset](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv)

## Analysis
**Question 1:** What is the average price for a four-bedroom house sold for each year? 

![(https://github.com/jttran97/Home_Sales/blob/f2fa090de3c018ab154a1514a6d0b3f2bc46be29/Images/avg_4bed.png)](https://github.com/jttran97/Home_Sales/blob/29d27036ec62036ea7c7da4267758aac7a580517/Images/avg_4bed.png)

**Question 2:** What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 

![(https://github.com/jttran97/Home_Sales/blob/f2fa090de3c018ab154a1514a6d0b3f2bc46be29/Images/avg_3bed_3bath.png)](https://github.com/jttran97/Home_Sales/blob/29d27036ec62036ea7c7da4267758aac7a580517/Images/avg_3bed_3bath.png)

**Question 3:** What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

![(https://github.com/jttran97/Home_Sales/blob/f2fa090de3c018ab154a1514a6d0b3f2bc46be29/Images/avg_3bed_2floors.png)](https://github.com/jttran97/Home_Sales/blob/29d27036ec62036ea7c7da4267758aac7a580517/Images/avg_3bed_2floors.png)

**Question 4:** What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?

![(https://github.com/jttran97/Home_Sales/blob/f2fa090de3c018ab154a1514a6d0b3f2bc46be29/Images/view_ratings.png)](https://github.com/jttran97/Home_Sales/blob/29d27036ec62036ea7c7da4267758aac7a580517/Images/avg_4bed.png)

**Run Times on Question 4**
- Uncached: 0.7150566577911377 seconds
- Cached: 0.33871889114379883 seconds
- Parquet DataFrame: 0.4382476806640625 seconds
