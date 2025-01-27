# Data Analytics and Machine Learning Tasks  

## Project Overview  
This repository contains solutions for three data analytics and machine learning tasks. The tasks aim to extract business insights, develop a lookalike model, and segment customers using clustering techniques.  

---

## Tasks  

### Task 1: Business Insights Extraction  

#### Objective  
Analyze customer, product, and transaction data to derive actionable business insights.  

#### Key Results  
- **Highest Revenue Region**: South America, contributing 31.79% of total revenue (219,352.56 USD).  
- **Top 3 Customers**:  
  - C0141: 10,673.87 USD (1.55%).  
  - C0054: 8,040.39 USD (1.17%).  
  - C0065: 7,663.70 USD (1.11%).  
- **Best Performing Category**: Books, contributing 27.85% to total revenue.  
- **Peak Sales Month**: Month 7 shows the highest demand.  
- **Underperforming Category**: Home Decor, suggesting potential for improvement through targeted promotions.  

#### Deliverables  
- A report summarizing the key insights.  

---

### Task 2: Lookalike Model Development  

#### Objective  
Build a lookalike model to recommend similar customers based on profile and transactional behaviors.  

#### Methodology  
- **Algorithm**: Cosine Similarity was selected due to its ability to effectively measure similarity in high-dimensional spaces.  
- **Features**:  
  - Total spending.  
  - Transaction count.  
  - Unique products purchased.  
- **Evaluation**: Supervised evaluation using pre-labeled similar customer pairs.  

#### Deliverables  
- **Lookalike Recommendations**: A CSV file mapping each customer to their top 3 most similar customers with similarity scores.  

---

### Task 3: Customer Segmentation using Clustering  

#### Objective  
Segment customers using clustering techniques to understand customer behavior better and create personalized strategies.  

#### Methodology  
- **Algorithm**: K-Means Clustering.  
- **Reasoning**: The dataset contained minimal outliers, making K-Means suitable for this task.  
- **Cluster Evaluation Metrics**:  
  - **Davies-Bouldin Index (DBI)**: Best k = 2.  
  - **Silhouette Score**: Best k = 2.  
  - **Inertia**: Best k = 10.  
  - **Calinski-Harabasz Index**: Best k = 3.  
  - **Dunn Index**: Best k = 2.  
- **Final Selection**: Based on DBI, the optimal number of clusters is 2.  


---

## How to Run  

1. Clone the repository:  
   ```bash
   git clone <repository_url>
   cd <repository_folder>
