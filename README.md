Below is the description, checklist, responsibilities and guidelines for the Capstone Project. Please use this as the base of your Project Reports. Project reports has to be submitted before the finishing of the course or within 15 days of assigning:
Machine Learning Project Description :
1.	Name of the Datasets : Household Power Consumption.
2.	Dataset is a minute wise data logging of Power Consumption of a Household Consumption
3.	Data Record Duration : December 2006 to November 2010 (4 Years).
4.	Record Frequency : Per minute
5.	Features recorded (07 No.) :
a.	Global Active Power
b.	Global Reactive Power
c.	Voltage
d.	Global Intensity
e.	Sub metering 1
f.	Sub metering 2
g.	Sub metering 3
6.	Observations : 2075259 (around 2 million)
 
Objective of the project:
1.	Develop a Machine Learning model to predict the Global Intensity
2.	Develop a Machine Learning model to predict if the Global Intensity is greater than 15.
 
Project Activities and responsibilities :
1.	Data loading
    a.	Converting the original dataset from the raw txt file to csv format.
    b.	Slice out the bottom/latest 200,000 observations for Project tests, and carry on the experiments with other available data observations.
    c.	Crosscheck the discrepancies and abnormalities in the dataset, and amend for further usage.
    d.	Load the data from csv file into Pandas dataframe for further usage.

2.	Data Analysis
    a.	In the prepared dataframe, checking the patterns of the different features using various reports and graphs
    b.	Checking the correlations among features
    c.	Checking the feature importance
    d.	Checking the missing values
    e.	Checking the outliers
    f.	Statistical Analysis

3.	Data Cleaning
    a.	Dropping off the unnecessary or irrelevant features
    b.	Treatment of the values creating the imbalance of the data
    c.	Finding and treating the outliers wherever required
    d.	Finding and treating the missing values appropriately wherever required.

4.	Data Transformation
    a.	Checking and Converting the features into needful formats.
    b.	Merging the relevant features as per requirements

5.	Pre-processing
    a.	Prepare the data for modelling by using Train-Test split method
    b.	Pre-processed data must contain X_train, X_test, Y_train, Y_test dataframes

6.	Modelling
    a.	Apply the relevant algorithms on the provided pre-processed data
    b.	Evaluate the accuracy of the model by using test data
    c.	Re-modelling to be done until the optimized results are achieved.
    d.	Re-modelling to be done using Algorithms changes and Hyper-parameter finetuning methods.

7.	Results
    a.	Results of the machine learning to be drafted in the forms of Accuracy, Confusion Matrix, Classification reports wherever applied.

