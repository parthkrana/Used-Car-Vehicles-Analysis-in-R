# Used Car Vehicles Analysis Project in R for DSC341 -- 

#### Summary

<p>
The dataset that we manipulated throughout this quarter contained information on cars sold in America. After further analyzing the many variables that were present, we decided to contain the data significantly by only assessing the value of used cars sold in the state of Wisconsin. All variables that were insignificant to finding car values were removed to determine the price at which the car was sold, year, make, model, color, condition, engine type, fuel type, mileage, title status, transmission type, drivetrain, as well as the type of car sold.
</p>

<p>
Utilizing R Studio, we were able to find the influential points, or the outliers that greatly affected the slope, of the dataset. We removed 2,523 rows that contained non finite values by creating scatterplots. 87 outliers were also removed due to missing values that were significant to the models that we were creating. (add details about what was removed)
We created three histograms using the dataset to better understand the degree of variation and to show the distribution pattern. The histograms created were for price, odometer, and year. The histograms of price and odometer are skewed to the left, while the histogram of year is skewed to the right. Our histogram for price told us that the min value of cars sold in Wisconsin was 0, the max was $109,995, and the average of all cars sold was $13,543. The histogram for odometer told us the minimum value for odometer was 0 miles, the maximum was 1500000, and the mean was 112469 miles. The histogram for year told us that the oldest car sold in Wisconsin in this dataset was a 1954 model year and the newest car was a 2021 model year. The year histogram also told us that most of the cars sold in Wisconsin were from the 2010 model year.
</p>

This assignment was for IT320 at DePaul University and taught me how to use a number of foundational R concepts, as outlined below:

1. Learned how to apply SQL clauses to perform the following:
* Grouping operations
* Calculations
* Aggregate functions
* Sorting techniques

2. Utilized the relational algebra concepts intrinsic in SQL for processing multiple tables using joins and or sub-queries.

3. Analyzed the requests to identify the tables, attributes, selection, and join criteria.

In completing the assignment, I used SQL queries, operations, and calculations to understand data on hotel guests, which included names, phone numbers, addresses, room reservations, and more.

In conclusion, building these models helped us predict the price of used cars sold in Wisconsin. Using variables such as year and odometer we were able to predict the price that these cars would sell for. 