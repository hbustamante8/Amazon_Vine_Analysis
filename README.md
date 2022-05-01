# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this project is to analyze the Amazon Vine program and determine if there is bias towards favorable reviews between vine/non-vine members. PySpark was used to perform the ETL process and then used to connect to an Amazon Web Services RDS instance. From PySpark, the data from the instance was loaded and transformed into pgAdmin tables. Lastly, Jupyter notebook was used to calculate different metrics on the vine reviews. This specific dataset was US reviews for Toys.


## Results

* Total Vine reviews and non-Vine reviews
![image](https://user-images.githubusercontent.com/96553992/166168193-daf8ff19-4185-4048-85c4-fe8c0f9a0133.png)

* Vine Reviews 
![image](https://user-images.githubusercontent.com/96553992/166168099-890a516e-63e8-4dda-ab4f-43210f7d4fd7.png)

*  Non-Vine Reviews
![image](https://user-images.githubusercontent.com/96553992/166168118-bcd40db2-6d4b-4ffd-b57b-16fdea630fd4.png)

Percentage of Vine Reviews that were 5 stars
![image](https://user-images.githubusercontent.com/96553992/166168317-fd66a05e-c5fe-49ee-b508-75d71f97c4aa.png)

Percentage of non-Vine reviews that were 5 stars
![image](https://user-images.githubusercontent.com/96553992/166168331-e3c164fa-a7f5-4ce1-a308-b3307e3fa099.png)


## Summary

The metrics revealed that 2.6% of the reviews in the Vine program are 5-star reviews while the non-Vine reviews are 97.4% of the total. Based on the results, there is no positivity bias for reviews in the Vine program. The Vine program which requires reviews is not inclining customers to give good reviews once they receive their orders. Also, this dataset happens to have almost all people doing toy reviews that are not a part of the Vine program, so it is not the ideal dataset to explore if there is positivity bias. An additional analysis that could be conducted at the opposite spectrum and repeat the analysis for 1-star reviews. The results would help to confirm if any bias can be inferred from the Toys dataset.
