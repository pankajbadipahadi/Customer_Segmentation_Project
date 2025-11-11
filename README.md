# 🧠 Customer Segmentation Web App (Streamlit + KMeans)

This project is a **Customer Segmentation Dashboard** built with **Streamlit**.
It uses a pre-trained **KMeans clustering model** and **scaler** to group customers based on their purchasing behavior and demographics.
The app also allows users to **upload their own marketing campaign data (CSV)** and automatically **predict clusters**, visualize spending behavior, and explore key insights.

---

## 🚀 Features

* 🧩 **KMeans Clustering** for customer segmentation
* 📊 **Interactive Streamlit Dashboard** with visual analytics
* 📂 **CSV Upload Support** — automatically assigns clusters using the trained model
* 📈 **Cluster-wise Summary Statistics** (Income, Total Spending, Recency, etc.)
* 💾 **Downloadable Output** with predicted clusters
* 🔍 **Data Exploration Tools** to view uploaded samples and key metrics

---

## 📁 Project Structure

```
customer_segmentation_project/
│
├── kmeans_model.pkl          # Trained KMeans clustering model
├── scaler.pkl                # StandardScaler used during model training
├── marketing_campaign.csv    # Original dataset used for training
├── customer_segmentation_project.py                    # Main Streamlit app script
├── requirements.txt          # List of dependencies
└── README.md                 # Project documentation
```

---

## ▶️ Run the App using Streamlit link
https://customersegmentationproject-vajjtxbzbghia9sqgzha7q.streamlit.app/


---

## 🧠 Model Overview

* **Algorithm:** KMeans Clustering
* **Number of Clusters:** 3 (customizable in training)
* **Features Used:**

  * Age
  * Income
  * Total Spending
  * Recency
  * Number of Children
  * Customer Tenure
  * Encoded Education & Marital Status

You can retrain or fine-tune the model by updating the training script (not included in deployment version).

---

## 🖼️ Dashboard Preview

```
📂 Upload CSV → ⚙️ Model Prediction → 📊 Cluster Visualization → 💾 Download Results
```

The dashboard shows:

* Average income and spending per cluster
* Customer recency distribution
* Cluster-level comparisons using interactive Plotly charts

---

## 🧑‍💻 Built With

* **Python 3.9+**
* **Streamlit** — for web UI
* **Pandas & NumPy** — for data handling
* **Scikit-learn** — for clustering
* **Plotly** — for interactive visualizations

---

## 🤝 Contributors

* **Pankaj Badipahadi** – Project Developer
* **Sanchit Satpaise**
* **Parth Neware**
* **Abdul Danish**
* **Shruty P**
* **Shrishav**

---

🏁 Future Enhancements

🔮 Add DB integration (e.g., PostgreSQL) for live data storage
🧠 Enable retraining from dashboard UI
📈 Add more advanced visualizations (e.g., 3D PCA cluster view)
