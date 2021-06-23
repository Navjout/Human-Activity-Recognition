# Human-Activity-Recognition
In this project we are going to design a robust activity recognition system based on the smartphones. As we know mobile devices have accelerometer as the sensor which collects the activities. These activities can be classified using K-nearest neighbor.

### REQUIREMENT
1. Pandas
2. Numpy
3. Matplotlib
4. Scikit Learn

## Machine Learning Model Used
1. k-nearest neighbors

## Database Information

The data was collected from 30 subjects aged between 19 and 48 years old performing one of 6 standard activities while wearing a waist-mounted smartphone that recorded the movement data. Video was recorded of each subject performing the activities and the movement data was labeled manually from these videos.

 
### Attribute Information:

For each record in the dataset it is provided:
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 561-feature vector with time and frequency domain variables.
- Its activity label.
- An identifier of the subject who carried out the experiment.

# Steps:

### Task 1 : Import the Dataset
First 10 top and 1 last record shown.

### Task 2 : Check for missing values
Here we checked for any missing values

### Task 3 : Exploring the Dataset
Count of records according to the activity

### Task 4 : Exploratory Data Analysis
Count of the activities we got here and listed top 2 records

Plotted Pie Graph to show the activities

### Task 5 : Data Processing

## Task 6 : Model Building for Human Acitivity Recognition
Kneighbor graph classifer

Optimal number of neighbors is: 19

Accuracy Score:90.29521547336275 %

# Conclusion:
In this project we designed a robust activity recognition system based on the smartphones. As we know mobile devices have accelerometer as the sensor which collects the activities. These activities can be classified using K-nearest neighbor. All the predictions we got, plotted confusion matrix with true values and predicted values. We printed classification report also with true and predicted values. We got the precision, recall, f1score and support and we can see Laying has higher precision and standing is less.
