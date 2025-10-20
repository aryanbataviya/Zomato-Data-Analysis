## 🧾 **README.md for Zomato Data Analysis Project**

# 🍽️ Zomato Data Analysis

This project explores and analyzes restaurant data from **Zomato** to uncover insights about restaurant types, customer preferences, ratings, costs, and more.
It uses Python’s data analysis and visualization libraries to extract meaningful trends from the dataset.

---

## 📊 **Project Overview**

The **Zomato Data Analysis** project aims to answer key business questions such as:

* What type of restaurants do customers prefer the most?
* Which areas have the highest number of restaurants?
* How does online ordering affect restaurant ratings?
* What is the relationship between cost for two and ratings?
* Which cuisines are the most popular?

---

## 🧠 **Objectives**

* Clean and preprocess raw Zomato dataset
* Perform exploratory data analysis (EDA)
* Visualize customer trends and restaurant patterns
* Derive insights that can help in business decision-making

---

## 🧰 **Technologies Used**

| Category             | Tools/Libraries                        |
| -------------------- | -------------------------------------- |
| Programming Language | Python 🐍                              |
| Data Handling        | Pandas, NumPy                          |
| Visualization        | Matplotlib, Seaborn                    |
| Environment          | Jupyter Notebook                       |
| Dataset              | Zomato restaurant dataset (CSV format) |

---

## 🧹 **Data Cleaning**

* Removed duplicate entries
* Handled missing values
* Dropped irrelevant columns (`url`, `address`, `phone`)
* Standardized column names
* Converted data types where necessary

---

## 🔍 **Exploratory Data Analysis (EDA)**

Key analyses performed:

1. **Top restaurant locations**
2. **Most popular cuisines**
3. **Distribution of ratings**
4. **Online order vs. rating relationship**
5. **Cost for two vs. rating correlation**
6. **Most ordered restaurant type**

---

## 📈 **Visualizations**

The notebook includes plots such as:

* Bar charts for top cuisines and locations
* Scatter plot for cost vs. rating
* Box plots for online order and book table comparisons
* Histograms for rating distributions

---

## 🏁 **Insights**

* Majority of customers order from **Quick Bites** type restaurants.
* Online ordering is associated with slightly higher average ratings.
* Most restaurants are concentrated in a few popular localities.
* North Indian and Chinese cuisines dominate the dataset.
* Cost for two does not strongly influence rating.

---

## 📂 **Project Structure**

```
Zomato_Data_Analysis/
│
├── Zomato_Analysis.ipynb      # Main Jupyter Notebook
├── Zomato data .csv           # Dataset
├── README.md                  # Project documentation
└── images/                    # (Optional) Visualization images
```

---

## 🚀 **How to Run the Project**

1. Clone this repository

   ```bash
   git clone https://github.com/<your-username>/Zomato_Data_Analysis.git
   ```
2. Navigate to the project directory

   ```bash
   cd Zomato_Data_Analysis
   ```
3. Install the required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open Jupyter Notebook

   ```bash
   jupyter notebook
   ```
5. Run **Zomato_Analysis.ipynb**





