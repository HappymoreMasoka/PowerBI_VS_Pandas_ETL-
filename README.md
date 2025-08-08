
# 📊 Broadband Adoption ETL Project — Python & Power BI

This project showcases my ETL (Extract, Transform, Load) and data analysis skills using **Python (Pandas)** and **Power BI**, comparing how each tool contributes to a data pipeline and visualization workflow. The dataset explores the relationship between **Home Broadband Adoption** and **No Internet Access** across various regions.

---

## ⚙️ ETL Using Pandas (Python)

**Convenience & Strengths:**

✅ Full control of data manipulation  
✅ Easy to automate pipelines  
✅ Great for integrating with APIs or file-based data  
✅ Efficient for preprocessing large datasets  

**ETL Tasks Performed:**

- **Extract:** Loaded CSV files using `pandas.read_csv()`
- **Transform:** Cleaned missing values, calculated broadband ratios
- **Load:** Saved transformed data to CSV for Power BI or further processing

**Visualization:**  
used matplotlib

---

## 📈 ETL Using Power BI

**Convenience & Strengths:**

✅ Drag-and-drop ease of use  
✅ Interactive visuals and filters  
✅ Fast dashboard deployment  
✅ Built-in DAX for quick calculations  

**ETL Tasks Performed:**

- **Extract:** Imported CSV directly into Power BI
- **Transform:** Used **Power Query** for cleaning and formatting
- **Load:** Visualized directly within Power BI interface

**Visualization:**  
Created an interactive scatter plot:

---

## 🔍 Key Insights

- There is a **strong negative correlation** between **Home Broadband Adoption** and **No Internet Access**.
- Areas with high broadband penetration tend to have significantly fewer households without internet access.

---

## 🧠 Takeaways

| Tool        | Best For                                      | Limitation                     |
|-------------|-----------------------------------------------|--------------------------------|
| **Pandas**  | Automation, scripting, preprocessing large data | Lacks native visuals           |
| **Power BI**| Dashboards, quick visuals, stakeholder reporting| Limited custom transformation |

---

## 🛠️ Tech Stack

- `Python 3.10`
- `Pandas`, `Matplotlib`
- `Power BI Desktop`
- `Power Query`, `DAX`

---

## 📌 Future Work

- Integrate with APIs for real-time data
- Create a web-based dashboard using Streamlit or Dash
- Deploy automated ETL pipelines to the cloud (e.g., AWS Lambda + S3)
