# AI & ML Internship - Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Objective
The goal of this project is to perform a comprehensive Exploratory Data Analysis (EDA) on the standard Titanic dataset using Python. This workflow cleans the data, summarizes descriptive statistics, visualizes distributions, identifies outlier anomalies, and explores correlations to isolate impactful features for downstream Machine Learning models.

---

## 🛠 Tools & Libraries Used
* **Pandas:** Data loading, structure checking, cleaning, and descriptive statistical summary.
* **NumPy:** Mathematical calculations and array manipulations.
* **Matplotlib:** Core plotting foundation and multi-plot layout structuring.
* **Seaborn:** High-level statistical visualization (Histograms, Boxplots, Heatmaps).

---

## 📈 Key Insights & Patterns Discovered
1. **Age Distribution:** The passenger age distribution peaks between 20 and 40 years old, exhibiting a slight right-skewed tail with fewer elderly passengers.
2. **Outlier Detection:** The ticket `fare` feature shows extreme high-value outliers, representing luxury premium-class tickets compared to the highly dense lower-class fare baselines.
3. **Gender vs. Survival Rate:** A distinct survival bias was observed where female passengers across all socio-economic classes yielded significantly higher survival rates compared to male passengers.
4. **Socio-Economic Impact:** Passengers staying in 1st class (`pclass = 1`) showed a significantly better chance of survival compared to those in 3rd class.

---

## 🚀 How to Run the Notebook
1. Open [Google Colab](https://google.com).
2. Click **File -> Upload Notebook** and select the `.ipynb` file from this repository.
3. Run the code blocks sequentially from top to bottom.
