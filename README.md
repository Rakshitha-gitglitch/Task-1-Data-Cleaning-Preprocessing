#  Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare raw data for Machine Learning by performing missing value handling, encoding, scaling, and outlier removal.

## Dataset
Used: [Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## Tools Used
- Python 🐍
- Pandas
- NumPy
- Seaborn / Matplotlib

---

##  What I Did

1. **Loaded the dataset** using `pandas.read_csv()` and explored data with `.info()`, `.describe()`.
2. **Handled missing values**:
   - Imputed `Age` with median
   - Filled `Embarked` with mode
   - Dropped `Cabin` due to high missing rate
3. **Encoded categorical columns**:
   - Applied One-Hot Encoding on `Sex` and `Embarked`
4. **Standardized numerical features**:
   - Used `StandardScaler` for `Age` and `Fare`
5. **Detected and removed outliers**:
   - Used boxplots and IQR method to clean outliers in `Fare`

---

## Key Concepts Practiced
- Mean/Median Imputation  
- One-Hot Encoding  
- Standardization vs Normalization  
- Outlier Detection using Boxplots & IQR  

---

## Output Files
- `cleaned_titanic.csv`: Final cleaned dataset
- `data_cleaning.py`: Python script with preprocessing logic


---

