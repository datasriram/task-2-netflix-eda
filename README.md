# task-2-netflix-eda
Exploratory Data Analysis of Netflix Movies and TV Shows dataset using Python.

# Task 2: Netflix Exploratory Data Analysis (EDA)

Exploratory Data Analysis of Netflix Movies and TV Shows dataset using Python and visualization libraries. This task is part of my AI & ML internship focused on developing core data analysis skills.

---

## 📂 Dataset Used
- **Name**: Netflix Titles Dataset
- **Source**: [Kaggle – Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File**: `netflix_titles.csv`
- **Rows**: ~8800 | **Columns**: 12

---

## 📌 Objective
To explore the structure, relationships, and trends in the Netflix dataset using summary statistics and rich visualizations.

---

## 📊 Key Steps Covered
1. **Basic Information & Summary**
   - Used `.info()` and `.describe()` for structure and stats
   - Checked for missing values

2. **Cleaning & Feature Prep**
   - Converted `duration` column for movies to numerical format
   - Parsed `date_added` and extracted `year_added`

3. **Visualizations**
   - Histogram of movie durations
   - Boxplot for outlier detection
   - Correlation heatmap of numerical features
   - Pairplot of related fields
   - Time trend of content releases by year and type

---

## 🛠️ Tools & Libraries
- Python (Google Colab)
- Pandas
- Matplotlib
- Seaborn
- Plotly (optional)

---

## 📁 Files in this Repository

| File Name            | Description                                           |
|----------------------|-------------------------------------------------------|
| `netflix_titles.csv` | Original dataset used for this analysis               |
| `netflix_eda.ipynb`  | Google Colab notebook with full EDA code and plots    |
| `README.md`          | Project overview and documentation                    |

---

## ✅ Outcome
The dataset was successfully explored using Python-based EDA techniques.  
This analysis reveals patterns in content duration, release trends, and relationships between variables like type, release year, and added year.

---

## 🧠 What I Learned
- How to approach any dataset from scratch
- Cleaning and converting real-world messy data
- Using visualization for pattern recognition
- Finding insights beyond basic stats

---

📌 This task was completed as part of a 45-day AI & ML internship project.

