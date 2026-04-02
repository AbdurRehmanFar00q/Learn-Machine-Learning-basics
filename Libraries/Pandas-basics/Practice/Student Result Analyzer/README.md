# 🎓 Student Result Analyzer (Pandas)

This project analyzes student academic performance using **Pandas**.

It reads student data from a CSV file, calculates average marks, identifies the topper, assigns pass/fail status, and saves the updated data.

---

## 📌 Features

- 📥 Read student data from CSV file  
- 📊 Calculate average marks for each student  
- 🏆 Identify the topper  
- ✅ Assign Pass/Fail status  
- 💾 Save updated data back to CSV  

---

## 📂 Dataset

The dataset (`studentdata.csv`) contains:

| Column | Description |
|--------|------------|
| Name | Student name |
| Math | Math marks |
| Physics | Physics marks |
| Chemistry | Chemistry marks |

---

## ⚙️ How It Works

### 1️⃣ Load Data
```python
data = pd.read_csv("studentdata.csv")