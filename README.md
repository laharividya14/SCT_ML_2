# 🏬 Mall Customer Segmentation (K-Means Clustering)

## 📌 Project Overview
This project applies **K-Means clustering** to segment customers of a retail store based on their **Annual Income** and **Spending Score**.  
The goal is to group customers into clusters that reveal spending patterns, which can help businesses with **targeted marketing, personalized offers, and customer retention strategies**.

---

## 📂 Project Structure
```
mall_customer_segmentation/
├── data/
│   └── Mall_Customers.csv          # Dataset
├── notebooks/
│   └── customer_segmentation.ipynb # Jupyter Notebook with clustering code
├── README.md                       # Project documentation
├── requirements.txt                # Dependencies
└── .gitignore                      # Ignore unnecessary files
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mall_customer_segmentation.git
   cd mall_customer_segmentation
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook notebooks/customer_segmentation.ipynb
   ```

4. Run all cells → generates customer clusters and visualizations.

---

## 📊 Results
- **Optimal number of clusters (k):** 5 (using Elbow Method).  
- **Cluster insights:**
  - Cluster 0 → Low income, low spending (conservative customers)  
  - Cluster 1 → Low income, high spending (impulsive buyers)  
  - Cluster 2 → Medium income, medium spending (average customers)  
  - Cluster 3 → High income, high spending (VIP customers 💰)  
  - Cluster 4 → High income, low spending (savers)  

✅ Final output: Scatter plot with 5 clusters and centroids.  

---

## 📜 License
This project is for educational purposes and demonstrates **unsupervised learning (K-Means)**.
