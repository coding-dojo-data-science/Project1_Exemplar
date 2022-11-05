<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/CodingDojo_Images/main/data-science.jpg">
</p>


# Data Science Role Salaries & Insights

## Analyzing Greatest & Least Salaries and Remote Work Opportunities

Sherlin Whaley

### Often times when choosing a career path, career seekers that have a love for data science want to work from home and earn the highest salary possible while doing so. There are so many options to choose from and knowing which path will be the best path to choose can be challenging.

## Data Source: 
Data Science Job Salaries
https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries

For this dataset, there were 607 rows and 12 columns.

## Data Dictionary

<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/DS%20Salaries%20Data%20Dictionary.png">
</p>


## To prepare this data, the data was cleaned, and the following processes were performed:

### Exploratory Data Analysis
    - During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
    - Also, a barplot was visualized for each categorical column. 
    - This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
    

<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/exploratory1.png">
</p>

This histogram shows that the majority of the salaries are around $100,000.


 ### Expanatory Data Analysis
    - To visualize the data for explantory purposes, three bargraphs were chosen and one linegraph was chosen.
    - The bargraphs were chosen to show how the categories compare to each other. 
    - Finally, a linegraph was chosen to show the trend of salaries over the past three years. 


## Explanatory Visuals

<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/explanatory1.png">
</p>


The top five highest earning job titles and average salaries are as follows:

- Data Analytics Lead: `$405,000.00`
- Principal Data Engineer: `$328,333.33`
- Financial Data Analyst: `$275,000.00`
- Principal Data Scientist: `$198,099.57`
- Director of Data Science: `$195,074.00`

The bottom five least paying job titles and average salaries are as follows: 


- 3D Computer Vision Researcher: `$5,409.00`
- Product Data Analyst: `$13,036.00`
- NLP Engineer: `$37,236.00`
- Computer Vision Engineer: `$44,419.33`
- Big Data Engineer: `$50,218.12`



<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/explanatory2.png">
</p>


The top and bottom earning experience level and average salary is as follows:

- Top Earning Experience Level
  - Director Level: `$199,561.81`
- Bottom Earning Experience Level
  - Junior Level: `$62,049.60`



<p align = "center"> 
  <img src = "https://raw.githubusercontent.com/coding-dojo-data-science/Project1_Exemplar/main/explanatory3.png">
</p>


This graph shows that `Data Engineers` have the most roles that are 100% remote, while `Cloud Data Engineers` through `Data Analytics Leads` have the least amount of 100% remote roles.



<p align = "center"> 
  <img src = "https://github.com/coding-dojo-data-science/Project1_Exemplar/blob/main/explanatory4.png">
</p>


This graph shows that workers in 2022 earned the most amount of money.


 ### Maching Learning Using the Following Models:
    - Linear Regression Model
    - Decision Tree Regressor Model
    - Tuned Decision Tree Regressor Model
    - Random Forest Regressor Model
    - Tuned Random Forest Regressor Model
    
    
## Models Evaluated & Results

- Linear Regression Model (Testing Set):
  - R^2: -1.442820300359156e+22
  - MAE: 2065461996953278.5
  - MSE: 6.752807031244359e+31
  - RMSE: 8217546489825512.0

- Decision Tree Regressor Model:
  - R^2: 0.186
  - MAE: 41512.219
  - MSE: 3809835283.133
  - RMSE: 61723.863

- Tuned Decision Tree Regressor Model:
  - R^2: 0.462
  - MAE: 34610.985
  - MSE: 2517885802.26
  - RMSE: 50178.539

- Random Forest Regressor Model:
  - R^2: 0.56
  - MAE: 31872.362
  - MSE: 2061515521.69
  - RMSE: 45403.915

- Tuned Random Forest Regressor Model:
  - R^2: 0.563
  - MAE: 31998.943
  - MSE: 2044264641.827
  - RMSE: 45213.545


- The Final Model Chosen was a `Random Forest Regressor Model` with the n_estimators tuned to 50.
- For the testing set on the model, `56.3%` of the variance in y was explained by x. 
- The Mean Absolute Error was off by about `$31,998.94`.
- The Mean Squared Error was `$2,044,264,641.83`.
- The Root Mean Squared Error had a calculation of `$45,213.55`.

Using this model to make predictions about the best places to live and which careers to choose to earn the most money would not be a very reliable. Considering the previous regression metrics from how the model performed, there is a disparity between the R^2 score and also the Root Mean Squared Error that cannot be ignored.

## Recommendations

Data Science Insights

- For those who have an interst in Data Science:
  - Data Analytics Leads & Principal Data Engineers earn the most amount of money. However, this are usually not entry level careers and I would recommend going through a program, like Coding Dojo, where you can earn your data science certificate and then map out your career to these positions.

  - Data Engineers & Data Scientists have the most 100% remote positions. So, if you are wanting to work from home, or work from anywhere in the world, choosing one of the top five remote positions would be a good choice to build your career upon.
  
  - Lastly, the trend for the last three years show that data science and related fields are increasingly earning more money each year. So, choosing a career in one of these fields can be very lucrative.

Model Performance
- Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far it outperformed the linear regression model. 


## Limitations & Next Steps

From here, a student could use the insights from the visuals on how to tailor their path for their career. As mentioned before, Coding Dojo has a fantastic program that prepares inspiring data scientists for the field of data science. 

## For Further Information

For any additional questions, please contact: 
- Sherlin Whaley (Data Science Instructor)
- swhaley@codingdojo.com

