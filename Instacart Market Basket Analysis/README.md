# 🛒 Instacart Market Basket Analysis  

*A data-driven exploration of customer purchase patterns to identify customer types.*  

## 📌 Project Overview  
This repository contains a series of Jupyter Notebooks analyzing Instacart's anonymized dataset of **3+ million grocery orders** from **200,000+ users**. The goal is to predict which products a customer will buy next, based on their historical order sequences.  

---

## 📂 Notebooks  

### 1. **Data Exploration**  
   - **Objective**: Uncover patterns in raw transactional data.  
   - **Key Actions**:  
     - Analyzed order frequency, product popularity, and time-based trends.  
     - Visualized customer behavior distributions (e.g., "Do most users order new or repeat products?").  

### 2. **Customer Segmentation**  
   - **Techniques**: PCA + K-Means Clustering.  
   - **Insights**:  
     - Reduced dimensionality using PCA to identify latent purchase behaviors.  
     - Grouped customers into clusters. 

---

## 🛠️ Tools Used  
```python
pandas | numpy | matplotlib/seaborn | scikit-learn | Google colab
```