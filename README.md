# 📱 Springboard Apps Project  
**Case Study: Integrating Apps**  
**Springboard Data Science Career Track**

---

## 📊 Project Overview

In this case study, we analyze whether there is a significant difference in app ratings between the **Apple Store** and **Google Play Store**.

The goal is to determine whether platform choice impacts app quality (measured by ratings), which would guide the decision to integrate either store into a custom operating system.

---

## ⚙️ Data Sources

- `AppleStore.csv`
- `appleStore_description.csv`
- `googleplaystore.csv`
- `googleplaystore_user_reviews.csv`

Original source:  
[https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps)

---

## 📚 Techniques Used

- Data Cleaning
- Handling missing data and outliers
- Exploratory Data Analysis (EDA)
- GroupBy analysis
- Boxplots & Visualizations
- Normality Testing (`stats.normaltest()`)
- Permutation Testing (10,000 iterations)
- P-value calculation
- Hypothesis testing
- Final conclusion

---

## 🚀 Results & Conclusion

The observed difference in mean ratings between platforms was statistically significant.

**Permutation test result: p-value = 0.0**  
→ Strong evidence that **platform does impact app ratings**.  
→ The Null Hypothesis was rejected.

---

## 💻 Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scipy
- matplotlib

---

## 🎓 Acknowledgments

This project was completed as part of the **Springboard Data Science Career Track**.
