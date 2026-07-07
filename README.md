# Genomes-And-Genetics
# Genetic Disorder Prediction using Machine Learning

## Overview

This project focuses on predicting **Genetic Disorders** using machine learning techniques based on patient demographic, clinical, and genetic information. It demonstrates the complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

The objective is to analyze the dataset, identify meaningful patterns, and develop a classification model capable of predicting the type of genetic disorder from the available patient data.

---

## Project Objectives

- Clean and preprocess the dataset.
- Handle missing and inconsistent values.
- Perform exploratory data analysis to understand the dataset.
- Visualize important trends and relationships among features.
- Train a machine learning model for genetic disorder prediction.
- Evaluate the model using appropriate performance metrics.

---

## Dataset

The dataset contains medical and genetic information collected from patients. Some of the important features include:

- Patient Age
- Gender
- Maternal Gene
- Paternal Gene
- Blood Cell Count
- White Blood Cell Count
- Blood Test Result
- Birth Defects
- Family Medical History
- Symptoms
- Genetic Disorder (Target Variable)

For this project, **Genetic Disorder** is used as the target variable, while **Disorder Subclass** has been excluded to simplify the classification task.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Visual Studio Code
- Jupyter Notebook

---

## Data Preprocessing

The preprocessing stage includes:

- Loading the training and testing datasets
- Removing unnecessary columns
- Replacing invalid values
- Handling missing values
- Imputing numerical values using the median
- Imputing categorical values using the mode
- Encoding categorical variables
- Preparing the dataset for machine learning

---

## Exploratory Data Analysis

Exploratory Data Analysis was performed to better understand the dataset before training the model.

The analysis includes:

- Dataset overview
- Data type inspection
- Statistical summary
- Missing value analysis
- Distribution of the target variable
- Histograms
- Count plots
- Scatter plots
- Line graphs
- Box plots
- Correlation heatmap
- Pair plots

These visualizations help identify feature distributions, relationships between variables, and potential outliers.

---

## Machine Learning Workflow

The project follows the following workflow:

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Encoding
5. Feature Selection
6. Model Training
7. Prediction
8. Model Evaluation

---

## Machine Learning Model

The primary model used in this project is:

- Logistic Regression

The model is trained to classify patients into different categories of genetic disorders based on the available clinical and genetic features.

---

## Repository Structure

```text
Genetic-Disorder-Prediction/
│
├── genome_train.csv
├── genome_test.csv
├── train_cleaned.csv
├── test_cleaned.csv
├── preprocessing.ipynb
├── eda.ipynb
├── ml_model.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Genetic-Disorder-Prediction.git
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Usage

1. Load the dataset.
2. Run the preprocessing notebook.
3. Perform exploratory data analysis.
4. Train the machine learning model.
5. Evaluate the model performance.

---

## Future Improvements

Potential enhancements include:

- Training additional machine learning models
- Hyperparameter tuning
- Feature selection techniques
- Cross-validation
- Improving prediction accuracy
- Developing a web application for deployment

---

## Author

**Jiya**

First-Year Bioinformatics Student with an interest in Bioinformatics, Data Science, and Machine Learning.

---

## License

This project is licensed under the GNU General Public License v3.0.
