<h1 align="center">🎓 Udemy Courses Analysis</h1>

<p align="center">
  Exploratory data analysis of 3,676 Udemy courses using Python
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Seaborn-Visualization-4C8CBF" alt="Seaborn">
  <a href="https://www.kaggle.com/"><img src="https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"></a>
</p>

## 📌 Overview

This project explores the **Udemy Courses** dataset. It cleans the data, answers questions about subjects, levels, pricing, subscribers, reviews and publishing years with Pandas, and visualizes the results with Matplotlib and Seaborn.

---

## ⚡ At a Glance

| 🧾 Courses | 💳 Paid | 🆓 Free | 🐍 Python Courses | 📅 Years Covered |
|:---:|:---:|:---:|:---:|:---:|
| **3,676** | **3,366** | **310** | **29** | **2011 – 2017** |

---

## 🔄 Workflow

1. **Load & Inspect** – Loaded `Udemy_Courses.csv` (3,682 rows × 11 columns) and reviewed it with `head()`, `shape` and `info()`.
2. **Clean** – Found no missing values, but found duplicate rows and removed them, leaving 3,676 courses.
3. **Feature** – Extracted `Year` from `published_timestamp`.
4. **Analyze** – Answered the questions below with `value_counts()`, `groupby()`, filtering and string operations.
5. **Visualize** – Built count plots, bar plots and a scatter plot with Seaborn.

> **Columns:** `course_id` · `course_title` · `is_paid` · `price` · `num_subscribers` · `num_reviews` · `num_lectures` · `level` · `content_duration` · `published_timestamp` · `subject` · `Year`

---

## 🔍 Key Findings

| Question | Result |
|---|---|
| Courses per subject | Web Development **1,199** · Business Finance **1,195** · Musical Instruments **680** · Graphic Design **602** |
| Courses per level | All Levels **1,928** · Beginner **1,269** · Intermediate **421** · Expert **58** |
| Paid vs. free courses | **3,366** paid · **310** free |
| Average lectures per course | Paid **≈ 41.8** · Free **≈ 21.4** |
| Most popular course (subscribers) | **Learn HTML5 Programming From Scratch** |
| Courses with "python" in the title | **29** |
| Year with the most published courses | **2016** (1,204 courses) |

**Courses published per year**

| 2011 | 2012 | 2013 | 2014 | 2015 | 2016 | 2017 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 5 | 45 | 201 | 490 | 1,014 | **1,204** | 717 |

---

## 📊 Questions Explored

| # | Question |
|:---:|---|
| 1 | How many courses are there per subject? |
| 2 | How many courses are there per level? |
| 3 | How many courses are paid vs. free? |
| 4 | Which has more lectures, free or paid courses? |
| 5 | Which has more subscribers, free or paid courses? |
| 6 | Which level has the most subscribers? |
| 7 | What is the most popular course? |
| 8 | What are the top 10 courses by subscribers? |
| 9 | Which level, subject and courses have the most reviews? |
| 10 | Do free or paid courses have more reviews? |
| 11 | Does price affect the number of reviews? |
| 12 | How many courses are related to Python, and which are the 10 most popular? |
| 13 | In which year were the most courses published? |
| 14 | How many courses per subject were published each year? |
## 👩‍💻 Author

**Marwa Samy** · [GitHub](https://github.com/marwa23-rgb)
