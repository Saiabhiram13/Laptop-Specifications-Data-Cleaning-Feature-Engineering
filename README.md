# 💻 Laptop Dataset Cleaning & Feature Engineering

## 📌 Project Overview
This project focuses on cleaning and preprocessing a laptop specifications dataset. The dataset contained inconsistent formatting, mixed data types, and categorical variations that required transformation before analysis.

The goal was to convert raw textual attributes into structured, machine-readable features suitable for analysis and modeling.

---

## 📂 Dataset Description
The dataset includes features such as:
- Screen Resolution
- RAM
- Weight
- Memory
- Operating System
- Processor Details
- Price

---

## 🧹 Data Cleaning & Feature Engineering Steps

### 1️⃣ Screen Resolution
- Extracted numeric resolution from values like:
- - Created two new columns:
- `X_res` (2560)
- `Y_res` (1600)

---

### 2️⃣ RAM Cleaning
- Converted values like `8GB` → `8`
- Removed `"GB"` and converted column to integer

---

### 3️⃣ Weight Cleaning
- Converted values like `1.5kg` → `1.5`
- Removed `"kg"` and converted to float

---

### 4️⃣ Memory Column Processing
Example:

- Extracted numeric storage value
- Created separate columns:
  - `Memory_Size`
  - `Storage_Type` (SSD / HDD / Flash Storage)
- Removed `"GB"` and standardized memory format

---

### 5️⃣ Operating System Standardization
Original values:
- Windows 7
- Windows 8
- Windows 10
- Windows 11
- macOS
- No OS

Standardized into:
- Windows
- macOS
- No OS

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

---

## 🚀 Key Outcome
The final cleaned dataset:
- Contains properly formatted numerical features
- Has standardized categorical variables
- Is ready for exploratory analysis or machine learning

---

## 👤 Author
Abhiram Konapala

