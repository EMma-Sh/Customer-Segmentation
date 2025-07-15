# 🛍️ Customer Segmentation using K-Means Clustering

A machine learning project that applies unsupervised learning to segment retail customers into distinct groups based on their age, income, and spending score. This helps businesses understand different customer behaviors and personalize marketing strategies accordingly.


## 🎯 Goal

To cluster customers into meaningful groups using K-Means based on behavioral and demographic data, and visualize those segments to identify patterns in spending and income.


## 🧰 Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data handling
- **Scikit-learn** – Clustering (K-Means), Scaling, PCA
- **Matplotlib, Seaborn** – Visualization


## 📂 Dataset

- **Name**: Mall Customers Dataset  
- **Source**: [Kaggle - Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Fields Used**:
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)


## ⚙️ Project Workflow

1. **Load Dataset**: Read `Mall_Customers.csv`
2. **Feature Selection**: Focused on Age, Annual Income, and Spending Score
3. **Scaling**: Used `StandardScaler` to normalize features
4. **Find Optimal Clusters**: Applied Elbow Method to determine best K
5. **K-Means Clustering**: Grouped customers into 3–5 clusters
6. **Visualization**:
   - 2D Scatter Plots (Age vs Spending, PCA plot)
   - Cluster-wise centroid analysis
7. **Interpretation**: Described behavior of each cluster


## 📊 Visual Outputs

- **Elbow Curve**: Helped identify the ideal number of clusters  
- **Scatter Plot (Age vs Spending Score)**: Showed customer grouping  
- **PCA Visualization**: Displayed clusters in 2D space  
- **Cluster Centroids**: Helped describe group behavior


## 🧠 Key Insights

- Cluster 0: High income, low spenders — potential for premium engagement  
- Cluster 1: Young, high spenders — ideal for targeted ads or offers  
- Cluster 2: Older, low spenders — may need retention strategies  
- Clear segmentation improves marketing decisions and customer satisfaction

## 📁 Project Structure

┣ 📄 customer_segmentation_kmeans.ipynb
┣ 📄 Mall_Customers.csv

## 👩‍💻 Author

**Eman Iqbal**  
Machine Learning & Data Science Enthusiast  
📍 Pakistan  
📧 emmnqb@gmail.com 
🔗 www.linkedin.com/in/emaniqbal

## 📌 Future Improvements

- Apply DBSCAN or Hierarchical Clustering for comparison  
- Add customer gender and region into clustering  
- Build a Streamlit dashboard for business users

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
