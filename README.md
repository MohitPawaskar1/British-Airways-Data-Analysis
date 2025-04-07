*Mohit Pawaskar*

This is GITHUB repo for British Airways Review Analysis

It is project given by @Forage of the @British Airways (BA)

Here is the step by step guide what I did


# TASK 1 

- 01. Data Collection : Collected the Data from the website called Skytrax which had around 4000 reviews about the BA.
                       Then after downloading the all the required data converted it into a CSV file called 
                       *"british_airways_reviews_extended.csv"*
                      
                      
- 02. Data Cleaning   : Imported all the essential Libraries
                        Read the Dataset
                        Checking the Null Values
                        Checking all the Columns and Datatypes
                        Renamking the Column from date to review_date
                        Converting all the Column names to lower
                        Dropping the Unnecessary Columns
                        Remove "✅ Trip Verified" and "Not Verified" from reviews
                        Function to clean ordinal suffixes like '1st', '2nd', '3rd', '4th'


- 03. ExploExploratory Data Analysis (EDA) : After Cleaning the Dataset converted all columns to numerical values in 
                                            order to find the relation.


- 04. Submitted the PPTX.









# TASK 2

- 01. Data Cleaning : Collected the Data from the website called Skytrax which had around 5000 entries about the BA.<br>
                       Then after downloading the all the required data converted it into a CSV file called <br>
                       *"customer_booking.csv"*<br>
                        Imported all the essential Libraries
                        Read the Dataset
                        Checking the Null Values
                        Checking all the Columns and Datatypes
                        Renamking the Column from date to review_date
                        Converting all the Column names to lower
                        Dropping the Unnecessary Columns


- 02. Model Training : After Cleaning the Dataset made a model using RandomForestClassifier.
                        Trained the model using train_test_split.
                        Cross-validation with ROC AUC.
                        ROC_AUC_SCORE.
                        Visualization using Matplotlib and Seaborn.


- 03. Submitted the PPTX.