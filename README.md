# Mall Customer Segmentation using K-Means

## 📌 Overview
Customer segmentation of mall shoppers using **K-Means clustering** based on **Age**, **Annual Income**, and **Spending Score** to identify distinct customer groups for targeted marketing.

## 📊 Dataset
- **Source:** [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Rows:** 200 customers
- **Features:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

## 🛠️ Technologies Used
- **Python**
- **Pandas** & **NumPy** – data processing
- **Scikit-learn** – K-Means clustering, scaling, silhouette score
- **Matplotlib** & **Seaborn** – visualizations

## 🚀 Steps Followed
1. Data loading and exploration
2. Feature selection & scaling
3. Finding optimal number of clusters using **Silhouette Score**
4. Applying **K-Means clustering**
5. Visualizing clusters using **PCA**
6. Analyzing cluster characteristics

## 📈 Results
- Discovered clear customer segments such as:
  - High income & high spending
  - High income & low spending
  - Low income & high spending
  - Low income & low spending
- PCA visualization for 2D representation of clusters

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/mall-customer-segmentation-kmeans.git
