# Used Car Vehicles Analysis Project in R for DSC341

## Summary

This assignment was for DSC341 at DePaul University and taught me how to use a number of foundational R concepts, as outlined below:

#### Synopsis
<p>
The dataset that we manipulated throughout this quarter contained information on cars sold in America. After further analyzing the many variables that were present, we decided to contain the data significantly by only assessing the value of used cars sold in the state of Wisconsin. All variables that were insignificant to finding car values were removed to determine the price at which the car was sold, year, make, model, color, condition, engine type, fuel type, mileage, title status, transmission type, drivetrain, as well as the type of car sold.
</p>

#### Learning Outcomes
<p>
Utilizing R Studio, we were able to find the influential points, or the outliers that greatly affected the slope, of the dataset. We removed 2,523 rows that contained non finite values by creating scatterplots. 87 outliers were also removed due to missing values that were significant to the models that we were creating. (add details about what was removed)
We created three histograms using the dataset to better understand the degree of variation and to show the distribution pattern. The histograms created were for price, odometer, and year. 

### <b>Details of the Three Histograms: </b>

Our histogram of price and odometer are skewed to the left, while the histogram of year is skewed to the right. 

#### Histogram #1 
Our histogram for price told us that the min value of cars sold in Wisconsin was 0, the max was $109,995, and the average of all cars sold was $13,543. 

![h1](https://i.ibb.co/5K9QxsN/Screen-Shot-2021-08-19-at-3-09-25-PM.png)

<br>

#### Histogram #2
Our histogram for odometer told us the minimum value for odometer was 0 miles, the maximum was 1500000, and the mean was 112469 miles. 

![h2](https://i.ibb.co/19Nqhkp/Screen-Shot-2021-08-21-at-12-42-58-PM.png)
<br>

#### Histogram #3
The histogram for year told us that the oldest car sold in Wisconsin in this dataset was a 1954 model year and the newest car was a 2021 model year. Also informed us that most of the cars sold in Wisconsin were from the 2010 model year.
<br>

![h3](https://i.ibb.co/QYdXPkJ/Screen-Shot-2021-08-21-at-1-12-30-PM.png)

</p>

## Conclusion
In conclusion, building these models helped us predict the price of used cars sold in Wisconsin. Using variables such as year and odometer we were able to predict the price that these cars would sell for. 