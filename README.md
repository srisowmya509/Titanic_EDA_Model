# Titanic EDA and Survival Prediction

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns and trends that affected passenger survival. The goal is to understand the data, engineer meaningful features, and build a machine learning model to predict survival.

## Dataset
The dataset contains information about Titanic passengers including demographic details, ticket information, and whether they survived the tragedy.

## Key Steps

1. **Data Cleaning and Preprocessing**  
   - Handled missing values in features like Age and Embarked.  
   - Encoded categorical variables (Sex, Embarked) into numeric form.

2. **Exploratory Data Analysis (EDA)**  
   - Generated summary statistics (mean, median, std, etc.) for numerical features.  
   - Visualized data distributions using histograms and boxplots.  
   - Used correlation matrices and pairplots to examine relationships between features.  
   - Identified patterns such as higher survival among females and first-class passengers.  
   - Detected anomalies and outliers in Fare and Age.

3. **Feature Engineering**  
   - Created new features like `FamilySize` (SibSp + Parch + 1) and `IsAlone` (whether the passenger was traveling alone).  
   - Scaled continuous variables to improve model performance.

4. **Model Building and Evaluation**  
   - Split the data into training and testing sets.  
   - Trained a Logistic Regression model to predict survival.  
   - Evaluated model performance using accuracy, classification report, and confusion matrix.  
   - Achieved approximately 80% accuracy on test data.

## Results and Insights
- Females had significantly higher survival rates than males.  
- Passengers in first class had better chances of survival compared to lower classes.  
- Younger passengers, especially children, tended to survive more often.  
- Large family size had an impact on survival chances.  
- The model shows good predictive ability with balanced precision and recall.

## How to Use
- Open the notebook in [Google Colab](https://colab.research.google.com/) or run locally with Jupyter Notebook.  
- Follow the steps in the notebook to reproduce the EDA, feature engineering, and model training.

## Dependencies
- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn
