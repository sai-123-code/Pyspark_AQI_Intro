 # 🚀 Air Quality Analysis with PySpark vs Pandas
This project analyzes city-wise air pollution levels using real-world data from six global cities. It demonstrates the differences in performance and execution style between Pandas and the optimized PySpark DataFrame by calculating simple aggregations like Q1,Q2,Q3,Q4 for each pollutants

The goal is to understand how PySpark handles larger datasets compared to regular Pandas — especially in terms of scalability, syntax, and speed.

# 🧪 Tools Compared
🐼 Pandas – Fast and intuitive for smaller datasets
⚡ PySpark DataFrame API – Highly optimized for distributed computation

# ⏱ Performance Comparison
| 🧮 Method           | ⏳ Time Taken    | ✅ Result     |
|--------------------|------------------|---------------|
| ⚡ Spark DataFrame  | 0.0643 seconds   | Fastest ✅     |
| 🐼 Pandas           | 0.1112 seconds   | Still Fast ✅  |


# ✅ Conclusion
The PySpark DataFrame API was approximately 1.7× faster than Pandas in this analysis, showcasing its advantage for scalable, high-performance data processing even on medium-sized datasets.
