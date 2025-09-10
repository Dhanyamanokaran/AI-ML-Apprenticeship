# AI-ML Apprenticeship 🚀

print("Hello AI World! My apprenticeship begins.")

---

### **Day 1 — Setup**
- Installed Python & Jupyter Notebook.
- Setup Git & GitHub for version control.
- Created first Jupyter notebook and successfully committed to GitHub.

---

### **Day 2 — Python & NumPy Basics**

**Python Dictionary**  
- Created and accessed values.

**Python Function**  
- Defined `square_numbers(numbers)` to return squares of numbers.

**NumPy Basics**  
- Sliced arrays (first 6 and last 5 elements).  
- Calculated **sum, mean, std, and row sums**.  
- Performed **element-wise addition** and **dot product**.  

✅ Committed & pushed notebook to GitHub.

---

### **Day 3 — Pandas & Data Handling**

- Created **DataFrame from a dictionary**.  
- Selected columns and filtered rows:  
  - `df["Name"]`  
  - Rows where `StudyHours > 5`  
  - First 3 rows  

- Calculated basic statistics:  
  - `.mean()`, `.max()`, `.sum()`  

- Added new column **TotalHours**.  
- Updated column values using `.loc`.  
- Saved DataFrame to CSV and read it back.  

📌 Notebook to push: `day3_pandas_basics.ipynb`

---

### **Day 4 — Pandas Dataset Practice**

- Worked with a **custom dataset** using Pandas.  
- Added new column `"Result"`:  
  - `"Pass"` if `Marks >= 50`  
  - `"Fail"` otherwise  

- Practiced:  
  - Filtering rows  
  - Grouping data  
  - Saving DataFrame back to CSV  

📌 Notebook: `day4_pandas_dataset.ipynb`

---

### **Day 5 — Advanced Pandas: Merging & Aggregations**

- **Merged multiple DataFrames** using:
  - `pd.merge(students, marks, on="student_id", how="inner")`
  - Learned about `inner`, `left`, `right`, and `outer` joins.
- Performed **aggregations**:
  - `.sum()`, `.mean()`, `.groupby()`
- Worked with **CSV input/output**:
  - Saved final merged DataFrame as `day5_final_students.csv`
- Practiced **filtering, sorting, and updating DataFrames**.

📌 Notebook: `day5_advanced_pandas.ipynb`  
📌 CSV: `day5_final_students.csv`


---


### **Day 6 — Data Visualization (Matplotlib & Seaborn)**

**Dataset:** Created a student dataset with columns → `Name`, `StudyHours`, `Marks`.

---

#### 🔹 Matplotlib
- **Line Plot** → StudyHours vs Marks  
- **Bar Chart** → Student Names vs Marks  
- **Histogram** → Marks distribution  

---

#### 🔹 Seaborn
- **Barplot** → Student Names vs Marks  
- **Histplot** → Marks distribution with KDE  
- **Scatterplot** → StudyHours vs Marks  

---

📌 Notebook: `day6_data_visualization.ipynb`  
✅ Learned how to create basic plots with Matplotlib and Seaborn.  




