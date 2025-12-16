# Jumbo-Company-Forcast
# Device Insurance Attach Rate Analysis 📊

## 📌 Project Overview

This project analyzes **Device Insurance Attach Rates** across multiple retail stores and regions in India. The objective is to evaluate historical performance, categorize store efficiency, and provide a **January forecast** to support business decision-making.

The analysis helps identify:

* High-performing stores (**Excellent**)
* Stable but improvable stores (**Good**)
* Low-performing stores requiring intervention (**Needs Improvement**)

---

## 📂 Files in This Repository

* **Zopper Assignment.ipynb**
  Jupyter Notebook containing:

  * Data cleaning and preprocessing
  * Attach rate calculations
  * Store categorization logic
  * Summary insights and forecasts

* **Device_Insurance_Attach_Rate_Analysis.pptx**
  Business-ready PowerPoint presentation including:

  * Performance overview
  * Store category insights
  * Top-performing stores
  * Key takeaways and action plan

---

## 🧾 Dataset Description

Each row in the dataset represents a **store-level performance record**.

### Columns Explained

| Column Name     | Description                                                       |
| --------------- | ----------------------------------------------------------------- |
| Branch          | Region / cluster name                                             |
| Store_Name      | Store identifier                                                  |
| Aug – Dec       | Monthly attach rate percentages                                   |
| Avg_Attach_Rate | Average attach rate (Aug–Dec)                                     |
| Store_Category  | Performance classification (Excellent / Good / Needs Improvement) |
| Jan_Forecast    | Expected attach rate for January                                  |

---

## 🧠 Store Categorization Logic

* **Excellent**: Avg Attach Rate ≥ 40%
* **Good**: Avg Attach Rate between 20% – 39%
* **Needs Improvement**: Avg Attach Rate < 20%

This classification helps prioritize **training, incentives, and operational focus**.

---

## 📈 Key Insights

* Excellent stores show **consistent high attach behavior** and act as benchmarks
* A large number of stores fall under **Needs Improvement**, indicating training gaps
* January forecasts highlight **growth opportunities in Delhi NCR, Pune, and Mumbai**

---

## 🎯 Business Use Cases

* Sales performance monitoring
* Regional comparison and benchmarking
* Store-level corrective action planning
* Leadership and client presentations

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – data manipulation
* **Jupyter Notebook** – analysis and documentation
* **Microsoft PowerPoint** – stakeholder presentation

---

## 🚀 How to Run the Notebook

```bash
pip install pandas jupyter
jupyter notebook
```

Open `Zopper Assignment.ipynb` and run cells sequentially.

---

## 📌 Future Enhancements

* Region-wise performance dashboards
* Trend analysis with visual charts
* Automated forecast model
* KPI alerts for low-performing stores

---

## 👤 Author

**Nikhil Yadav**
Aspiring Data Analyst | Business & Performance Analytics

--- 
