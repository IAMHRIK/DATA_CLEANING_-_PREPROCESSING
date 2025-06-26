# 🧼 Data Cleaning & Preprocessing 

## Objective

- Handle missing values
- Encode categorical variables
- Normalize numerical features
- Detect and visualize outliers


## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Dataset

A small, custom dataset inspired by the Titanic dataset with the following columns:
- `Name`
- `Age`
- `Gender`
- `Survived`
- `Fare`


## Tasks Performed

1. **Imported and explored** the dataset  
2. **Handled missing values** using:
   - Mean for `Age`
   - Median for `Fare`
   - Row drop for missing `Name`
3. **Encoded** categorical variables (`Gender`)
4. **Normalized** numerical features (`Age`, `Fare`) using `StandardScaler`
5. **Visualized outliers** using boxplots

