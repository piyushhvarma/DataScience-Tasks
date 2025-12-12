

## 1. Overview

This repository contains all the tasks completed during my **Data Science Internship**.

I used **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **Jupyter/Colab** to analyze and visualize the dataset.

The goal was to **clean data**, **explore patterns**, **create features**, and **build simple predictive models**.

---

## 2. Tasks Completed

### 🔹 Task 1: Data Exploration & Preprocessing
* Loaded the dataset and checked rows and columns.
* Identified and handled **missing values**.
* Converted data types where required.
* Analyzed the distribution of **Aggregate Rating**.
* Checked for class imbalance.

### 🔹 Task 2: Statistical Analysis
* Calculated mean, median, standard deviation, etc.
* Explored categorical columns (**City**, **Country Code**, **Cuisines**).
* Found top cuisines and top cities with most restaurants.

### 🔹 Task 3: Geospatial Analysis
* Plotted restaurant locations on a map using latitude/longitude.
* Studied distribution of restaurants across cities and countries.
* Checked if location affects ratings.

### 🔹 Task 4: Table Booking & Online Delivery
* Calculated percentage of restaurants offering **table booking** and **online delivery**.
* Compared ratings of restaurants with and without table booking.
* Analyzed online delivery availability across different price ranges.

### 🔹 Task 5: Price Range Analysis
* Identified the **most common price range**.
* Calculated **average rating** for each price range.
* Found the rating color linked to the highest-rated price range.

### 🔹 Task 6: Feature Engineering
Created simple new features:
* Name length
* Address length
* Number of cuisines
* Table booking flag (0/1)
* Online delivery flag (0/1)

> These features help improve data understanding and modeling performance.

### 🔹 Task 7: Predictive Modeling
Built **regression models** to predict restaurant ratings. Used:
* **Linear Regression**
* **Decision Tree Regressor**
* **Random Forest Regressor**

Split data into training/testing sets. Evaluated using **MAE**, **MSE**, **RMSE**, and **R²**. Compared which model performed best.

### 🔹 Task 8: Customer Preference Analysis
* Studied how **cuisine type** relates to rating.
* Identified most popular cuisines based on votes.
* Found cuisines that tend to receive **higher ratings**.

### 🔹 Task 9: Data Visualization
* Created histograms, bar charts, scatter plots, and boxplots.
* Visualized rating distribution, top cuisines, and top cities.
* Explored feature relationships with ratings.

---

## 3. Tools Used

* **Python**
* **Google Colab / Jupyter Notebook**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **Folium** (for maps)

---

## 4. How to Run

1.  Open any `.ipynb` file in Google Colab or Jupyter Notebook.
2.  Upload the dataset (`dataset.csv`).
3.  Run the notebook cells in order to see the results.

---

## 5. Conclusion

This internship helped me understand **data cleaning**, **visualization**, **feature engineering**, and building simple **predictive models**.

I learned how to analyze restaurant trends, customer preferences, and rating behavior effectively.