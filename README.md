# **Big Data Analysis of Air Quality Using PySpark**
A deep dive into the **3Vs of Big Data**—Volume, Variety, and Velocity—applied to air quality analysis. This project leverages **PySpark** to process, analyze, and classify air quality data, demonstrating how Big Data tools can drive actionable insights for environmental sustainability.

---

## **Project Overview**
Air pollution impacts over 99% of the global population, making it a critical issue for public health and sustainability. This project explores how advanced Big Data techniques can help analyze air quality patterns, predict pollution risks, and support decision-making for climate action. The methodology aligns with global sustainability goals, including those discussed at **COP29**, hosted in Azerbaijan.

---

## **Goals**
1. **Analyze air quality patterns** using Big Data tools.
2. **Understand the 3Vs of Big Data**—Volume, Variety, and Velocity.
3. **Build predictive machine learning models** to classify air quality.

---

## **Dataset**
- **Source**: [AirQualityUCI Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality)
- **Description**:
  - Contains hourly measurements of pollutants (e.g., CO, Benzene, NO2) and timestamps.
  - Includes numerical and textual data.
- **Challenges Addressed**:
  - Missing values and inconsistencies.
  - High-dimensional data transformation.

---

## **Technologies and Tools**
- **Apache Spark (PySpark)**: Distributed data processing and machine learning.
- **Python**: Data manipulation and preprocessing.
- **Jupyter Notebook**: Development environment.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - Decision Tree Classifier

---

## **Methodology**
### **1. Preprocessing Workflow**
- **Tokenization**: Breaking textual data into tokens.
- **Stopword Removal**: Eliminating irrelevant words.
- **Feature Extraction**:
  - **TF-IDF**: Weighted term importance.
  - **Bag-of-Words**: Frequency representation.
  - **N-Gram**: Sequential relationships.

### **2. Training and Evaluation**
- **Data Split**: 80-20 train-test split.
- **Metrics**:
  - Accuracy
  - F1 Score
  - Recall
  - Precision

---

## **Key Results**
- **Logistic Regression**: Best accuracy at **96.4%**.
- **Random Forest**: Balanced performance across metrics.
- **Decision Tree**: High interpretability with **95.4% accuracy**.

---

## **The 3Vs in Action**
- **Volume**: Processed thousands of rows efficiently.
- **Variety**: Integrated numerical and textual data.
- **Velocity**: Enabled near-real-time data processing.

---

## **Future Work**
1. **Integration with IoT systems** for real-time air quality monitoring.
2. **Development of interactive dashboards** for policymakers and stakeholders.

---

## **Relevance to COP29**
This project supports the goals of **COP29**, hosted in Azerbaijan, by showcasing how data-driven insights can contribute to global efforts to improve air quality and combat climate change. By leveraging Big Data tools, this work demonstrates scalable, actionable solutions for sustainability.

---

## **Contributers**
Azarin Bayali 
Nabat Gasimzade 
Ilyas Yagubov
Murad Ibrahimov
Ali Aliyev


