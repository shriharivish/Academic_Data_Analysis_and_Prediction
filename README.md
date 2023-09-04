# Academic_Data_Analysis_and_Prediction_using_R

**_Completed in fulfillment of the Machine Learning Course at BITS Pilani; Advisor: Dr. Navneet Goyal_**

This repository contains analysis and prediction of a student's final grade using different Machine Learning methodologies and the data contains the student's mid-semester performance along with some other academic information.

The data is in the csv file named "grade_original.csv". 
The given data is taken for 205 students.
It contains the following columns- IDNO, YEAR, ATTENDANCE %, CGPA, MidSemester, MidSemester Grades, MidSemester Collection, Quiz1, Quiz2, Part A, Part B and Grade.

PREPROCESSING OF THE DATA:
1. All the columns with very less values will be removed. For example, 'CGPA' has only 40 values.
2. Using the correlation matrix,the columns which had very low correlation values will be removed.
3. The final correlation matrix will be calculated after removing irrelevant columns.
4. A heat map will be plotted for better understanding of the correlation matrix.

The following methods were used to analyze and predict the final grades:
a. Naive Bayes
b. Decision Trees
c. Neural Networks
d. Linear SVM

To install the required packages,run the script -> install.R
If it doesn't work,then install the packages individually using -> install.packages("package_name")

_I can be contacted for the official project report or any further clarifications._


