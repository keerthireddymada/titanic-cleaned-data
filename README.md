# Titanic Dataset - Data Cleaning & Preprocessing

This project focuses on preparing the Titanic dataset for machine learning by performing essential data cleaning and preprocessing steps.

## Steps Completed

1. **Loaded the Dataset**  
   - Used `pandas` to import the CSV file.

2. **Explored the Data**  
   - Checked for missing values and data types.
   - Visualized key distributions and columns.

3. **Handled Missing Values**  
   - Filled missing `Age` values with median age.
   - Filled missing `Embarked` with the most common port.

4. **Encoded Categorical Variables**  
   - Converted `Sex`, `Embarked`, and extracted titles from `Name`.
   - Applied label/one-hot encoding where necessary.

5. **Dropped Unnecessary Columns**  
   - Removed `Ticket` and `Cabin` due to high missing values or irrelevance.

6. **Feature Scaling**  
   - Standardized numerical features like `Age` and `Fare` using `StandardScaler`.

7. **Removed Outliers**  
   - Used IQR method to remove outliers in `Age` and `Fare` columns.
   - Visualized before/after using boxplots.

## Output
- Final cleaned dataset: `cleaned_titanic.csv`

---

This preprocessing makes the dataset ready for training ML models in the next step.
