# 🔍 Big Data Analysis of Machine Learning Jobs using PySpark

This project demonstrates big data processing and analysis using **PySpark** on a dataset of 1000 machine learning jobs in the United States.

---

## 📁 Dataset

- **Name**: `1000_ml_jobs_us.csv`
- **Description**: A dataset containing job listings related to machine learning roles in the US, including information such as job title, company name, location, salary estimate, and more.

---

## 🧰 Tools & Technologies

- [PySpark](https://spark.apache.org/docs/latest/api/python/)
- [Google Colab](https://colab.research.google.com/)
- Apache Spark 3.3.2
- OpenJDK 8
- Python 3

---

## 🚀 Features & Analysis Performed

- ✅ Load large CSV dataset using Spark DataFrame
- ✅ Inspect schema and preview rows
- ✅ Clean and transform columns (e.g., salary fields)
- ✅ Perform big data operations like grouping, aggregation, and filtering
- ✅ Extract meaningful insights

---

## 📊 Insights Extracted

- **Top 10 Job Titles** in demand
- **Top 10 Hiring Companies**
- **Average Salary Estimates** from parsed salary ranges (if available)
- **Top 5 US States** hiring ML professionals (based on location parsing)
- **Job counts by Company and Job Title**

---
## 🔮 Future Scope

- **Cloud Deployment**: This project can be extended to run on cloud-based distributed systems such as AWS EMR, Google Cloud Dataproc, or Azure HDInsight for handling even larger datasets.
- **Real-Time Data Processing**: Integrate Spark Structured Streaming to analyze job listings in real-time from APIs or job portals.
- **Natural Language Processing (NLP)**: Apply NLP techniques on job descriptions to extract technologies, skills, and responsibilities.
- **Machine Learning Integration**: Utilize Spark MLlib for salary prediction, job recommendation systems, or company clustering based on job roles.
- **Interactive Dashboards**: Use tools like Tableau, Power BI, or Streamlit to visualize the data and insights for better decision-making.

---

## ✅ Conclusion

This project showcases the capability of PySpark in processing and analyzing large-scale datasets efficiently. By examining job listings for machine learning roles in the US, we extracted valuable insights such as top job titles, hiring companies, and geographic trends. The project demonstrates that PySpark is a powerful tool for big data analytics and can be scaled further for real-time analysis, machine learning, and advanced business intelligence applications.
