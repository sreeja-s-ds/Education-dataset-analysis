# Education-dataset-analysis

📘 **Student Feedback & Grade Analysis Using Python** 🧑‍🏫

This project analyzes a real-world educational dataset to explore the relationship between student feedback (through question-based surveys) and final grades. The analysis was performed using Python, and the goal is to uncover patterns, correlations, and insights that can improve teaching strategies and course delivery.

🔍 **Project Overview**

The notebook performs a detailed data analysis and visualization using tools from Python’s data science stack:

Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Correlation analysis between survey questions

Outlier detection using boxplots

Grade distribution across courses

Pivot table analysis to evaluate course/grade balance

🔍 **About the Data**

This CSV file contains data for 145 students and includes 33 columns. Here's a breakdown:

**Columns**:

STUDENT ID – Unique identifier for each student (e.g., STUDENT1, STUDENT2, etc.)

Columns 1 to 30 – These likely represent responses or scores to 30 different questions or items (numbered 1 to 30).

COURSE ID – Identifies the course related to the responses.

GRADE – Final grade or performance level for the course.

✅ **Clean Aspects**:
No missing values in any column.

No duplicate rows.

Columns 1 to 30 contain only numeric values (as expected).

COURSE ID has 9 unique values (suggesting multiple courses).

GRADE has 8 unique values (ranging from 0 to 7).

🧰 **Tools & Libraries Used**

pandas for data manipulation

seaborn for data visualization

📊 **Key Insights**

Certain questions show high response correlation, indicating possible redundancy or related concepts.

Outlier analysis reveals inconsistencies or extreme feedback for some questions, potentially due to interpretation differences.

The dataset is imbalanced across courses and grades, making it crucial to consider fairness and sampling when modeling.

📁 **Files in This Repository**

Edu_dataset.ipynb – Main Jupyter notebook containing the full analysis

DATA.csv – Cleaned version of the student feedback dataset
