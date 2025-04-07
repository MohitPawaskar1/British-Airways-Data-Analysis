# ✈️ British Airways Review Analysis  
**Project by:** *Mohit Pawaskar*  
**Organization:** @Forage | @British Airways (BA)  
**Dataset Source:** Skytrax Reviews  

---

## 📌 Overview

This repository contains analysis and insights derived from customer reviews of British Airways (BA), collected from the Skytrax website. The project was conducted in two main tasks provided by the @Forage virtual experience program.

---

## 🧹 TASK 1 – **Review Analysis & Insights**

### 🔹 01. Data Collection
- Scraped ~4000 reviews from the Skytrax website.
- Exported and structured the data into a CSV file:  
  **`british_airways_reviews_extended.csv`**

### 🔹 02. Data Cleaning
- Imported essential Python libraries.
- Read and explored the dataset (null values, data types, column names).
- Renamed `date` to `review_date` and converted all column names to lowercase.
- Dropped unnecessary columns for clarity.
- Cleaned the review text by removing:
  - “✅ Trip Verified”
  - “Not Verified”
- Implemented a function to clean ordinal suffixes like `1st`, `2nd`, `3rd`, etc.

### 🔹 03. Exploratory Data Analysis (EDA)
- Transformed categorical data into numerical form for better analysis.
- Visualized patterns and relationships between different variables.

### 🔹 04. Deliverable
- Submitted a presentation (**PPTX**) summarizing key findings and visualizations.

---

## 🧹 TASK 2 – **Customer Booking Prediction**

### 🔹 01. Data Preparation
- Collected and cleaned a new dataset (~5000 entries):  
  **`customer_booking.csv`**
- Standard data preprocessing:
  - Handled missing values.
  - Renamed `date` to `review_date`.
  - Converted all column names to lowercase.
  - Dropped irrelevant columns.

### 🔹 02. Model Building
- Implemented a **RandomForestClassifier** to predict customer booking behavior.
- Performed:
  - **Train/Test Split**
  - **Cross-Validation** with **ROC AUC**
  - Evaluation using **ROC_AUC_SCORE**
- Visualized results using **Matplotlib** and **Seaborn**.

### 🔹 03. Deliverable
- Submitted a presentation (**PPTX**) explaining the model workflow, evaluation, and insights.

---

## 🚀 Tools & Technologies
- **Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)**
- **Web Scraping** (BeautifulSoup/Selenium)
- **Machine Learning** (Random Forest)
- **EDA & Visualization**
- **PowerPoint** for stakeholder presentation