# 🔢 NumPy Basics

This folder contains my learning and practice of **NumPy**, the fundamental library for numerical computing in Python.

It covers core concepts required for **Machine Learning**, including array creation, indexing, slicing, stacking, and broadcasting.

---

## 📌 Topics Covered

### 1️⃣ Importing NumPy
```python
import numpy as np
```

---

### 2️⃣ Array Creation

#### 🔹 1D Array
```python
np.array([1,2,3,4,5])
```

#### 🔹 2D Array
```python
np.array([[0,1,2,3,4], [5,6,7,8,9]])
```

#### 🔹 3D Array
```python
np.array([
    [[1,2,3],[4,5,6]],
    [[7,8,9],[10,11,12]]
])
```

---

### 3️⃣ Indexing & Slicing

#### 🔹 Indexing
```python
array1[3]
```

#### 🔹 Slicing
```python
array1[0:3]
```

#### 🔹 Negative Indexing
```python
array1[-3]
```

---

### 4️⃣ 3D Array Indexing

```python
array[depth, row, column]
```

Examples:
```python
array3[0,0,1]
array3[1]
array3[:,:,1]
```

---

### 5️⃣ Stacking Arrays

```python
np.vstack((a,b))
np.hstack((a,b))
np.stack((a,b))
np.dstack((a,b))
```

---

### 6️⃣ Broadcasting

```python
arr + 5
2D_array + 1D_array
column_array + row_array
```

---

## 🎯 Learning Outcome

- Create and manipulate NumPy arrays  
- Perform indexing and slicing  
- Work with multi-dimensional arrays  
- Combine arrays using stacking  
- Apply broadcasting  

---

## ▶️ How to Run

```bash
python arrays.py
```

---

## 🚀 Next Step

- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 💡 Author
Abdur Rehman Farooq  
Artificial Intelligence Student   🚀  
Building Machine Learning projects and learning step-by-step
GitHub: https://github.com/AbdurRehmanFar00q
