# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Screenshot 2024-11-26 224043](https://github.com/user-attachments/assets/01aa4cee-7ada-46a2-8d2a-9ce78fb1e456)
![Screenshot 2024-11-26 224109](https://github.com/user-attachments/assets/ec233134-b668-4637-8a07-e0e06ee1d8c1)
![Screenshot 2024-11-26 224126](https://github.com/user-attachments/assets/0d1c3f06-f038-41b2-84ed-a98e07eb074a)
![Screenshot 2024-11-26 224148](https://github.com/user-attachments/assets/9c255043-cdcb-4f32-9302-727863539bc5)
![Screenshot 2024-11-26 224207](https://github.com/user-attachments/assets/aabc8f4f-8441-43f4-b684-bc9b4bce23ab)
![Screenshot 2024-11-26 224223](https://github.com/user-attachments/assets/19559af2-0648-4348-a829-7959192da237)

# RESULT
Thus,Feature selection and Feature scaling has been used for given data
