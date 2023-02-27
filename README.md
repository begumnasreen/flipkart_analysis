# FlipKart anaysis


This dataset can be used for a variety of purposes, including market analysis, product development, and pricing strategy. It could also be used to train machine learning models for predicting smartphone prices or classifying smartphones based on technical specifications.

## price Prediction:

Attributes -

1. brand: The brand of the smartphone, such as Samsung, Apple, Xiaomi, etc.

2. model: The name and model number of the smartphone, such as iPhone 12, Samsung Galaxy A33, Redmi Note 10, etc.

3. colour: The colour of the smartphone, such as sandy gold, sunrise blue, etc.

4. original_price: The original price of the smartphone in Indian rupees (INR) before any discounts.

5. discounted_price: The discounted price of the smartphone in INR after any discounts or promotions.

6. ratings: The average rating of the smartphone by customers on the Flipkart website, on a scale of 1 to 5 stars.

7. rating count: The number of ratings given by customers on the Flipkart website for the smartphone.

8. reviews: The text reviews given by customers on the Flipkart website for the smartphone.

9. memory: The amount of RAM memory included in the smartphone measured in gigabytes (GB).

10. storage: The amount of internal storage included in the smartphone measured in gigabytes (GB).

11. processor: The type and speed of the processor included in the smartphone, such as Qualcomm Snapdragon 888, Apple A14 Bionic, etc.

12. rear_camera: The number and specifications of the rear cameras included in the smartphone, such as 48 MP + 12 MP + 5 MP, etc.

13. front_camera: The number and specifications of the front camera included in the smartphone, such as 20 MP, etc.

14. display_size: The diagonal size of the smartphone screen measured in centimeters (cm).

15. battery_capacity: The capacity of the smartphone battery measured in milliampere-hours (mAh).

16. battery_type: The type of battery included in the smartphone, such as lithium-ion (Li-Ion), lithium-polymer (Li-Po), etc.


## Data Preprocessing:

1.	Understand the dataset:
a.	Identify the shape of the dataset
b.	Identify variables with null values
c.	Identify variables with unique values
2.	Generate a separate dataset for numerical and categorical variables
3.	EDA of numerical variables:
a.	Missing value treatment
b.	Identify the skewness and distribution
c.	Identify significant variables using a correlation matrix 
d.	Pair plot for distribution and density
4.	EDA of categorical variables
a.	Missing value treatment
5. Which brand has the highest average ratings?
6. # df_br is having values of those only have rating more then 4.3 in the XIAOMI brand
Note: The last two points are performed to make the new dataset ready for training and prediction.
