# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an end-to-end exploratory data analysis (EDA) on the Titanic dataset provided as `Titanic dataset.csv`. The objective is to clean the data, analyze survival patterns, and visualize meaningful trends using Python libraries.

---

## 📌 Objective

- Load and inspect the dataset
- Clean missing or irrelevant data
- Perform grouping and aggregation
- Visualize key relationships
- Generate summary insights

---

## 📂 Dataset

- **Filename**: `Titanic dataset.csv`
- Contains passenger details such as age, class, gender, and survival status.
- Used for analyzing survival patterns based on various factors.

---

## 🧪 Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 EDA Workflow

1. **Data Loading & Inspection**
   - Used `pandas` to read the CSV file
   - Explored data structure and missing values

2. **Data Cleaning**
   - Dropped the `Cabin` column (due to missing values)
   - No missing values found in other columns

3. **Grouping & Aggregation**
   - Calculated survival rates by `Sex`
   - Calculated survival rates by `Pclass`

4. **Visualizations**
   - Histogram of Age distribution
   - Barplot of Survival by Class and Gender
   - Correlation heatmap for numerical features

5. **Insights**
   - Males had a higher survival rate than females in this dataset (66.7% vs 25%)
   - First-class passengers had the highest survival rate (66.7%)
   - Indicates possible sampling or custom data configuration




