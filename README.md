# Product-Recommendation-System

## Objective
The goal of this project is to develop a machine learning model that can recommend products to users.

## Dataset
The dataset used in this project contains user-product interactions with ratings, product categories, and purchase dates. The data was preprocessed and split into training and test sets.

## Steps Taken
1. **Exploratory Data Analysis (EDA)**: Explored the dataset to understand user behavior, trends, and product popularity.
2. **Model Building**: Built a collaborative filtering model using the Surprise library, which was trained on the user-product interaction data.
3. **Model Evaluation**: Evaluated the model performance using RMSE (Root Mean Squared Error) on the test data.

## Environment and Setup
- **GPU Used**: Google Colab with a T4 GPU for model training and evaluation.
- **Libraries**: The project requires the following Python libraries:
  - `pandas`
  - `seaborn`
  - `surprise`
  - `matplotlib`
