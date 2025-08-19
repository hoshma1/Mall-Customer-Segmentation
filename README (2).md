# 🛍️ Mall Customer Segmentation (K-Means Clustering)

## 📌 Project Overview
This project applies **Unsupervised Learning** to cluster mall customers into meaningful segments based on their **annual income** and **spending score**.  
By identifying customer groups, businesses can design targeted marketing strategies and improve customer experience.  

---

## 📂 Dataset
- **Mall Customers Dataset (Kaggle)**  
  [Download Here](https://www.kaggle.com/datasets/shwetabh123/mall-customers)  

### Features Used:
- `Annual Income (k$)` – Customer’s income  
- `Spending Score (1–100)` – Score assigned by the mall based on customer spending behavior  

---

## ⚙️ Tools & Libraries
- Python  
- Pandas – data handling  
- Matplotlib & Seaborn – visualization  
- Scikit-learn – K-Means clustering, StandardScaler  

---

## 🧠 Covered Topics
- **Unsupervised Learning**  
- **K-Means Clustering**  
- **Data Scaling (Standardization)**  
- **Elbow Method** to find optimal clusters  
- **Cluster Visualization (2D plots)**  

---

## 📊 Steps Implemented
1. **Data Cleaning** – checked for missing values.  
2. **Feature Selection** – selected `Annual Income` and `Spending Score`.  
3. **Feature Scaling** – applied `StandardScaler` for clustering stability.  
4. **Elbow Method** – determined optimal number of clusters (k=5).  
5. **K-Means Clustering** – assigned customers into groups.  
6. **Visualization** – plotted clusters in 2D.  
7. **Cluster Summary** – calculated average income & spending per cluster.  

---

## 📈 Results
- **Optimal Clusters (k):** 5  
- Customers segmented into groups such as:
  - High Income, High Spending  
  - Low Income, Low Spending  
  - High Income, Low Spending  
  - etc.  

### Example Visualization:
(Clusters will appear as distinct colored groups on a scatterplot of Income vs Spending Score)

---

## ▶️ How to Run
1. Download the dataset from Kaggle and place it in your working directory.  
2. Open the notebook in Jupyter/Colab.  
3. Run all cells step by step.  

```bash
pip install pandas matplotlib seaborn scikit-learn
