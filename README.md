# 📊 Netflix Data Analysis using Pandas

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies and TV Shows** dataset using **Python and Pandas**.  
It focuses on real-world **data cleaning, transformation, and analysis**, making it an ideal beginner-to-intermediate Pandas project.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Google Colab / Jupyter Notebook**
- **GitHub**

---

## 📂 Dataset

**Netflix Movies and TV Shows Dataset** (CSV format)

The dataset includes information such as:

- Type (Movie / TV Show)
- Title
- Director
- Country
- Date Added
- Release Year
- Rating
- Duration

---

## 🔍 Analysis Performed

- Loading and inspecting data
- Handling missing values
- Data cleaning and formatting
- Extracting year from date columns
- Movies vs TV Shows distribution
- Country-wise content analysis
- Year-wise content trends

---

## 📈 Key Insights

- 🎬 Movies dominate Netflix’s content library
- 🇺🇸 The United States produces the most content
- 📅 Majority of content was added after **2015**

---

## 🗂️ Project Structure

```text
pandas-netflix-eda/
│
├── data/
│   └── netflix_titles.csv
│
├── notebook.ipynb
│
└── README.md
```

## ▶️ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/pandas-netflix-eda.git
```

### 2️⃣ Install Dependencies
```bash
pip install pandas
```

### 3️⃣ Run the Notebook

Open `notebook.ipynb` in **Jupyter Notebook** or **Google Colab**.

## 🧪 Sample Code Snippet

```python
import pandas as pd

df = pd.read_csv("data/netflix_titles.csv")

# Display first 5 rows
df.head()
```


## 🚀 Future Improvements

- Add data visualizations using Matplotlib & Seaborn

- Perform genre-based analysis

- Apply machine learning for content recommendation

- Build an interactive dashboard

## 🧠 Learning Outcome

This project strengthened my understanding of:

- Real-world data cleaning

- Pandas data manipulation

- Exploratory data analysis techniques

- Writing clean and readable analysis code

## 📄 License

This project is licensed under the MIT License.

⭐ If you find this project helpful, consider giving it a star!
