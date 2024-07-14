# Breast Cancer Classification using Logistic Regression

## Overview

This Jupyter Notebook demonstrates how to perform logistic regression on the Breast Cancer Wisconsin dataset to classify tumors as benign or malignant. It covers data preprocessing, model training, evaluation, and visualization of results.

## Dataset

The dataset used in this notebook is the Breast Cancer Wisconsin dataset from Kaggle

## Features

The dataset contains 30 feature columns and a target column:
- **Features**: Various properties of the cell nuclei present in the image.
- **Target**: 
  - 1: Malignant (cancerous)
  - 0: Benign (non-cancerous)

## Prerequisites

To run this notebook, you'll need to have the following installed:
- Python (>= 3.6)
- Jupyter Notebook


## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/abdul-5844/Logistic_Regression.git
    cd Logistic_Regression
    ```
2. **Install the required dependencies:**
    ```bash
    %pip install seaborn
    ```

4. **Download the dataset:**
    Place the `breast_cancer_data.csv` file in the `data` directory.

## Usage

1. **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

2. **Open the notebook:**
    In the Jupyter interface, navigate to the `notebooks` directory and open `logistic_regression.ipynb`.

## Notebook Outline

1. **Introduction**
   - Overview of the dataset and problem statement.

2. **Data Loading and Preprocessing**
   - Import necessary libraries.
   - Load the dataset.
   - Handle missing values and encode categorical variables.
   - Split the data into training and testing sets.

3. **Exploratory Data Analysis**
   - Visualize class distributions.
   - Generate summary statistics.

4. **Model Training**
   - Train a logistic regression model on the training data.

5. **Model Evaluation**
   - Evaluate the model using accuracy, precision, recall, and F1-score.
   - Plot the confusion matrix.

7. **Conclusion**
   - Summarize findings and potential improvements.

## Results

The logistic regression model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Visualization of the class distributions and confusion matrix is also provided.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
