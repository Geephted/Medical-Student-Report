# Medical Student Data Analysis with Excel

## Overview
This repository contains a comprehensive dataset of medical students enrolled in a University during a specific academic year. The data was collected with the objective of studying various characteristics and trends among medical students. It encompasses a rich combination of numerical and categorical variables, providing valuable insights into the diverse student population.

## Data Set
The dataset consists of a single data file in a comma-separated values (CSV) format. Each row represents a unique medical student, and the columns contain different attributes of the students.

### Attributes
 
The data set include the following attributes:
-	Student ID: A unique identifier for each student.
-	Age: The age of the student in years.
-	Gender: The gender of the student (Male or Female).
-	Blood Group: The ABO blood group of the student (A, B, AB, O).
-	Smoker: Indicates whether the student smokes or not (Yes/No).
-	Diabetic: Indicates whether the student has diabetes (Yes/No).
-	Health Conditions: Any other relevant health conditions or medical history of the student.

Below is a screen short of the Data set used
![](uncleanData.jpg)

### Data Preprocessing/Cleaning 
The dataset has undergone some basic preprocessing, including:
- Handling missing values by imputing or removing them based on the context.
- Removing duplicates and converting data types 
- Encoding categorical variables to numerical representations for analysis purposes.

Below is the screen short of the Dataset after it has been properly cleaned 
![](CleanedData.jpg)

## Objective 
The purpose is to study and analyze the relationship between different attributes and identify any patterns or trends related to health conditions among medical students based on the data set.

## Analysis of the Data 
I gained insights from the data set by performing the following analyses:

- Health Conditions Analysis: Identifying the most common health conditions among medical students. Understanding the distribution of students based on Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol for both male and female students.

This task involved utilizing a pivot table to calculate the average values of Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol for both males and females. To achieve this, the Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol columns were all placed in the "Values" section of the pivot table, while the "Gender" column was placed in the "Rows" section of the pivot table field. By doing so, the pivot table automatically aggregated the data, providing the average values for each of the mentioned variables separately for males and females.

Below is the the resulting pivot table:
![](Averageage.jpg)

- Height and Weight Analysis:  Identifying Average Height and Weight for both Genders of the medical students (in 2 decimal places)

This task involved using a pivot table to calculate the average values for height and weight separately for male and female individuals. To accomplish this, the "height" and "weight" columns were placed in the "Values" section of the pivot table, and the "gender" column was placed in the "Rows" section of the pivot table field. By doing so, the pivot table automatically aggregated the data, providing the average height and weight values for both male and female individuals in the dataset. This analysis helps understand the average height and weight characteristics among males and females separately, which can be valuable for various research and health-related studies.	

Below is the the resulting pivot table:
![](AvgHeight.jpg)

- Blood Group Analysis: Examining the distribution of blood groups among medical students.

This task involved using a pivot table to find the number of students across different blood groups. The "Student ID" column was placed in the "Values" section of the pivot table, while the "Blood Group" column was placed in the "Rows" section of the pivot table field. By doing so, the pivot table automatically aggregated the data, providing the count of students for each blood group separately. This analysis allows us to understand the distribution of students among different blood groups, providing insights into the prevalence of each blood group among the student population.

Below is the the resulting pivot table:
![](Bloodgroups.jpg) 

- Smoking Analysis: Identifying smoking habits among medical students. 

This task involved using a pivot table to find the number of students who smoke and those who don't. The "Student ID" column was placed in the "Values" section of the pivot table, and the "Smoking" column (which likely contains categorical values like "Yes" and "No" to indicate smoking status) was placed in the "Rows" section of the pivot table field. By doing so, the pivot table automatically aggregated the data, providing the count of students for each smoking status separately.

Below is the the resulting pivot table:

![](Smokers.jpg) 

This analysis allows us to understand the number of students who smoke and those who do not, providing insights into the prevalence of smoking among the student population.

- Diabetes Analysis: Investigating the prevalence of diabetes among medical students.

This task involved using a pivot table to find the number of students who have diabetes and those who don't. The "Student ID" column was placed in the "Values" section of the pivot table, and the "Diabetes" column (which likely contains categorical values like "Yes" and "No" to indicate diabetes status) was placed in the "Rows" section of the pivot table field. By doing so, the pivot table automatically aggregated the data, providing the count of students for each diabetes status separately.

Below is the the resulting pivot table:

![](Diabetes.jpg)
This analysis allows us to understand the number of students who have diabetes and those who do not, providing insights into the prevalence of diabetes among the student population.

## Visualization of the insights gotten from the Pivot Tables created 
After carefully analyzing the data from the pivot tables, I created several pivot charts to visualize the information obtained. Below are the pivot charts used for each of the pivot tables:

#### Average Height and Weight for Both Genders: Clustered Column Chart
This chart provides a visual comparison of the average height and weight for both genders. The x-axis represents the genders (Male and Female), and the y-axis represents the average height and weight values. The chart displays clustered columns for each gender, making it easy to compare the average height and weight side by side.

![](avgheightch.jpg)

#### Number of Students across Different Blood Groups: Clustered Column Chart
This chart presents the distribution of students across different blood groups. The x-axis represents the blood groups (e.g., A, B, AB, O), and the y-axis represents the number of students. The chart displays clustered columns for each blood group, allowing for a quick comparison of the number of students in each group.

![](Bloodgroupsch.jpg) 

#### Number of Students Who Smoke and Those Who Don't: Doughnut Chart
This chart visualizes the proportion of students who smoke and those who don't. The doughnut chart represents a circle with segments that show the percentage of students who smoke (Yes) and those who don't (No) out of the total student population.

![](Smokersch.jpg) 

#### Number of Students Who Have Diabetes and Those Who Don't: Clustered Bar Chart
This chart displays the number of students who have diabetes and those who don't. The x-axis represents the diabetes status (Yes or No), and the y-axis represents the number of students. The chart uses clustered bars to compare the count of students with diabetes and without diabetes.
Using pivot charts helps to present the insights from the pivot tables in a visually appealing and easy-to-understand manner. The visualizations enable quick comparisons, identify patterns, and communicate the findings effectively to stakeholders and decision-makers.

![](Diabetesch.jpg)

## Medical Student Data Analysis Dashboard
This dashboard is designed to visually represent the key insights and analysis from the medical student dataset. It provides a concise and interactive way to present the most important findings in an easy-to-understand format. The top middle section of the dashboard displays essential summary metrics, including the total number of students, the average age, average height and average weight

![](Dashboard.jpg)

## Tool Used

This analysis and dashboard was done using Microsoft Excel, a powerful spreadsheet tool widely used for data analysis and visualization. Excel offers a range of features and functionalities that enable me to manipulate, analyze, and present data effectively. Some of the Excel tools and functions i used in analysing this data include:

- PivotTables
- Charts and Graphs 
- Data Filtering and Sorting
- Formulas and Functions
- Data Visualization Techniques

## Conclusion 
This repository serves as a valuable asset to advance knowledge in the field of medical education, contributing to a better understanding of medical student characteristics and health-related aspects. By leveraging this analysis, stakeholders can work collaboratively to drive positive changes, support student success, and ultimately improve the quality of medical education and student experiences.
