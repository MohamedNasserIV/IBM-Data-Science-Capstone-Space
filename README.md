# IBM Data Science Capstone – SpaceX Landing Prediction

## Overview

This project is part of the **IBM Data Science Professional Certificate Capstone**.
It analyzes **SpaceX Falcon 9 launch data** and builds **machine learning classification models** to predict whether the **first-stage booster will land successfully**.

The project also includes:

* SQL analysis
* Exploratory data visualization
* Interactive Folium maps
* Plotly Dash dashboard for launch analytics

These insights help estimate **launch cost reduction** and support **mission planning decisions**.

---

## Objectives

* Collect SpaceX launch data from **REST APIs and public datasets**
* Perform **data wrangling and feature engineering**
* Conduct **exploratory data analysis (EDA)** using SQL and visualization
* Build **interactive visual analytics** with Folium and Plotly Dash
* Train and evaluate **classification models** to predict landing success

---

## Repository Structure

```
IBM-Data-Science-Capstone-SpaceX/
│
├── notebooks/        # Project notebooks (API, wrangling, EDA, ML, Dash)
├── data/             # Datasets used in the project
├── screenshots/      # Maps, dashboard, confusion matrix, results
├── presentation/     # Final PowerPoint presentation
└── README.md         # Project documentation
```

---

## Methodology

### Data Collection

* Retrieved launch data using **SpaceX REST API calls**
* Parsed JSON responses and converted them into structured datasets
* Stored processed data for analysis

### Data Wrangling

* Handled missing values and inconsistent formats
* Created **landing outcome labels**
* Converted categorical variables using **one-hot encoding**

### Exploratory Data Analysis

* Used **SQL queries** and **visualizations** to explore:

  * Payload impact on landing success
  * Launch site performance
  * Orbit distribution

### Interactive Analytics

* Built **Folium maps** to visualize launch locations
* Developed a **Plotly Dash dashboard** for interactive filtering and insights

### Predictive Modeling

* Trained and evaluated:

  * Logistic Regression
  * Support Vector Machine (SVM)
  * Decision Tree
  * Random Forest
* Compared models using:

  * Accuracy
  * Precision & Recall
  * F1-Score
  * Confusion Matrix

---

## Results

* **Payload mass, orbit type, and launch site** strongly influence landing success.
* **Random Forest** achieved the best overall predictive performance.
* Interactive dashboards and maps provide **clear visualization of success patterns**.

These findings demonstrate how **data science supports reusable rocket economics**.

---

## Technologies Used

* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* SQL
* Folium
* Plotly Dash
* Jupyter Notebook

---

## Author

**Mohamed Ragab**
IBM Data Science Professional Certificate Candidate

---

## License

This project is created for **educational purposes** as part of the IBM Data Science Capstone.
