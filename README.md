
## 🎯 Introduction

### **Purpose**
This project aims to evaluate student academic performance at Ascend Academy using detailed datasets that track academic metrics, behavioral factors, and socio-economic indicators.

### **Objective of the Project**
To uncover patterns, correlations, and influential factors affecting student outcomes, such as total score and final grade, using Excel-based analytical methods like pivot tables and performance tracking.

### **Problem Being Addressed**
Ascend Academy wants to understand what drives academic success among its students and identify areas for educational improvement.

### **Key Datasets and Methodologies**
- **Dataset Includes:** Student demographics, academic scores, attendance, extracurricular involvement, sleep/study hours, and family background.
- **Tools Used:** Microsoft Excel (Pivot Tables, Conditional Formatting, Filtering, and Aggregation).

## 📘 Story of the Data

### **Data Source**
Dataset was gotten from Kaggle, a well known website.

### **Data Collection Process**
Compiled via institutional records, digital surveys, and administrative logs.

### **Data Structure**
- **Rows:** Individual student records.
- **Columns:** Variables like `Gender`, `Department`, `Attendance (%)`, `Total_Score`, `Grade`, `Parent Education`, etc.

### **Important Features**
- `Total_Score` & `Grade`: Primary indicators of academic performance.
- `Study_Hours_per_Week`, `Sleep_Hours_per_Night`: Behavioral indicators.
- `Parent_Education_Level`, `Family_Income_Level`: Socio-economic context.

### **Data Limitations**
- Missing values in socio-economic indicators.
- Slight imbalances in department distributions.

## 🔧 Data Splitting and Preprocessing

### **Data Cleaning**
- Removed duplicates, corrected typos, standardized column formats.

### **Handling Missing Values**
- Used median replacement for numeric values.
- Filled categorical blanks with “Unknown” or most frequent label.

### **Transformations**
- Created total scores by aggregating components like assignments, quizzes, and participation.

### **Independent vs Dependent Variables**
- **Independent:** Gender, Department, Attendance, Study Hours, etc.
- **Dependent:** Total Score, Grade.

### **Industry Context**
Education & Academic Evaluation.

### **Stakeholders**
School management, academic coordinators, curriculum developers.

### **Value to the Industry**
Supports targeted academic interventions and data-driven policy decisions.

## 🧪 Pre-Analysis

### **Key Trends**
- Male students had a slightly higher aggregate total score.
- Mathematics students led average performance across departments.

### **Potential Correlations**
- Higher parental education doesn’t strongly correlate with better scores.
- Study hours showed clearer influence than sleep hours.

### **Initial Insights**
- Students with more than 20 study hours/week consistently outperformed.
- Final scores are highest among those with 9+ hours of weekly study.

## 🔍 In-Analysis

### **Unconfirmed Insights**
- Students from the Mathematics department performed better overall.
- High family income did not drastically improve academic scores.

### **Recommendations**
- Encourage effective study practices over focusing on socioeconomic status.
- Consider departmental curriculum reviews to level performance gaps.

### **Excel Tools Used**
Pivot Tables, Pivot Charts.

## ✅ Post-Analysis and Insights

### **Key Findings**
- Gender difference in performance is minimal but present.
- Higher study hours relate directly to better academic scores.
- Sleep hours showed minimal performance impact.

### **Comparison with Initial Expectations**
- Contrary to assumptions, parental education had limited effect.
- Department performance variance was more noticeable than expected.

## 💡 Recommendations and Observations

### **Actionable Insights**
- Promote academic mentoring in underperforming departments.
- Increase focus on personal study plans.
- Monitor participation scores as strong performance indicators.

### **Optimizations**
- Introduce a balanced schedule prioritizing both academics and extracurriculars.
- Provide tools/resources for independent study.

### **Unexpected Outcomes**
- Sleep hours didn’t significantly impact performance, contradicting expectations.

## 🏁 Conclusion

### **Key Learnings**
- Behavioral factors like study hours influence student performance more than socio-economic ones.
- Data-backed strategies can be implemented to personalize academic interventions.

### **Limitations**
- Simulated dataset may not fully capture real-world nuances.
- Some fields like extracurriculars were binary and lacked granularity.

### **Future Research**
- Explore impact of teacher feedback and classroom engagement.
- Introduce time series analysis for longitudinal insights.

## 📚 References & Appendices

### **References**
- kaggle.
- Microsoft Excel documentation and best practices.

### **Appendices**
- Full pivot tables.
- Raw data snapshots.
- Excel formulas used.

![Updated Dashboard 8](https://github.com/user-attachments/assets/fd50ae88-9794-4a5d-8306-2db44f404811)
