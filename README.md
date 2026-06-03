# SmartCart: E-commerce Customer Clustering System

A data-driven machine learning solution designed to transition e-commerce businesses from generic, uniform marketing to highly targeted, personalized customer engagement strategies.

## 🧠 The Business Problem

In the competitive e-commerce landscape, a "one-size-fits-all" marketing approach leads to wasted advertising budgets and lost revenue. Businesses frequently struggle to distinguish between their most valuable loyalists and one-time buyers. Without clear customer segmentation, companies cannot effectively allocate resources to maximize Return on Investment (ROI) and minimize customer churn.

## 💡 Actionable Insights Generated

By applying **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering**, this system successfully segmented the customer base into distinct, actionable profiles:

* **The Champions:** A small segment driving a disproportionately high percentage of total revenue. *Recommendation: Target with exclusive loyalty programs and early-access product drops.*
* **The At-Risk Shoppers:** Customers with historically high monetary value who haven't made a purchase recently. *Recommendation: Deploy targeted re-engagement campaigns and personalized discount codes to prevent churn.*
* **The Window Shoppers:** High frequency of site visits or low-value purchases but low overall monetary contribution. *Recommendation: Upsell through product bundling.*

## 🚧 Challenges Faced & Overcome

During the development of this clustering model, several technical hurdles were addressed to ensure accuracy and reliability:

* **Handling Skewed Financial Data:** E-commerce monetary data is often highly right-skewed due to a few massive purchasers. I applied log transformations and robust scaling techniques to normalize the data before feeding it into the clustering algorithm.
* **Determining the Optimal Clusters:** Selecting the right number of customer segments can be highly subjective. I utilized both the **Elbow Method** and **Silhouette Score analysis** to mathematically validate that the chosen number of clusters provided the most distinct and meaningful business groupings.
* **Data Quality & Noise:** The raw transaction logs contained missing Customer IDs and anomalous refund entries (negative values). I built a robust preprocessing pipeline to clean, filter, and structure the data specifically for RFM metric extraction.

## 🛠 Tech Stack

* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-learn (K-Means Clustering, StandardScaler)
* **Data Visualization:** Matplotlib, Seaborn

## 📂 Project Structure

```text
├── data/               # Contains raw and processed datasets
├── notebooks/          # Jupyter notebooks with EDA and Model Training
├── images/             # Visualizations (Elbow curve, Cluster scatter plots)
└── README.md           # Project documentation

```

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/LearnerNikhilk/SmartCart-E-commerce-Customer-Clustering-System.git

```


2. Install required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```


3. Open the Jupyter Notebook to explore the data pipeline and clustering results.

## 📬 Let's Connect

**Nikhil Kushwaha**

* Data Scientist | Data Analyst
* [GitHub Profile](https://github.com/LearnerNikhilk)
