# 🧠 Customers Segmentation Using K-Means

This project focuses on segmenting customers into distinct groups using the **K-Means Clustering** algorithm. By analyzing behavioral and demographic attributes, the goal is to help businesses tailor their marketing strategies, improve customer experience, and boost profitability.

---

## 📊 Overview

Customer segmentation is a key strategy in marketing and data analytics. It allows businesses to better understand the diversity of their customer base and develop targeted campaigns.

This project implements:
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **K-Means Clustering**
- **Cluster Visualization**
- **Business Insights**
- **Naive Recommender Engine For Customers**

---

## 📁 Dataset

The dataset contains anonymized customer information. Typical features used include:
- Date of Birth  
- Balance
- Transactions 
- Gender 

> Dataset: attached as a zip file

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Visualization
- **Scikit-learn** – K-Means Clustering, StandardScaler
- **Jupyter Notebook** – Interactive analysis

---

## 🔍 Key Steps

1. **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Feature selection  
   - Data normalization
   - Feature Engineering (creating new features)

2. **Exploratory Data Analysis**  
   - Distribution of features  
   - Count Plots

3. **K-Means Clustering**  
   - Elbow Method to find optimal `k`  
   - Applying K-Means  
   - Assigning cluster labels

4. **Visualization**  
   - Used **PCA** for 2D cluster plotting
   - Cluster interpretation

5. **Business Insights**  
   - Understanding the characteristics of each cluster  
   - Recommendations for marketing strategies

---

## 📈 Results

- Optimal number of clusters determined using the **Elbow Method**  
- Distinct customer groups discovered based on **income** and **spending score**  
- Visual insights generated to guide **marketing decision-making**

---

## 📌 Future Improvements

- Use **t-SNE** for dimensionality reduction and better visualization  
- Experiment with **other clustering algorithms** (e.g., DBSCAN, Agglomerative Clustering)  
- Deploy the model as an interactive **Streamlit app**  
- Integrate with a customer-facing dashboard (e.g., Power BI)

---

## 🚀 Getting Started

1. Clone the repository  
```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the notebook
```bash
jupyter notebook Customer_Segmentation_KMeans.ipynb
```
