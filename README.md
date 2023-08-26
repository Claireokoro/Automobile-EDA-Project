# Exploratory Data Analysis
We call the process of studying a dataset and enumerating its key properties "exploratory data analysis." This type of descriptive analytics is used. 


Creating a repository for your project is a great idea! Here's a suggested structure for your repository along with a placeholder for the README.md file:

**Repository Name:** Automobile-EDA-Project

**Structure:**
```
Automobile-EDA-Project/
│
├── data/                          # Directory to store the dataset
│   └── automobile_data.csv        # Placeholder for the dataset
│
├── notebooks/                     # Directory for Jupyter notebooks
│   ├── EDA_Notebook.ipynb         # Your EDA Jupyter notebook
│   └── ...
│
├── images/                        # Directory to store images for documentation
│   ├── scatterplot_engine_size_price.png     # Placeholder for the scatterplot image
│   ├── boxplot_body_style_price.png         # Placeholder for the boxplot image
│   ├── heatmap_body_style_price.png         # Placeholder for the heatmap image
│   └── ...
│
└── README.md                      # Project README
```

**README.md Placeholder:**


# Automobile EDA Project

Welcome to the Automobile EDA Project repository! This project involves exploratory data analysis of an automobile dataset using Python. Below is an overview of the project content:

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Notebooks](#notebooks)
- [Visualizations](#visualizations)
- [Findings](#findings)

## Introduction
In this project, I performed exploratory data analysis (EDA) on an automobile dataset to uncover insights and patterns within the data.

## Dataset
The dataset used in this project contains both continuous numerical variables and categorical variables. The variables include:
- Continuous Numerical Variables: Length, Width, Curb-weight, Engine-size, Horsepower, City-mpg, Highway-mpg, Wheel-base, Bore
- Categorical Variables: Drive-wheels, Engine-location, Body-style

## Notebooks
The exploratory data analysis process is documented in the Jupyter notebook `EDA_Notebook.ipynb` located in the [notebooks](notebooks/) directory.

## Visualizations
I utilized various visualization techniques to better understand the relationships within the dataset:
- Scatterplot of Engine-size and Price
  ![Scatterplot Engine-size vs Price](images/scatterplot_engine_size_price.png)
- Boxplot of Body-style and Price
  ![Boxplot Body-style vs Price](images/boxplot_body_style_price.png)
- Heatmap of Correlations between Variables
  ![Heatmap Correlations](images/heatmap_body_style_price.png)

## Findings
From the analysis, I discovered:
- Positive correlation between Engine-size and Price
- Price differences among different Body-style categories
- Relationships between variables such as Drive-wheels and Price

For a detailed analysis and more insights, refer to the [EDA notebook](notebooks/EDA_Notebook.ipynb).

Feel free to explore the repository and notebook for a deeper understanding of the project!


Remember to replace the placeholder images with actual images of your visualizations and findings. This README structure provides an organized and informative overview of your project.
There are some data visualizations involved.

# About the Dataset

This data set contains information about autobiles which has 29 columns and 201 rows.

# Conclusion: Important Variables

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
