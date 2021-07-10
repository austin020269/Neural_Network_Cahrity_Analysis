# Neural_Network_Charity_Analysis

UT Bootcamp Module 19 Challenge

## Project Overview
Use neural networks and to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Data provided from Alphabet Soup is a collection of 34,000 organizations that have been previously funded over the past few years.

## Resources
Data Sources provided to analyze and minipulate included:

-Alphabet Soup Charity dataset (charity_data.csv)
Software utilized for this study included:

-Python 3.7.6
-Pandas
-Personal GitHub account

## Analysis and Workflow

### Deliverable 1: Preprocessing the Data for a Neural Network
Spcifically for this deliverable we did the following:

1. Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
- What variable(s) are considered the target(s) for your model?
- What variable(s) are considered the feature(s) for your model?
2. Drop the EIN and NAME columns.
3. Determine the number of unique values for each column.
4. For those columns that have more than 10 unique values, determine the number of data points for each unique value.
5. Create a density plot to determine the distribution of the column values.
6. Use the density plot to create a cutoff point to bin "rare" categorical variables together in a new column, Other, and then check if the binning was successful.
7. Generate a list of categorical variables.
8. Encode categorical variables using one-hot encoding, and place the variables in a new DataFrame.
9. Merge the one-hot encoding DataFrame with the original DataFrame, and drop the originals (see below).
alt text

10. Split the preprocessed data into features and target arrays.
11. Split the preprocessed data into training and testing datasets.
12. Standardize numerical variables using Scikit-Learn’s StandardScaler class, then scale the data.
Code:

alt text

### Deliverable 2: Compile, Train, and Evaluate the Model
Specifically for this deliverable we did the following:

1. Continue using the AlphabetSoupCharity.ipynb file where you’ve already performed the preprocessing steps from Deliverable 1.
2. Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.
3. Create the first hidden layer and choose an appropriate activation function.
4. If necessary, add a second hidden layer with an appropriate activation function.
5. Create an output layer with an appropriate activation function.
6. Check the structure of the model.
7. Compile and train the model.
8. Create a callback that saves the model's weights every 5 epochs.
9. Evaluate the model using the test data to determine the loss and accuracy.
10. Save and export your results to an HDF5 file, and name it AlphabetSoupCharity.h5.
alt text

### Deliverable 3: Optimize the Model
Specifically for this deliverable we did the following:

Create a new Jupyter Notebook file and name it AlphabetSoupCharity_Optimzation.ipynb.
Import your dependencies, and read in the charity_data.csv to a Pandas DataFrame.
Preprocess the dataset like you did in Deliverable 1, taking into account any modifications to optimize the model.
Design a neural network model, taking into account any modifications that will optimize the model to achieve higher than 75% accuracy.
Create a callback that saves the model's weights every 5 epochs.
Save and export your results to an HDF5 file, and name it AlphabetSoupCharity_Optimization.h5.
alt text

### Deliverable 4: A Written Report on the Neural Network Model
Results
Summary
