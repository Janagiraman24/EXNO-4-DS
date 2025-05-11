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
![Screenshot 2025-05-11 165633](https://github.com/user-attachments/assets/6df4ae96-4da2-4f4f-bc2a-5dc84e9f85dd)
![Screenshot 2025-05-11 165651](https://github.com/user-attachments/assets/ccd29981-f865-4a30-a490-c20859db2c2c)
![Screenshot 2025-05-11 165708](https://github.com/user-attachments/assets/f06b88dc-4db7-4a63-84a1-a08ca4613d38)
![Screenshot 2025-05-11 165726](https://github.com/user-attachments/assets/0663b84e-c70f-4d12-97e7-03253619dae5)
![Screenshot 2025-05-11 165751](https://github.com/user-attachments/assets/391acf5f-e96a-498a-9a43-3c4b02dc3d38)
![Screenshot 2025-05-11 165802](https://github.com/user-attachments/assets/0439db06-b576-4068-97c2-ab529e7292a4)
![Screenshot 2025-05-11 165811](https://github.com/user-attachments/assets/a53bcf9e-ad80-44a6-93c6-cd15e7f446e3)
![Screenshot 2025-05-11 165821](https://github.com/user-attachments/assets/726650b6-f215-474e-9e82-20fec09e3ba3)
![Screenshot 2025-05-11 165832](https://github.com/user-attachments/assets/4bd30aa3-d3f8-4e26-9bc6-a2ac4a13e21f)
![Screenshot 2025-05-11 165841](https://github.com/user-attachments/assets/5fc511c4-1290-4402-8a7c-f1b9764670f4)

# RESULT:
Feature scaling and feature selection process has been successfullyperformed on the data set.
