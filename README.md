# 📊 Sales Optimization & Customer Segmentation

### Apex Planet Internship – Task 4

---

## 🚀 Project Overview

This project focuses on **Data Storytelling and Statistical Validation**, where raw sales data is transformed into meaningful business insights. The goal is to analyze customer behavior, identify revenue opportunities, and validate findings using statistical methods.

---

## 🎯 Objective

* Analyze sales data to identify growth opportunities
* Build a **compelling business narrative**
* Apply **statistical hypothesis testing** to validate insights
* Provide **data-driven recommendations** for decision-making

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** (Data Cleaning & Processing)
* **SciPy** (Statistical Testing)
* **Power BI / PPT** (Visualization & Storytelling)

---

## 📂 Dataset

* Cleaned dataset containing **sales transactions**
* Total Records: **2673 orders**
* Features include:

  * Segment (Consumer / Corporate)
  * Sales
  * Customer data

---

## 📊 Data Analysis & Storytelling

### Key Insights:

* 📍 **West Region** generates highest revenue
* 💻 **Technology Category** has highest profit margins
* 📈 **Q1 (Jan–Mar)** shows strong sales spike
* 👥 Customer segmentation using **RFM Analysis**

---

## 🧠 Hypothesis Testing

### 📌 Business Question

Is there a significant difference in spending between **Consumer** and **Corporate** segments?

---

### 📐 Hypotheses

* **Null Hypothesis (H₀):** No difference in average sales between segments
* **Alternative Hypothesis (H₁):** Significant difference exists

---

### 🧪 Statistical Test

* **Test Used:** Independent T-Test
* **Library:** SciPy

---

### 💻 Python Code

```python
import pandas as pd
from scipy import stats

df = pd.read_csv("Cleaned_DataSet.csv")

consumer_sales = df[df['segment'] == 'Consumer']['sales']
corporate_sales = df[df['segment'] == 'Corporate']['sales']

t_stat, p_value = stats.ttest_ind(consumer_sales, corporate_sales)

print(f"T-Statistic: {t_stat:.4f}")
print(f"P-Value: {p_value:.4f}")
```

---

### 📈 Results

* **T-Statistic:** -1.6033
* **P-Value:** 0.1090

---

### ✅ Conclusion

Since **p-value > 0.05**, we:
➡️ **Fail to Reject the Null Hypothesis**

### 💡 Business Insight

There is **no statistically significant difference** in spending behavior between Consumer and Corporate customers.

---

## 📢 Recommendations

* ✅ Use a **Unified Marketing Strategy**
* 🎯 Focus on **high-performing regions (West)**
* 🔄 Launch **Win-Back Campaigns** for inactive customers
* 🏆 Introduce **Loyalty Programs** for top customers

---

## 📽️ Deliverables

* 📊 **Presentation Deck** (PPT)
* 🧪 **Hypothesis Testing Code (Python)**
* 🎥 **LinkedIn Video Presentation (7–10 mins)**

---

## 🔗 Project Links

* 📁 GitHub Repository: https://github.com/VishnuVardhanParnandi/ApexPlanet-Task-4.git
* 🎥 LinkedIn Video: # 📊 Sales Optimization & Customer Segmentation

### Apex Planet Internship – Task 4

---

## 🚀 Project Overview

This project focuses on **Data Storytelling and Statistical Validation**, where raw sales data is transformed into meaningful business insights. The goal is to analyze customer behavior, identify revenue opportunities, and validate findings using statistical methods.

---

## 🎯 Objective

* Analyze sales data to identify growth opportunities
* Build a **compelling business narrative**
* Apply **statistical hypothesis testing** to validate insights
* Provide **data-driven recommendations** for decision-making

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** (Data Cleaning & Processing)
* **SciPy** (Statistical Testing)
* **Power BI / PPT** (Visualization & Storytelling)

---

## 📂 Dataset

* Cleaned dataset containing **sales transactions**
* Total Records: **2673 orders**
* Features include:

  * Segment (Consumer / Corporate)
  * Sales
  * Customer data

---

## 📊 Data Analysis & Storytelling

### Key Insights:

* 📍 **West Region** generates highest revenue
* 💻 **Technology Category** has highest profit margins
* 📈 **Q1 (Jan–Mar)** shows strong sales spike
* 👥 Customer segmentation using **RFM Analysis**

---

## 🧠 Hypothesis Testing

### 📌 Business Question

Is there a significant difference in spending between **Consumer** and **Corporate** segments?

---

### 📐 Hypotheses

* **Null Hypothesis (H₀):** No difference in average sales between segments
* **Alternative Hypothesis (H₁):** Significant difference exists

---

### 🧪 Statistical Test

* **Test Used:** Independent T-Test
* **Library:** SciPy

---

### 💻 Python Code

```python
import pandas as pd
from scipy import stats

df = pd.read_csv("Cleaned_DataSet.csv")

consumer_sales = df[df['segment'] == 'Consumer']['sales']
corporate_sales = df[df['segment'] == 'Corporate']['sales']

t_stat, p_value = stats.ttest_ind(consumer_sales, corporate_sales)

print(f"T-Statistic: {t_stat:.4f}")
print(f"P-Value: {p_value:.4f}")
```

---

### 📈 Results

* **T-Statistic:** -1.6033
* **P-Value:** 0.1090

---

### ✅ Conclusion

Since **p-value > 0.05**, we:
➡️ **Fail to Reject the Null Hypothesis**

### 💡 Business Insight

There is **no statistically significant difference** in spending behavior between Consumer and Corporate customers.

---

## 📢 Recommendations

* ✅ Use a **Unified Marketing Strategy**
* 🎯 Focus on **high-performing regions (West)**
* 🔄 Launch **Win-Back Campaigns** for inactive customers
* 🏆 Introduce **Loyalty Programs** for top customers

---

## 📽️ Deliverables

* 📊 **Presentation Deck** (PPT)
* 🧪 **Hypothesis Testing Code (Python)**
* 🎥 **LinkedIn Video Presentation (7–10 mins)**

---

## 🔗 Project Links

* 📁 GitHub Repository: https://github.com/VishnuVardhanParnandi/ApexPlanet-Task-4.git
* 🎥 LinkedIn Video: *(Add your video link here)*

---

## 🏁 Conclusion

This project demonstrates how **data analytics + statistical validation** can help businesses make informed decisions, optimize strategies, and improve customer engagement.

---

## 🙌 Acknowledgement

Thanks to **Apex Planet** for providing this opportunity to work on real-world data analytics tasks.

---

## 📬 Connect with Me

* 🔗 LinkedIn: linkedin.com/in/vishnuvardhan-parnandi-32bba7329
* 💻 GitHub: https://github.com/VishnuVardhanParnandi/

---



---

## 🏁 Conclusion

This project demonstrates how **data analytics + statistical validation** can help businesses make informed decisions, optimize strategies, and improve customer engagement.

---

## 🙌 Acknowledgement

Thanks to **Apex Planet** for providing this opportunity to work on real-world data analytics tasks.

---

## 📬 Connect with Me

* 🔗 LinkedIn: linkedin.com/in/vishnuvardhan-parnandi-32bba7329
* 💻 GitHub: https://github.com/VishnuVardhanParnandi/

---

