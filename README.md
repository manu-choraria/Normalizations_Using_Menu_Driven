# Normalizations_Using_Menu_Driven

We have implemented Different types of normalizations techniques min-max normalization, Z-scale normalization, and decimal scaling normalization using menu- driven approach. We have used a user-input method for taking inputs from the user and perform normalization on the data value.

# What is Normalization
Data normalisation is a common machine learning technique that involves converting numeric columns to a standard scale. Some feature values differ from others multiple times in machine learning. The learning process will be dominated by features with higher values. As a result, normalising these values between scales is critical.

# Types of Normalization
There are mainly three types of normalization techniques:

1. min-max normalization: To convert data value between a specified new minimum and maximum value. The user need to specify old minumum, old maximum, new minimum and new maximum values to perform the normaalization. Let v denotes old data value and v' denotes corresponding new data value, then:
![image](https://user-images.githubusercontent.com/92246789/170271112-093d65c6-9091-4722-b1d9-ccac3328990c.png)

2. Z-score normalization: The z-score method (also known as standardisation) converts data into a distribution with a mean of zero and a standard deviation of one.
![image](https://user-images.githubusercontent.com/92246789/170271705-38f93d82-80e6-4ef5-ac13-bc34021533dc.png)

3. Decimal Scaling: It normalizes the data value between the range 0 to 1.
![image](https://user-images.githubusercontent.com/92246789/170271940-d7381acc-b024-4695-806b-ba7efa909062.png)

# Python code implentation
We have used only simple menu driven if-else looping to perform the all normalization techniques.
