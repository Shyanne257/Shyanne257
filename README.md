# 👋 Hi, I'm Chenyu Zuo

🎓 M.S. Applied Data Science @ **University of Southern California** (expected May 2027)  
📊 Data scientist / analyst focused on **A/B testing, causal inference, and large-scale data pipelines**  
📍 Los Angeles, CA

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chenyu-zuo-025017355/)
[![Email](https://img.shields.io/badge/Email-chenyuzu%40usc.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:chenyuzu@usc.edu)

---

## 🎓 Education

**University of Southern California** — M.S. Applied Data Science | Los Angeles, CA | *Expected May 2027*  
Coursework: Foundations of Data Management, Machine Learning for Data Science, Web Technologies, Foundations and Applications of Data Mining, Data Visualization

**China University of Geosciences (Beijing)** — B.S. Geographic Information Science | Beijing, China | *Sep 2021 – Jun 2025*  
Coursework: Fundamentals of Programming, Data Structures, Principles of Spatial Database, Web GIS, Digital Image Processing

## 📚 Featured Projects

### 📈 Ad Incrementality A/B Test & Uplift Modeling
**PySpark · Python · LightGBM · Causal Inference** | Sep 2026

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat&logo=github)](https://github.com/Shyanne257/criteo-uplift-ab-test)
[![Dashboard](https://img.shields.io/badge/Live-Dashboard-2a78d6?style=flat)](https://shyanne257.github.io/criteo-uplift-ab-test/)

Does ad exposure actually drive extra visits and conversions, which users respond, and who should we target? An end-to-end analysis of Criteo's randomized ad experiment with **14M users**.

- Built a **PySpark** pipeline to ingest, validate, and analyze the experiment, including sample ratio mismatch and covariate balance (SMD) checks
- Measured a **59.4% conversion lift** (95% CI: 54.4–64.7%) with two-proportion z-tests and bootstrap CIs; separated intent-to-treat from complier effects (**CACE**), showing naive exposed-vs-control comparisons overstate impact by 62%
- Ran power / MDE analysis and verified it empirically on 100 disjoint traffic buckets: 1% of traffic would still detect the conversion lift with 85% power
- Trained a **T-learner uplift model** (LightGBM): targeting the top 30% of users captures **78% of incremental conversions** (95% CI: 71–87%)

[![Dashboard preview](https://raw.githubusercontent.com/Shyanne257/criteo-uplift-ab-test/main/reports/figures/dashboard.png)](https://shyanne257.github.io/criteo-uplift-ab-test/)

---

### 🚕 NYC Taxi Trip Analytics Dashboard
**DuckDB · SQL · Streamlit** | Course Project, USC | Jan – Apr 2026

[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat&logo=github)](https://github.com/Shyanne257/nyc-taxi-duckdb)
[![App](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat&logo=streamlit&logoColor=white)](https://nyc-taxi-duckdb.streamlit.app)

- Modeled **6.7M** NYC Yellow Taxi trips as a star schema (6.7M-row fact table, 265-row zone dimension) and wrote 8 analytical SQL queries covering aggregation, filtering, Top-K ranking, and joins
- Built an interactive Streamlit dashboard that pairs each analytical question with its results, query plan (EXPLAIN / EXPLAIN ANALYZE), and a performance insight
- Achieved **sub-50ms** query latency on 6.7M rows; cut scanned data by ~90% via column projection and reduced join probe-side rows 5× via predicate pushdown

---

## 🏢 Experience

### Research Algorithm Engineer Intern · iFLYTEK Co., Ltd.
*Core R&D Platform Department | Hefei, China | Jul – Aug 2023*

- Evaluated YOLOv8 object detection models on autonomous-driving datasets with **100K+** labeled objects, tracking training dynamics with TensorBoard and automated metric scripts
- Built analysis tools in Python and SQL to compute Precision, Recall, mAP, and F1, reducing evaluation turnaround time by **30%**
- Ran systematic error analysis on edge-case failures (low light, motion blur, occlusion) and visualized detection results to help the team locate issues quickly
- Tested improvement hypotheses with the algorithm team (learning-rate scheduling, batch size, multi-scale training, Mosaic/CutMix augmentation), contributing to **7–12%** accuracy gains across day and night scenarios

---

## 🔧 Skills

**Languages & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Big Data & Databases**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Data Science & ML**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Methods**
- **Experimentation & statistics:** A/B testing, hypothesis testing, power analysis / MDE, bootstrap, regression
- **Causal inference:** ITT vs. CACE (instrumental variables), uplift modeling (T-learner), Qini evaluation
- **Machine learning:** random forest, gradient boosting (LightGBM), deep learning (YOLOv8), model evaluation (Precision, Recall, F1, mAP)
- **Data & analytics:** ETL and data cleaning, data modeling (star schema), metric design, data visualization, dashboarding

---

🧗 Outside of data: rock climbing and photography.
