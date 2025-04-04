*Mohit Pawaskar*

This is GITHUB repo for British Airways Review Analysis

It is project given by @Forage of the @British Airways (BA)

Here is the step by step guide what I did

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
                        