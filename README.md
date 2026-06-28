# 🎬 Netflix Movie Data Analysis using Python

## 📌 Project Overview

Netflix Movie Data Analysis is a Python-based data analytics project that explores a real-world movie dataset to uncover meaningful insights into movie popularity, genres, ratings, and release trends. The project demonstrates the complete data analysis workflow, including data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), and visualization using Python.

---

## 🎯 Objectives

* Load and understand the movie dataset.
* Clean and preprocess the data.
* Remove unnecessary columns.
* Handle missing and duplicate values.
* Categorize movie ratings using quartiles.
* Analyze movie genres and popularity.
* Explore release year trends.
* Create informative visualizations.
* Extract meaningful business insights.

---

## 📂 Dataset

**Dataset Name:** `mymoviedb.csv`

### Dataset Features

* Release_Date
* Title
* Overview
* Popularity
* Vote_Count
* Vote_Average
* Original_Language
* Genre
* Poster_Url

**Total Records:** 9,827 Movies

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Inspection
4. Data Cleaning
5. Feature Engineering
6. Exploratory Data Analysis (EDA)
7. Data Visualization
8. Insights & Conclusion

---

## 🧹 Data Cleaning

* Converted `Release_Date` into DateTime format.
* Extracted release year.
* Removed unnecessary columns:

  * Overview
  * Original_Language
  * Poster_Url
* Checked missing values.
* Checked duplicate records.
* Verified data types.
* Prepared a clean dataset for analysis.

---

## ⚙️ Feature Engineering

* Categorized `Vote_Average` into:

  * Not Popular
  * Below Average
  * Average
  * Popular
* Split multiple genres into individual rows using `explode()` for accurate genre-level analysis.

---

## 📈 Exploratory Data Analysis

The project explores:

* Genre Distribution
* Movie Popularity
* Vote Average Distribution
* Vote Count Analysis
* Release Year Trends
* Most Popular Movie
* Least Popular Movie

---

## 📌 Key Insights

* 🎭 Drama is the most frequent movie genre.
* ⭐ Popular-rated movies represent a significant portion of the dataset.
* 🕷️ **Spider-Man: No Way Home** has the highest popularity score.
* 🎬 **The United States vs. Billie Holiday** and **Threads** have the lowest popularity values.
* 📅 The year **2020** contains the highest number of movie releases.

---

## 📁 Project Structure

```text
Netflix-Movie-Analysis/
│
├── Netflix_Movie_Analysis.ipynb
├── mymoviedb.csv
├── README.md
├── requirements.txt
└── images/
```

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/Netflix-Movie-Analysis.git
```

### Navigate to the Project

```bash
cd Netflix-Movie-Analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open:

```text
Netflix_Movie_Analysis.ipynb
```

using Jupyter Notebook or JupyterLab.

---

## 📦 Requirements

```text
numpy
pandas
matplotlib
seaborn
```

---

## 📸 Project Output

The project generates visualizations that highlight:

* Genre frequency
* Rating distribution
* Movie popularity
* Release year trends
* Dataset insights

---

## 🚀 Future Improvements

* Build a Movie Recommendation System.
* Perform Sentiment Analysis on movie reviews.
* Develop an interactive dashboard using Streamlit or Power BI.
* Predict movie popularity using Machine Learning.

---

## 👩‍💻 Author

**Ishika Sharma**

Computer Science Engineering Student

Passionate about Python, Data Analytics, Machine Learning, and building real-world data-driven projects.

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!

