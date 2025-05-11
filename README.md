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
![Screenshot 2025-05-11 165633](https://github.com/user-attachments/assets/bf28e10a-1cf6-4988-a6f2-d0c88e82a8e9)
![Screenshot 2025-05-11 165651](https://github.com/user-attachments/assets/12dba12f-f6ba-4d58-b81e-435be653dee1)
![Screenshot 2025-05-11 165708](https://github.com/user-attachments/assets/eee54cc3-6176-4a6a-a45c-a993261efce7)
![Screenshot 2025-05-11 165726](https://github.com/user-attachments/assets/f1a9cd5d-5386-41cf-96b4-9bf67dd3b563)
![Screenshot 2025-05-11 165751](https://github.com/user-attachments/assets/d4f81b78-d064-4369-9c99-9cde9d178ca3)
![Screenshot 2025-05-11 165802](https://github.com/user-attachments/assets/fc00c569-cf71-4f79-8dad-9ecfcb67d26a)
![Screenshot 2025-05-11 165811](https://github.com/user-attachments/assets/7335cc6d-d7c3-4416-88c3-f2cb3671e80f)
![Screenshot 2025-05-11 165821](https://github.com/user-attachments/assets/684fe286-4669-4935-ac1a-dfbda01231b4)
![Screenshot 2025-05-11 165832](https://github.com/user-attachments/assets/05bfef45-784d-4d63-be71-302350dd5b46)
![Screenshot 2025-05-11 165841](https://github.com/user-attachments/assets/016e0e00-1ac0-45ae-8cfc-01a8ba5eebe6)

# RESULT:
Feature scaling and feature selection process has been successfullyperformed on the data set.
