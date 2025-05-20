# Customer Segmentation – KJ Marketing

## Final Project Repository

This repository contains the **finalized codebase, resources, and documentation** for the customer segmentation project developed for **KJ Marketing**, a leading retail supermarket chain in Sri Lanka. The project was completed as part of an academic-industry collaboration and is aimed at implementing a **personalized, data-driven marketing strategy** through intelligent customer classification.

---

## Project Overview

KJ Marketing seeks to modernize its customer engagement by moving beyond traditional marketing methods that no longer resonate with its evolving customer base. This project focuses on classifying **new customers into six well-defined segments** based on their purchasing behavior in three core product categories:

- **Dry Goods**: Non-perishable staples such as cereals, snacks, and beverages  
- **Fresh Produce**: Perishable items like fruits, vegetables, and dairy  
- **Luxury Items**: High-end goods including electronics, fashion, and gourmet products  

---

## Objective

The primary goal is to develop and deploy a **clustering-based classification model** that can accurately assign new customers to one of six predefined segments using historical purchasing data. These insights will empower KJ Marketing to run **tailored marketing campaigns** and strengthen customer relationships.

---

## Customer Segments

| Cluster Number | Cluster Name              | Outlet City     | Fresh Sales | Dry Sales | Luxury Sales |
|----------------|---------------------------|------------------|-------------|-----------|--------------|
| 1              | Value Seekers              | Both             | Very Low    | High      | Very Low     |
| 2              | Elite Shoppers             | Mostly Urban     | Very High   | Very High | Highest      |
| 3              | Smart Savers               | Both             | High        | Very Low  | Lowest       |
| 4              | Essentials-Only            | Mostly Urban     | Lowest      | Low       | Low          |
| 5              | High Volume Spenders       | Mostly Urban     | Low         | Highest   | Very High    |
| 6              | Wellness Driven            | Both             | Highest     | Lowest    | High         |

### Segment Profiles:
- **Value Seekers**: Price-conscious shoppers with strong focus on dry goods  
- **Elite Shoppers**: Affluent customers with broad spending across all categories  
- **Smart Savers**: Value seekers with high fresh produce focus  
- **Essentials-Only**: Low-volume shoppers with minimal purchasing activity  
- **High Volume Spenders**: Volume-driven buyers with premium preferences  
- **Wellness Driven**: Health-focused and brand-loyal segment with strong fresh and luxury purchases  

---

## Methodology

1. **Data Preparation**
   - Cleaned and transformed historical sales data
   - Standardized numerical features and handled missing values  
2. **Feature Engineering**
   - Focused on impactful features like product category spending and outlet city
   - Scaled data for optimal clustering results  
3. **Clustering and Classification**
   - Applied multiple clustering algorithms and validated segment coherence
   - Trained predictive classification models for segment prediction on new data  
4. **Deployment Insight**
   - Final model enables integration into KJ Marketing’s CRM or campaign engine for segment-based targeting  

---

## Tech Stack

- **Languages & Libraries**:  
  `Python`, `Pandas`, `Polars`, `NumPy`, `Scikit-learn`, `Seaborn`, `Matplotlib`, `Plotly`  
- **Machine Learning Models**:  
  `K-Means`, `LightGBM`, `XGBoost`, `RandomForest`, `Multinomial Logistic Regression`, `EBM` 
- **Development Tools**:  
  `Jupyter Notebook`  

---

## Contributors

- **Hikma Shazneen**  
- **Aaliyah Shakoor**  
- **Hansa Wijeratne**  
- **Livin John**  
- **Muhammed Saneej**

---

> This repository marks the final submission, inclusive of all cleaned datasets, optimized models, visualizations, and scripts used throughout the project.
