# Day1

# Task 1: Data Cleaning & Preprocessing

## 🎯 Objective
The goal of this task is to learn how to clean and prepare raw data for Machine Learning by performing essential preprocessing steps.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Files Included
- `data_cleaning.ipynb`: Jupyter Notebook with step-by-step code for data preprocessing.
- `your_dataset.csv`: The raw dataset used (replace with your actual dataset).
- `screenshots/`: Folder containing any screenshots (e.g., of visualizations).
- `README.md`: This file.

---

## 🔄 Steps Performed

### 1. **Data Exploration**
- Loaded the dataset using `pandas`.
- Viewed summary statistics, data types, and checked for missing values.

### 2. **Handling Missing Values**
- Filled missing values using mean or median depending on the column.
- In some cases, dropped rows with excessive missing data.

### 3. **Encoding Categorical Features**
- Converted categorical columns into numerical form using:
  - Label Encoding for binary categories.
  - One-Hot Encoding for multiclass features.

### 4. **Normalization/Standardization**
- Used Min-Max Scaling or Standard Scaling to bring numerical features to the same scale.

### 5. **Outlier Detection and Removal**
- Visualized outliers using boxplots.
- Removed outliers using the IQR (Interquartile Range) method.

---

## 📊 Sample Output

Some visualizations and outputs (boxplots, missing value stats) can be found in the `screenshots/` folder or inside the notebook itself.

---
