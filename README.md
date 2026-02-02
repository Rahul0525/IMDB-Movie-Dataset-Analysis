

---

# IMDB Movie Dataset Analysis

### Merge & GroupBy Operations in Pandas

## 📌 Project Overview

This project demonstrates **data merging and aggregation techniques in Pandas** using an IMDB movie dataset.
It focuses on combining multiple DataFrames using different join strategies and performing insightful **groupby operations** for analysis.

The notebook is designed as a **learning-oriented, hands-on guide** for understanding real-world data manipulation in Python.

---

## 📂 Dataset

The dataset is based on **IMDB movie-related data**, which is split into multiple subsets to demonstrate:

* DataFrame merging
* Join behavior
* Aggregation and grouping

*(The dataset is assumed to be available in the notebook environment or loaded directly within the notebook.)*

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Google Colab / Jupyter Notebook**

---

## 🔑 Key Concepts Covered

### 1. DataFrame Creation

* Creation of multiple subsets from the original IMDB dataset
* Understanding relational structure between datasets

### 2. Merge Operations in Pandas

The notebook demonstrates the following merge techniques:

* **Inner Join**
* **Left Join**
* **Right Join**
* **Outer Join**

```python
pd.merge(df1, df2, on='column_name', how='inner')
```

Each join type is explained with examples and outputs.

---

### 3. Concatenation

Combining DataFrames using:

```python
pd.concat([df1, df2], axis=0)
```

---

### 4. GroupBy Operations

Aggregation and analysis using:

* `groupby()`
* `mean()`
* `count()`
* `sum()`

Example use cases include:

* Average ratings by category
* Movie count per group
* Summary statistics

---

## ▶️ How to Run the Notebook

1. Clone the repository:

```bash
git clone https://github.com/Rahul0525/IMDB-Movie-Dataset-Analysis.git
```

2. Open the notebook:

```bash
IMDB_Movie_Dataset_Analysis.ipynb
```

3. Run all cells in **Jupyter Notebook** or **Google Colab**

---

## 📖 References

* Pandas Merge Documentation:
  [https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html](https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html)

---

## 🎯 Learning Outcomes

By completing this notebook, you will:

* Understand different types of SQL-style joins in Pandas
* Learn how to combine multiple datasets effectively
* Perform grouped data analysis on real-world datasets
* Build strong foundations for data analysis projects

---
