# 📊 Netflix Titles Dataset – Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the [Netflix Titles dataset](https://www.kaggle.com/shivamb/netflix-shows). The dataset includes details of movies and TV shows available on Netflix as of 2021.

---

## 🔍 About the Project

**Exploratory Data Analysis (EDA)** is the first step in the data science process. It helps to:
- Understand the structure of the dataset.
- Identify patterns, trends, and anomalies.
- Formulate questions and hypotheses.
- Prepare the dataset for further analysis or modeling.

This project uses the Netflix dataset to showcase how EDA is done using Python tools.

---

## 📁 Dataset Description

The dataset contains the following features:
- **show_id**: Unique ID for each show
- **type**: Movie or TV Show
- **title**: Title of the show
- **director, cast, country**: Metadata
- **date_added**: When it was added to Netflix
- **release_year**: Release year
- **rating**: Age rating (e.g., PG, TV-MA)
- **duration**: Duration of the show
- **listed_in**: Genre(s)
- **description**: Summary of the show

---

## 🧰 Tech Stack

| Tool | Use |
|------|-----|
| `pandas` | Data loading and manipulation |
| `numpy` | Numeric operations |
| `matplotlib` & `seaborn` | Data visualization |
| `Jupyter Notebook` | Interactive analysis and plotting |

---

## 📌 EDA Tasks Performed

- Data loading and preview
- Dataset info and summary statistics
- Missing value analysis and visualization
- Distribution plots for numerical features
- Outlier detection using boxplots
- Correlation matrix heatmap
- Pairplots (if applicable)
- Categorical feature analysis via count plots

---

## ▶ Installation & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/netflix-eda.git
   cd netflix-eda
