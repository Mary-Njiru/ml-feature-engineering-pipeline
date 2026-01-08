# ML Feature Engineering Pipeline

This repository is a comprehensive collection of machine learning projects focused on the critical stage of **Feature Engineering**. It demonstrates how to transform raw data into high-quality features that enhance model accuracy across various domains, including healthcare, urban planning, and natural language processing.

---

## 📂 Project Overview

The repository contains five distinct projects, each tackling unique data challenges:

### 1. 🏥 Alzheimer's Prediction (`alzheimer.ipynb`)
Focuses on preprocessing medical records and diagnostic data.
* **Key Tasks:** Handling missing clinical values, feature scaling for biological markers, and correlation analysis.

### 2. 🎬 Movie Reviews Sentiment (`movie_reviews.ipynb`)
Text-based feature engineering for sentiment classification.
* **Key Tasks:** Text cleaning (stop-word removal, stemming), TF-IDF vectorization, and N-gram extraction.

### 3. 🚗 NYC Vehicle Collisions (`newyork_vehicle_collisions.ipynb`)
Analyzing traffic safety data from New York City.
* **Key Tasks:** Time-series extraction (hour/day/month), geospatial grouping, and categorical encoding for vehicle types.

### 4. 🏗️ Issued Construction Permits (`issued_construction_permits1.ipynb`)
Processing urban development records.
* **Key Tasks:** Date-time feature engineering, handling high-cardinality categorical data, and permit duration calculation.

### 5. 🌬️ Air Monitoring (`air_monitoring.ipynb`)
Environmental data analysis for air quality.
* **Key Tasks:** Smoothing sensor noise, lagging features for time-series forecasting, and outlier detection.

---

## 🛠️ Technical Stack

* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn`
* **Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebooks

---

## 🚀 How to Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Mary-Njiru/ml-feature-engineering-pipeline.git](https://github.com/Mary-Njiru/ml-feature-engineering-pipeline.git)
2. **Install required libraries:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn notebook
3. **Run the notebooks:**
   Open your terminal and run jupyter notebook to explore the specific engineering steps for each dataset.

## 📌 Project Goals
The primary objective of this repository is to showcase:
- Data Cleaning: Dealing with nulls and inconsistent records.
- Feature Extraction: Creating new variables from timestamps and text.
- Feature Selection: Identifying which variables contribute most to model performance.

## Developed by Mary Njiru
