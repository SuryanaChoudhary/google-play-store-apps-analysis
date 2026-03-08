# 📱 Google Play Store Apps Analysis & Rating Prediction

## 📌 Project Overview

The Google Play Store hosts millions of mobile applications across various categories. Understanding the factors that influence app ratings and popularity can help developers improve their applications and user experience.

This project performs **exploratory data analysis (EDA)** and **machine learning modeling** to analyze app characteristics and predict app ratings based on different features such as installs, reviews, category, size, and price.

---

## 📊 Dataset

The dataset contains information about thousands of Google Play Store applications including:

* App name
* Category
* Rating
* Reviews
* Size
* Installs
* Price
* Content rating
* Genres
* Last updated

Dataset Source:
https://www.kaggle.com/datasets/lava18/google-play-store-apps

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Project Workflow

1. **Data Loading**

   * Import dataset using pandas.

2. **Data Cleaning**

   * Handling missing values
   * Converting installs and price columns
   * Removing duplicate records

3. **Exploratory Data Analysis**

   * Distribution of app ratings
   * Most popular app categories
   * Relationship between installs and ratings
   * Price vs ratings analysis

4. **Feature Engineering**

   * Transform categorical variables
   * Scaling numerical features

5. **Machine Learning Model**

   * Train-test split
   * Model training using regression algorithms

6. **Model Evaluation**

   * Mean Squared Error (MSE)
   * R² Score

---

## 📈 Key Insights

* Most apps on the Play Store are **free applications**.
* Categories such as **Games and Tools** dominate the store.
* Apps with higher installs generally receive **more reviews**.
* Certain categories consistently receive **higher average ratings**.

---

## 📷 Example Visualization

The project includes visualizations such as:

* Rating distribution
* Category popularity
* Installs vs Reviews relationship
* App size distribution

---

## 🚀 Future Improvements

* Build a **web app for app rating prediction**
* Implement **advanced machine learning models**
* Add **feature importance analysis**

---

## 📂 Project Structure

```
google-play-store-analysis
│
├── notebook
│   └── google-play-store-analysis.ipynb
│
├── images
│
└── README.md
```

---

## 👩‍💻 Author

**Suryana Choudhary**

Data Science | Machine Learning | Python
