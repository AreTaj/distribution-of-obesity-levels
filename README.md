# Distribution Of Obesity Levels: A Statistical Overview

This project is a part of the AAI 500 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 

-- Project Status: [Completed]

## Installation
Download the code in the project Github repository, and ensure Python is installed on the device. Run the code present in the .ipynb files.
  
## Project Intro/Objective
The main purpose of this project is to contribute to a deeper understanding of the complex factors that contribute to obesity in Latin America. The analysis focuses on using statistical methods, particularly random forest regression, to identify key determinants of obesity, such as body mass index (BMI), body weight, and diet. We hypothesize that specific combinations of lifestyle factors, such as high consumption of processed foods, limited physical activity, and family history of obesity, are significantly correlated with obesity rates. By identifying these patterns, targeted public health interventions can be developed to address individuals at higher risk and promote healthier behaviors.

Through statistical analysis and machine learning techniques, we hypothesize that specific combinations of these variables are significantly correlated with obesity rates. For instance, we anticipate that individuals who consume a high proportion of processed foods, engage in limited physical activity, and have a family history of obesity are more likely to be overweight or obese. By identifying these patterns, targeted public health interventions can be developed to address the specific needs of individuals at risk and promote healthier lifestyles. Ultimately, this research aims to contribute to a deeper understanding of the complex factors that contribute to obesity in Latin America. The findings will inform public health strategies and interventions to combat this growing health crisis and support efforts to improve overall population health.

## Partner(s)/Contributor(s)  
•	Payal Patel, Ahmed Salem, Aresh Tajvar

## Methods Used
•	Inferential Statistics

•	Machine Learning

•	Data Visualization

•	Data Manipulation

•	Random Forest Modeling

•	Correlation Analysis

•	Multivariate Analysis

•	PCA Analysis

•	Confusion Matrices

•	ROC

•	Data Balancing

•	Winsorization

•	Outlier Detection

## Technologies
•	Python

•	Jupyter Notebook

## Project Description
The source dataset, “Estimation of Obesity Levels Based On Eating Habits and Physical Condition”, was created by Fabio Mendoza Palechor and Alexis de la Hoz Manotas in 2019 and obtained from the UCI Irvine Machine Learning Repository (https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition). It has 16 features, 2111 instances, and a class variable NObesity (Obesity Level) that allows classification of the data using the values of Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III. 

Data cleaning & preparation and exploratory data analysis were performed in Python to facilitate model selection and model analysis. A random forest model was constructed and provided accurate predictions and highlighted relationships between predictors and obesity levels.

The Random Forest model performed extremely well in predicting obesity levels, achieving overall accuracy of 98.28%. The model’s reliability is evident in the Confusion Matrix, which indicated high classification accuracy across different obesity groups. Additionally, the ROC curve analysis highlighted the model’s ability to distinguish between classes. 

Despite the Random Forest model’s strong performance, two key limitations were identified. First, the model struggled to distinguish between Overweight Level I and Overweight Level II classes, which led to minor misclassification. Second, the model relies on available features, which may overlook other important factors that influence obesity, such as genetics, and socioeconomic status. Addressing these limitations could improve the model’s accuracy in future studies.

## License
MIT License

## Acknowledgments
Thanks to professors Dallin Munger and Leon Shpaner of our AAI 500 class.
