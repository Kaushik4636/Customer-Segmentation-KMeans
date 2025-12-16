# Customer Segmentation using K-Means Clustering

This project segments customers into different groups based on their purchasing behavior using K-Means clustering, an unsupervised machine learning algorithm.

## Project Objective
The goal is to identify distinct customer groups based on their **Annual Income** and **Spending Score**. This helps businesses tailor marketing strategies and improve customer targeting.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

## Dataset
- Dataset used: `Mall_Customers.csv`
- Features:
  - `CustomerID` (optional)
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## Workflow
1. **Data Loading:** Load dataset into a Pandas DataFrame.  
2. **Feature Selection:** Selected `Annual Income` and `Spending Score` as clustering features.  
3. **Data Scaling:** Applied StandardScaler to normalize features.  
4. **Optimal Cluster Selection:** Used the Elbow Method to determine the ideal number of clusters.  
5. **Model Training:** Applied K-Means clustering algorithm.  
6. **Visualization:** Plotted clusters to observe customer segments.  

## Results
- Customers were segmented into **3–5 distinct clusters** (depending on Elbow method).  
- Each cluster represents customers with similar income and spending behavior.  
- Visualization allows easy understanding of customer groups for business decisions.

## Conclusion
This project demonstrates how unsupervised machine learning can help businesses understand customer behavior and segment their audience effectively. It highlights the practical application of K-Means clustering in marketing and sales strategies.

## How to Run
1. Upload `Mall_Customers.csv` to your Google Colab or local machine.  
2. Run the notebook `customer_segmentation_kmeans.ipynb`.  
3. Visualize the clusters in the final plot.
