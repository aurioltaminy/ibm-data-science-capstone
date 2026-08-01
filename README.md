# SpaceX Falcon 9 First Stage Landing Prediction

> **IBM Data Science Professional Certificate — Capstone Project**

## Project Overview

SpaceX advertises Falcon 9 rocket launches at **$62 million**, far below competitors who charge upward of $165 million. The key differentiator: SpaceX reuses the first stage of the rocket. If we can predict whether the first stage will land successfully, we can estimate the true cost of a launch — valuable intelligence for any company looking to compete with SpaceX.

This project builds an end-to-end data science pipeline to predict Falcon 9 first stage landing success.

---

## Project Pipeline

| Step | Notebook | Description |
|------|----------|-------------|
| 1 | `jupyter-labs-spacex-data-collection-api.ipynb` | Data collection via SpaceX REST API |
| 2 | `jupyter-labs-webscraping.ipynb` | Web scraping launch records from Wikipedia using BeautifulSoup |
| 3 | `labs-jupyter-spacex-Data_wrangling.ipynb` | Data wrangling & training label engineering |
| 4 | `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Exploratory Data Analysis with SQL (SQLite) |
| 5 | `lab_jupyter_launch_site_location_jupyterlite.ipynb` | Geospatial analysis of launch sites with Folium |
| 6 | `SpaceX_Machine_Learning_Prediction_Part_5_jupyterlite.ipynb` | ML model training & prediction |

---

## 🔧 Methods & Technologies

**Data Collection**
- SpaceX REST API (HTTP requests)
- Web scraping with `BeautifulSoup` from Wikipedia

**Data Processing**
- `pandas`, `NumPy` — data manipulation and label engineering
- `SQLite` — SQL-based exploratory analysis

**Visualization & Geospatial Analysis**
- `Matplotlib`, `Seaborn` — statistical charts
- `Folium` — interactive maps of launch sites

**Machine Learning**
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Hyperparameter tuning with `GridSearchCV`

---

## Objective

Predict whether the **Falcon 9 first stage will land successfully** (binary classification: `1` = success, `0` = failure), enabling cost estimation for competing rocket launch providers.

---

## Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn folium beautifulsoup4 requests sqlalchemy
```

---

## Certificate

IBM Data Science Professional Certificate — [Coursera](https://www.coursera.org/professional-certificates/ibm-data-science)
