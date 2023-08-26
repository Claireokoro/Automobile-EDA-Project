# Automobile EDA Project

Welcome to the Automobile EDA Project repository! We call the process of studying a dataset and enumerating its key properties "exploratory data analysis." This type of descriptive analytics is used. This project involves exploratory data analysis of an automobile dataset using Python. Below is an overview of the project content:

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Visualizations](#visualizations)
- [Findings](#findings)
- [Conclusion: Important Variables](#conclusion: important variables)

## Introduction
In this project, I performed exploratory data analysis (EDA) on an automobile dataset to uncover insights and patterns within the data.

## Dataset
This data set contains information about autobiles which has 29 columns and 201 rows. The dataset used in this project contains both continuous numerical variables and categorical variables. The variables include:
- Continuous Numerical Variables: Length, Width, Curb-weight, Engine-size, Horsepower, City-mpg, Highway-mpg, Wheel-base, Bore
- Categorical Variables: Drive-wheels, Engine-location, Body-style

## Notebooks
The exploratory data analysis process is documented in the Jupyter notebook `EDA_Notebook.ipynb` located in the [notebooks](notebooks/) directory.

## Visualizations
I utilized various visualization techniques to better understand the relationships within the dataset:
- Scatterplot of Engine-size and Price
  ![Scatterplot Engine-size vs Price](<img width="632" alt="Screenshot 2023-08-26 at 10 01 21 AM" src="https://github.com/Claireokoro/Exploratory_Data_Analysis/assets/122834264/4d2f3028-4155-4479-9fb6-a8f3dbb435c2">
)
- Boxplot of Body-style and Price
  ![Boxplot Body-style vs Price](<img width="631" alt="Screenshot 2023-08-26 at 10 01 40 AM" src="https://github.com/Claireokoro/Exploratory_Data_Analysis/assets/122834264/aa1b7c64-2b47-4f55-af0c-e43ea3351ef1">
)
- Heatmap of Correlations between Variables
  ![Heatmap Correlations](<img width="611" alt="Screenshot 2023-08-26 at 10 02 47 AM" src="https://github.com/Claireokoro/Exploratory_Data_Analysis/assets/122834264/e184b175-d68c-48fa-91a8-530403f6921e">
)

## Findings
From the analysis, I discovered:
- Positive correlation between Engine-size and Price
- Price differences among different Body-style categories
- Relationships between variables such as Drive-wheels and Price

For a detailed analysis and more insights, refer to the [EDA notebook](notebooks/EDA_Notebook.ipynb).

Feel free to explore the repository and notebook for a deeper understanding of the project!


Remember to replace the placeholder images with actual images of your visualizations and findings. This README structure provides an organized and informative overview of your project.
There are some data visualizations involved.


## Conclusion: Important Variables

<p>We now have a better idea of what our data looks like and which variables are important to take into account when predicting the car price. We have narrowed it down to the following variables:</p>

Continuous numerical variables:

<ul>
    <li>Length</li>
    <li>Width</li>
    <li>Curb-weight</li>
    <li>Engine-size</li>
    <li>Horsepower</li>
    <li>City-mpg</li>
    <li>Highway-mpg</li>
    <li>Wheel-base</li>
    <li>Bore</li>
</ul>

Categorical variables:

<ul>
    <li>Drive-wheels</li>
</ul>

<p>As we now move into building machine learning models to automate our analysis, feeding the model with variables that meaningfully affect our target variable will improve our model's prediction performance.</p>
