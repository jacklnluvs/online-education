# 🎓 Online Education Student Performance Analysis

> 📊 Analyzing student engagement and predicting academic performance using Python and Machine Learning.

## 📌 Project Overview

This project analyzes an **online education dataset** to understand how student engagement is related to academic performance.

The project explores factors such as **total clicks, engagement level, final results, and pass/fail performance**. A **Logistic Regression** model is also implemented to examine the relationship between student engagement and passing outcomes.

---

## 🎯 Objectives

* 📚 Analyze student performance in online education
* 📊 Explore different engagement levels
* 🔍 Compare pass rates across engagement levels
* 🧹 Handle missing values in the dataset
* 📈 Visualize student engagement and performance
* 🤖 Build a Logistic Regression model
* 💡 Understand whether engagement can help predict passing outcomes

---

## 🛠️ Technologies Used

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| 🐍 Python           | Programming               |
| 🐼 Pandas           | Data manipulation         |
| 🔢 NumPy            | Numerical operations      |
| 📊 Matplotlib       | Data visualization        |
| 🎨 Seaborn          | Statistical visualization |
| 🤖 Scikit-learn     | Machine Learning          |
| 📓 Jupyter Notebook | Development environment   |

---

## 🔎 Project Workflow

```text
📂 Dataset
     ↓
🧹 Data Loading & Inspection
     ↓
📊 Exploratory Data Analysis
     ↓
📈 Engagement vs Pass Rate Analysis
     ↓
🧹 Missing Value Handling
     ↓
⚙️ Feature Scaling
     ↓
🤖 Logistic Regression
     ↓
📌 Model Coefficient Analysis
```

---

## 📊 Analysis Performed

### 1️⃣ Dataset Exploration

The dataset is loaded using Pandas and explored using:

* `head()`
* `tail()`
* `info()`
* Value counts

The `final_result` column is also analyzed to understand the distribution of student outcomes.

### 2️⃣ Engagement Level Analysis

The project calculates the average `pass_flag` for different **engagement levels**.

This helps identify how **Low, Medium, and High engagement** are associated with student passing outcomes.

### 3️⃣ Data Visualization

A bar chart is created to visualize:

**Engagement Level → Pass Rate**

This makes it easier to identify differences in academic outcomes across engagement groups.

### 4️⃣ Missing Value Handling

Missing values in:

* `total_clicks`
* `pass_flag`

are handled before applying the machine learning model.

### 5️⃣ Machine Learning

A **Logistic Regression** model is trained using:

**Feature:**

* `total_clicks`

**Target:**

* `pass_flag`

The `total_clicks` feature is standardized using `StandardScaler` before training the model.

---

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is used to model the relationship between the number of online learning interactions (`total_clicks`) and whether a student passes (`pass_flag`).

The model coefficient is also examined to understand the direction of the relationship between the feature and the target.

---

## 📁 Project Structure

```text
Online-Education-Analysis/
│
├── 📓 Untitled7.ipynb
├── 📄 online_education_dataset.csv
└── 📖 README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/online-education-analysis.git
```

### 2. Open the project

Open `Untitled7.ipynb` using **Jupyter Notebook** or **Google Colab**.

### 3. Install required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 4. Run the notebook

Make sure `online_education_dataset.csv` is in the same directory as the notebook.

Then run the cells sequentially.

---

## 📌 Key Features

✨ Student performance analysis
📊 Engagement-level comparison
📈 Data visualization
🧹 Missing-value handling
⚙️ Feature scaling
🤖 Logistic Regression
📚 Online education analytics

---

## 🔮 Future Improvements

* Add more student-related features to the prediction model
* Evaluate model accuracy and other performance metrics
* Create a confusion matrix
* Compare Logistic Regression with other ML algorithms
* Build an interactive dashboard using **Streamlit**
* Add more visualizations for student behavior and performance

---

## 👩‍💻 Author

**Jacklyne**

🎓 BCA Student
💻 Interested in Technology, Design & Data Analytics

---

⭐ If you find this project useful, consider giving the repository a **star**!
