# clustering-validity-indices
A report on various clustering validity indices in machine learning, including internal and external evaluation metrics.

# 📊 HW03 – Clustering Validity Indices in Machine Learning

This repository contains a comprehensive report on various **clustering validity indices** used to evaluate the performance of unsupervised learning models.

📘 **Assignment Title:** Clustering Validity Index  
🧑‍🏫 **Instructor:** Dr. Zarinbal  
👨‍🎓 **Student:** Farzad Mohseni  
🏛️ **University:** Amirkabir University of Technology  
📅 **Term:** Spring 1404  

---

## 🧠 Assignment Prompt

> Regarding clustering validity indices, the following metrics can be used:  
> **Silhouette Score**, **Calinski-Harabasz Index**, **Davies-Bouldin Index**,  
> **Adjusted Rand Index**, **Normalized Mutual Information (NMI)**  
>  
> 🔍 *What are they, and when should we use them?*

---

## 📘 Report Overview

The report explains **5 popular clustering validity metrics**, covering:

- What each metric is
- How it’s calculated
- When and how to use it
- Its advantages and limitations
- Example formulas and interpretation range

📄 [Click here to view the full report (PDF)](https://github.com/farzadmohseni-ir/clustering-validity-indices/blob/main/clustering%20validity%20index.pdf)

---

## 📊 Summary Table

| Metric                         | Type      | Label Required | Best Value | Range       | Usage Note                              |
|-------------------------------|-----------|----------------|------------|-------------|------------------------------------------|
| **Silhouette Score**          | Internal  | ❌ No          | Higher     | -1 to +1    | Measures compactness & separation        |
| **Calinski-Harabasz Index**   | Internal  | ❌ No          | Higher     | 0 to ∞      | Ratio of inter- vs. intra-cluster spread |
| **Davies-Bouldin Index**      | Internal  | ❌ No          | Lower      | 0 to ∞      | Measures average similarity between clusters |
| **Adjusted Rand Index (ARI)** | External  | ✅ Yes         | Higher     | -1 to +1    | Compares predicted vs. true labels       |
| **Normalized Mutual Information (NMI)** | External | ✅ Yes | Higher | 0 to 1 | Measures shared info between labelings   |

---

## 📌 When to Use Each Metric?

- 🧪 **Silhouette / CH / DBI** → When there are **no labels** (unsupervised clustering)
- 🧾 **ARI / NMI** → When you have **ground truth labels** (e.g., for validation)

---

## 📈 Applications

- Evaluating clustering results from **K-Means**, **DBSCAN**, **Agglomerative**, etc.
- Choosing the **optimal number of clusters (k)**
- Comparing **different clustering models**
- Benchmarking clustering with and without **label supervision**

---

## 👤 Author

**Farzad Mohseni**  
M.Sc. Student in IT Engineering  
Amirkabir University of Technology – Tehran, Iran  
📧 farzadmohseni@aut.ac.ir  
🔗 [GitHub Profile](https://github.com/farzadmohseni-ir)

---

## ⭐️ Like this work?

If you found this report helpful, consider giving this repo a ⭐️ and sharing it with your peers!
