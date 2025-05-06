# ✈️ **British Airways Review Analysis**  
**Project by:** *Mohit Pawaskar*  
**Organization:** @Forage | @British Airways (BA)  
**Dataset Source:** Skytrax Reviews  

---

## 🎓 Certificate of Completion

![Certificate](D:\British Airways - Web Svrapping\Certificate.png)

---

## 📌 **Overview**

This project involves analyzing customer reviews of British Airways (BA) from the Skytrax website to derive insights into customer sentiment and predict booking behaviors. The project was conducted as part of the **Forage virtual internship** program in collaboration with **British Airways**.

### Tasks
- **Task 1:** Review Analysis & Insights  
- **Task 2:** Customer Booking Prediction

---

## 🧹 **TASK 1 – Review Analysis & Insights**

### 🔹 **01. Data Collection**
- Scraped approximately **4000 reviews** from the Skytrax website.
- Exported and structured the data into a CSV file:  
  **`british_airways_reviews_extended.csv`**

### 🔹 **02. Data Cleaning**
- Imported essential Python libraries.
- Performed data exploration (null values, data types, column names).
- Renamed `date` to `review_date` and standardized column names to lowercase.
- Dropped unnecessary columns to enhance data clarity.
- Cleaned the review text by removing:
  - “✅ Trip Verified”
  - “Not Verified”
- Created a function to clean ordinal suffixes like `1st`, `2nd`, `3rd`, etc.

### 🔹 **03. Exploratory Data Analysis (EDA)**
- Transformed categorical data into numerical form for better analysis.
- Visualized patterns and relationships between variables to uncover insights.

### 🔹 **04. Key Insights and Findings**
- Patterns in customer sentiments based on ratings and review length.
- Key features affecting customer satisfaction.
- Generated **visualizations**, including bar charts, histograms, and a **word cloud**.

---

## 🧹 **TASK 2 – Customer Booking Prediction**

### 🔹 **01. Data Preparation**
- Collected and cleaned a new dataset containing approximately **5000 entries**:  
  **`customer_booking.csv`**
- Standard preprocessing included:
  - Handling missing values.
  - Renaming `date` to `review_date`.
  - Dropping irrelevant columns.

### 🔹 **02. Model Building**
- Developed a **RandomForestClassifier** model to predict customer booking behavior.
- Process:
  - **Train/Test Split**
  - **Cross-Validation** with **ROC AUC**
  - Model Evaluation using **ROC_AUC_SCORE**
- Visualized the model performance using **Matplotlib** and **Seaborn**.

### 🔹 **03. Key Insights and Findings**
- Insights into features influencing booking decisions.
- Model accuracy and evaluation results were visualized to provide clarity on the model's performance.

---

## 🚀 **Tools & Technologies Used**
- **Programming Languages:** Python  
- **Libraries:**  
  - **Data Analysis & Preprocessing:** Pandas, NumPy  
  - **Visualization:** Matplotlib, Seaborn  
  - **Machine Learning:** Scikit-learn (RandomForestClassifier)  
- **Web Scraping:** BeautifulSoup, Selenium  
- **Others:** PowerPoint (for presentations)

---

## 📊 **Results & Deliverables**
- **PowerPoint Presentations (PPTX):**  
  - **Task 1:** Key findings and visualizations on the review analysis.
  - **Task 2:** Detailed explanation of the customer booking prediction model and insights.
  
- Both deliverables summarize the key findings, insights, and visualizations in a concise and professional format, ready for stakeholder presentations.

---

## 💡 **Conclusion**
This project provided valuable insights into customer sentiments and booking behaviors for British Airways, leveraging data analysis and machine learning techniques. The analysis was framed to help understand factors influencing customer satisfaction, and the predictive model aimed to improve booking decision-making for BA.

---

## 📄 **License**
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
