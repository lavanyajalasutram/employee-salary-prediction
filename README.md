[adult.csv](https://github.com/user-attachments/files/21342240/adult.csv)# employee-salary-prediction
Machine Learning project to predict whether an individual's income exceeds $50K/year using the UCI Adult Census Income dataset. Includes data preprocessing, outlier removal, feature encoding, and evaluation of multiple ML models.
---
# Dataset
- Source: [UCI Machine Learning Repository – Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- Features include age, workclass, education, marital status, occupation, race, sex, hours per week, etc.
- Target variable: `income` (binary: `<=50K` or `>50K`)
---
# Workflow
1. Data Cleaning
   - Handling missing values (`?`)
   - Removing outliers from age and education
   - Dropping redundant columns

2. Data Preprocessing
   - Label Encoding for categorical variables
   - Feature scaling using `StandardScaler`

3. Model Training
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)

4. Evaluation
   - Confusion Matrix
   - Accuracy Score
   - Classification Report (Precision, Recall, F1-score)
---
# Results
Each model was trained and tested using a 70-30 train/test split. Evaluation metrics are printed for comparison.


