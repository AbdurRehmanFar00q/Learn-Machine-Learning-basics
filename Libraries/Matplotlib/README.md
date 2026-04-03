# 📊 Matplotlib Basics

This repository contains my learning and practice of **Matplotlib**, a powerful Python library used for data visualization.

It covers different types of graphs and how to customize them using colors, styles, and other important functions.

---

## 📌 Topics Covered

### 1️⃣ Line Plot
- Basic line graph
- Styling (color, linestyle, markers)

### 2️⃣ Bar Chart
- Category-based visualization
- Custom colors and borders

### 3️⃣ Scatter Plot
- Relationship between variables
- Used in Machine Learning

### 4️⃣ Histogram
- Data distribution visualization
- Bins and frequency

### 5️⃣ Pie Chart
- Percentage distribution
- Labels and formatting

---

## 🎨 Styling & Customization

The following features are used across graphs:

- Colors (`color`)
- Line styles (`linestyle`)
- Markers (`marker`)
- Transparency (`alpha`)
- Figure size (`figsize`)
- Grid (`plt.grid()`)
- Legends (`plt.legend()`)

---

## 💻 Example Code

```python
import matplotlib.pyplot as plt

x = [1,2,3,4]
y = [10,20,25,30]

plt.plot(x, y, color="blue", linestyle="--", marker="o")

plt.title("Line Plot")
plt.xlabel("X Axis")
plt.ylabel("Y Axis")

plt.grid(True)
plt.show()