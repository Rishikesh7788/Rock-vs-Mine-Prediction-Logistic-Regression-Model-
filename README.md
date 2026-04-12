# Rock vs. Mine Prediction - Logistic Regression Model

A machine learning classification project that uses Logistic Regression to predict whether sonar signals detected underwater represent a rock or a mine. Built using the UCI Sonar dataset and implemented in a Jupyter Notebook.

## Overview

This project demonstrates binary classification using Logistic Regression. The model is trained on sonar signal data to distinguish between two classes:
- **R** (Rock)
- **M** (Mine)

## Dataset

- **Source**: UCI Machine Learning Repository - Sonar Dataset
- **Features**: 60 sonar signal frequency measurements
- **Classes**: 2 (Rock vs. Mine)
- **Samples**: 208 instances

## Technologies Used

- **Python** - Programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning library
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Project Workflow

1. **Data Loading & Exploration** - Load the Sonar dataset and perform initial data exploration
2. **Data Preprocessing** - Handle missing values, encode categorical variables
3. **Exploratory Data Analysis (EDA)** - Visualize data distributions and correlations
4. **Train-Test Split** - Split data into training (80%) and testing (20%) sets
5. **Model Training** - Train a Logistic Regression classifier
6. **Model Evaluation** - Evaluate using accuracy, confusion matrix, and classification report

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rishikesh7788/Rock-vs-Mine-Prediction-Logistic-Regression-Model-.git
   ```

2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook "Rock vs Mine Prediction.ipynb"
   ```

## Results

The model achieves classification accuracy on the test set, demonstrating effective discrimination between rock and mine sonar signals.

## Files

- `Rock vs Mine Prediction.ipynb` - Jupyter Notebook with the complete implementation
- `Copy of sonar data.csv` - The Sonar dataset
- `README.md` - Project documentation

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## License

MIT License

---
