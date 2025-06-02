 Elevatelabs-Data-Analyst-Intern-Task1

 📌 Task 1 – Data Cleaning & Preprocessing

📝 Task Description
This task is part of a Data Analyst Internship program and focuses on preparing a raw dataset for analysis. Using Python and Pandas, I performed essential data cleaning steps to convert an unstructured CSV into a clean and analysis-ready format.

---

 📊 Dataset Overview
- *Dataset*: Sales Data Sample  
- *Source*: [Kaggle – Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)  
- *File Name*: sales_data_sample_set.csv  
- *Context*: This dataset includes information about product orders such as customer names, order dates, quantities, and sales values.

---

 🧪 Cleaning Process Summary

 🔍 Step-by-step Actions:
- *Explored the dataset* for structure and null values
- *Dropped empty rows* and handled missing data using forward fill (fillna(method='ffill'))
- *Removed duplicate records* to avoid redundancy
- *Renamed column headers* to be lowercase and underscore-separated for consistency
- *Converted orderDate column* to datetime format using pd.to_datetime()
- *Cast quantityOrdered* column to integer
- *Saved* the cleaned data into a new CSV file

---

 🧰 Tools & Technologies
- Python (v3.x)
- Jupyter Notebook
- Pandas Library

---

🗂 Output Files
- cleaned_sales_data_set.csv – Cleaned version of the original dataset
- Task_1_Data_Cleaning.ipynb – Jupyter notebook with code and step-by-step cleaning process

---

 📈 Why This Matters
Cleaning data is the first and most critical step in any data science or analytics workflow. Clean data ensures accurate insights, reduces errors, and improves model performance. This task helped reinforce those skills with a real-world dataset.

---

👨‍💻 Author
*Sowmya Katuri*  
Data Analyst Intern – Task 1 Submission
