# Human-Activity-Recognition

### Problem Statement
Every people have smartphone. These smartphone contains many sensors. Two of the most important sensors are **accelerometer** and **gyroscope**.
**Accelerometer** measure the acceleration and **gyroscope** measure the angular velocity. Suppose we have collected the data from these sensors to predict the activity by human like running, walking etc.

" The main problem statement is to predict the human activities like, walking, running, sitting, walking upstairs, walking downstairs, laying."

### Data Understanding
The data is collected from 30 people in a lab manually by putting these sensors on their body while performing these activities. The data recorded with sensors in smartphone. These experiment was video recorded and to label data manually.
By using sensors, they have catured the 3-axial angular velocity from gyroscope and 3 axial linear acceleration using accelerometer with several variation. The data also contain the time series.

People who created these data, in addition to giving time series, data they have also designed some features like:
* tBodyAcc-XYZ
* tGravityAcc-XYZ
* tBodyAccJerk-XYZ
* tBodyGyro-XYZ
* tBodyGyroJerk-XYZ
* tBodyAccMag
* tGravityAccMag
* tBodyAccJerkMag
* tBodyGyroMag
* tBodyGyroJerkMag
* fBodyAcc-XYZ
* fBodyAccJerk-XYZ
* fBodyGyro-XYZ
* fBodyAccMag
* fBodyAccJerkMag
* fBodyGyroMag
* fBodyGyroJerkMag

For all these features they have calculated different values like mean, standard deviation, max, min, energy etc.

#### Model Building Approach
* For the expert engineered features we will build classical ML model.
* For raw time series data we will use deep learning model like LSTM.

## Approach
* Data Exploration: Exploring the dataset using pandas, numpy etc.
* Data Cleaning: Cleaning the dataset using pandas and numpy, handling null values.
* EDA: Performing exploratory data analysis, Univariate analysis, applying t-SNE to check separability of data points.
* Model building: For the expert engineered features we will build classical ML model and for raw time series data we will use deep learning model like LSTM.

### Visulization
![Screenshot (331)](https://user-images.githubusercontent.com/54364376/165042777-bd567936-54c5-4167-ab92-880df056b400.png)
![Screenshot (332)](https://user-images.githubusercontent.com/54364376/165042807-4ea14909-b29d-4e19-ad01-6a2ec728c52d.png)
![Screenshot (333)](https://user-images.githubusercontent.com/54364376/165042825-a94505df-142a-4721-bebb-b1bbee1a5a33.png)
![Screenshot (334)](https://user-images.githubusercontent.com/54364376/165042856-e268e711-be56-4f13-a580-3532ce8f8c76.png)


