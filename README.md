# Income-Classification-Data-Mining
## Project Overview

This project analyzes the UCI Census Income dataset to predict whether an individual earns more than $50,000 annually based on demographic and socioeconomic attributes such as education level, occupation, age, and marital status. The goal of the analysis was to evaluate how different machine learning classification algorithms perform when predicting income levels and to understand how data preprocessing techniques influence model performance. The notebook included in this repository focuses on the implementation and evaluation of several classification models using Python.

## Key Results
The Decision Tree model achieved 81.62% accuracy, while the manually implemented Logistic Regression model achieved 80.58% accuracy. The K-Nearest Neighbors classifier achieved 77.36% accuracy, showing strong recall but weaker precision for the minority income class. A weighted ensemble model combining the Decision Tree, Logistic Regression, and KNN classifiers achieved the best overall performance with 82.3% accuracy, improving the precision–recall balance and reducing false negatives compared to individual models.

## My Contribution

Within the team project, my primary focus was implementing and evaluating the K-Nearest Neighbors (KNN) and Logistic Regression models. I implemented the KNN classifier and evaluated its performance across different values of k to better understand how neighborhood size influences classification accuracy. In addition, I developed a manual implementation of Logistic Regression using gradient descent in order to better understand how the model’s parameters are optimized during training.

My work also included computing model evaluation metrics such as accuracy, precision, recall, and F1-score, as well as comparing the performance of different classification approaches. These results were later incorporated into the ensemble model that combines predictions from multiple classifiers.

## Dataset

The dataset used in this project is from the UC Irvine Machine Learning Repository. It which contains more than 32,000 observations describing demographic and socioeconomic characteristics of individuals in the United States. The dataset includes attributes such as age, education, occupation, marital status, work class, hours worked per week, and native country. The target variable is a binary classification that indicates whether an individual earns less than or equal to $50K or more than $50K annually.

## Data Preprocessing

Several preprocessing techniques were applied to prepare the dataset for modeling. Missing values were addressed using KNN-based imputation, and class imbalance was handled using oversampling techniques. Categorical variables were converted into numerical format using one-hot encoding, while continuous variables were normalized using z-score normalization. These steps ensured that the dataset was appropriately formatted and scaled for machine learning algorithms.

## Models Implemented

Multiple classification algorithms were implemented and evaluated as part of the project. These included a Decision Tree model used as an initial baseline, a manually implemented Logistic Regression model, and a K-Nearest Neighbors classifier. The project also explored a weighted ensemble approach that combines predictions from multiple classifiers to improve overall predictive performance.

## Technologies Used

The project was implemented in Python using libraries commonly used in data science and machine learning workflows. These included pandas and NumPy for data manipulation, scikit-learn for machine learning models and evaluation metrics, and matplotlib for data visualization. The analysis was conducted in a Jupyter Notebook environment and version controlled using Git and GitHub.

## Running the Project

To run the project locally, first clone the repository from GitHub and navigate into the project directory. After cloning the repository, install the required Python libraries using pip. The necessary dependencies include pandas, NumPy, scikit-learn, and matplotlib.

Once the dependencies are installed, launch Jupyter Notebook and open the notebook file contained in the repository. Running the notebook from top to bottom will execute the full analysis pipeline, including data preprocessing, model training, and model evaluation.

## Repository Structure

The repository contains the main Jupyter Notebook used for the analysis, the processed training dataset used in the modeling pipeline,the official report, and this README file describing the project.
