# 🛍️ Mall Customer Segmentation using Unsupervised Machine Learning

## 📌 Project Overview
This project performs customer segmentation using unsupervised machine learning techniques to identify groups of customers with similar purchasing behavior. By analyzing customer demographics and spending patterns, the project helps businesses develop targeted marketing strategies and improve customer engagement.

---

## 🚀 Features
- Exploratory Data Analysis (EDA)
- Customer behavior visualization
- Data preprocessing and feature scaling
- Customer segmentation using multiple clustering algorithms
- Optimal cluster selection using Elbow Method and Silhouette Score
- Cluster visualization and business insights
- Customer segment recommendations

---

## 📂 Dataset
The project uses the **Mall Customers Dataset** containing customer demographic and spending information.

### Dataset Features
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Joblib

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset exploration
- Missing value analysis
- Pair plots
- Correlation heatmap
- Customer distribution analysis
- Income vs Spending visualization

---

## ⚙️ Data Preprocessing

- Selected relevant numerical features
- Standardized features using **StandardScaler**
- Prepared data for clustering algorithms

---

## 🤖 Clustering Algorithms Implemented

The following unsupervised learning algorithms were implemented and compared:

- K-Means Clustering
- Agglomerative Hierarchical Clustering
- DBSCAN
- Gaussian Mixture Model (GMM)

---

## 🔍 Model Selection

The project determines the optimal number of clusters using:

- Elbow Method (WCSS)
- Silhouette Score
- Cluster comparison across multiple algorithms

---

## 📈 Results & Business Insights

- Segmented customers into meaningful behavioral groups.
- Identified high-value, average-value, and low-value customer segments.
- Assigned descriptive labels to customer groups based on income and spending behavior.
- Generated business recommendations for each customer segment to support targeted marketing campaigns.

---

## 📁 Project Structure

```
MallCustomerSegmentation/
│
├── mallcustomersegmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/MallCustomerSegmentation.git
```

Navigate to the project directory

```bash
cd MallCustomerSegmentation
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
mallcustomersegmentation.ipynb
```

---

## 📌 Future Improvements

- Interactive dashboard using Streamlit
- Customer recommendation system
- Real-time customer segmentation
- Dimensionality reduction using PCA or t-SNE
- Automated cluster monitoring and reporting

---

## 📄 License

This project is intended for educational and learning purposes.

---
