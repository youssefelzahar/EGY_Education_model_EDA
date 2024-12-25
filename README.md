# EGY Education Model and Exploratory Data Analysis (EDA)

This repository contains the implementation of a machine learning model and exploratory data analysis (EDA) for the **Egyptian Education Dataset**. The aim is to analyze key trends and insights from the dataset and build predictive models for educational outcomes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project focuses on:

1. **Exploratory Data Analysis (EDA):**
   - Analyzing trends and patterns in the dataset.
   - Identifying key factors affecting educational outcomes.
2. **Machine Learning Modeling:**
   - Developing predictive models to forecast outcomes.
   - Evaluating model performance with various metrics.

## Features

- Interactive visualizations to explore the data.
- Machine learning pipeline for preprocessing, training, and evaluation.
- Implementation of advanced models like XGBoost, Random Forest, and Support Vector Machines (SVM).
- Comprehensive feature engineering for improving model performance.

## Dataset

The dataset used in this project contains educational data from Egyptian institutions. It includes features like:

- Student demographics.
- Academic performance.
- Institutional statistics.

**Note:** Due to privacy concerns, the dataset is not included in this repository. Please use your dataset or contact the author for further details.

## Installation

To run the code in this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/youssefelzahar/EGY_Education_model_EDA.git
   ```

2. Navigate to the repository folder:
   ```bash
   cd EGY_Education_model_EDA
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook model.ipynb
   ```

## Usage

1. Run the notebook `model.ipynb` to explore the EDA and modeling steps.
2. Modify parameters in the code for custom analyses and predictions.

## Modeling

The project implements the following models:

- **Logistic Regression** for baseline classification.
- **Random Forest** for feature importance analysis.
- **Decision Tree Classifier** for interpretable modeling.
- **Gradient Boosting Classifier** for advanced classification.
- **K-Nearest Neighbors (KNN)** for instance-based learning.

### Preferred Algorithm

The **Decision Tree Classifier** was selected as the preferred algorithm based on the Confusion Matrix (CM) analysis, offering the best balance of performance and interpretability.

### Key Steps:

1. **Data Preprocessing:** Handling missing values, scaling, and encoding.
2. **Feature Engineering:** Creating meaningful features to improve model performance.
3. **Model Training:** Training and optimizing models using cross-validation.
4. **Evaluation:** Using metrics like R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## Results

- **EDA:** Visualizations revealed key insights about student performance and institutional trends.
- **Model Performance:**
  - Best-performing model: **Decision Tree Classifier**
  

For detailed results, check the `model.ipynb` notebook.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
