📘 Student Performance Analysis

This project analyzes the Student Performance Dataset (student-mat.csv) to explore relationships between study habits, family background, and final grades.

📂 Dataset

Source: UCI Machine Learning Repository

Rows: 395

Columns: 33

Target Variable: G3 (Final Grade)

🔹 Steps Performed
1. Load Dataset

Used pandas to read the dataset (; separated).

2. Data Cleaning

Checked and handled missing values

Removed duplicates

Verified column data types

3. Data Analysis

✅ Average final grade of students

✅ Number of students scoring above 15

✅ Correlation between study time and grades

✅ Gender-wise performance comparison

4. Data Visualization

📊 Histogram of grades (G3)

📉 Scatter plot: Study time vs Grades

📦 Bar chart: Male vs Female average grades

🔎 Tools Used

Python 🐍

Pandas

Matplotlib

📌 Findings (example — update with your results)

Average final grade: 10.4

Students scoring above 15: 90

Study time shows weak correlation with grades

On average, female students perform slightly better than male students

🚀 How to Run

Clone this repo

git clone https://github.com/your-username/student-performance-analysis.git


Install requirements (if any)

pip install pandas matplotlib


Open Jupyter Notebook and run:

jupyter notebook student_performance.ipynb
