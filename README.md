# Academic Data Analysis and Prediction using R

**_Completed in fullfillment of the Machine Learning Course at BITS Pilani; Advisor: Dr. Navneet Goyal_**

This repository contains analysis and prediction of a student's final grade using different Machine Learning methodologies and the data contains the student's mid-semester performance along with some other academic information.

The data is in the csv file named "grade_original.csv". 
The given data is taken for 205 students.
It contains the following columns- IDNO, YEAR, ATTENDANCE %, CGPA, MidSemester, MidSemester Grades, MidSemester Collection, Quiz1, Quiz2, Part A, Part B and Grade.

### Preprocessing of the Data:
1. All the columns with very less values will be removed. For example, 'CGPA' has only 40 values.
2. Using the correlation matrix,the columns which had very low correlation values will be removed.
3. The final correlation matrix will be calculated after removing irrelevant columns.
4. A heat map will be plotted for better understanding of the correlation matrix.



### Installation:
    - Install the "requiRements" package:
        - install.packages("requiRements")
    - Install all the other dependencies:
        - Run install.R


### Methods:
The following methods were used to analyze and predict the final grades:  
1. **Naive Bayes**  
    - Run `naive_bayes.R`
2. **Decision Trees**  
    - Run `decision_tree.R`
    - PCA processed Run `decision_tree_pca.R`
3. **Neural Networks**
    - Run `neuralnet.R`
4. **Linear SVM**  
    - Run `svm.R`


### Comparison
Compare all methods by running `barplot.R`.

_I can be contacted for the official project report or any further clarifications._


