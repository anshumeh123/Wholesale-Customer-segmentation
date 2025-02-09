# 🚀 Wholesale Customer Segmentation & Revenue Optimization  

📊 **Uncovering hidden customer patterns to drive business growth through data science.**  

---

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Business Impact](#business-impact)
- [Technical Approach](#technical-approach)
- [Findings & Business Recommendations](#findings--business-recommendations)
- [How to Run the Project](#how-to-run-the-project)
- [Next Steps & Future Improvements](#next-steps--future-improvements)
- [Contact & Contribution](#contact--contribution)

---

## 📊 Project Overview  
**In today's fast-moving wholesale industry, businesses struggle to understand customer purchasing behavior.**  
This project leverages **K-Means Clustering** and **EDA (Exploratory Data Analysis)** to segment customers, optimize marketing strategies, and streamline inventory management.  

### 🔍 **Problem Statement**  
**Can we segment wholesale customers based on their purchasing behavior to improve business decisions?**  

### 📌 **Dataset Information**
- **440 clients** across **two business channels**:  
  - **Horeca (Hotels, Restaurants, Cafes)**
  - **Retail**
- **Six product categories**: Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicatessen  
- **Features include** customer spending patterns, region, and business channel  

---

## 💡 Business Impact  
✅ **Cost Optimization:** Improve supply chain decisions based on purchasing trends.  
✅ **Customer Personalization:** Segment high-value customers for **tailored marketing campaigns**.  
✅ **Demand Forecasting:** Use insights to **reduce stockouts & overstocking**, boosting efficiency.  
✅ **Revenue Growth:** Focus on high-spending clusters to **maximize sales potential**.  

---

## 🛠️ Technical Approach  

### 🔹 **1. Data Preprocessing & EDA**
✔️ Removed **outliers** using the **IQR method**  
✔️ **Visualized spending patterns** (Boxplots, Correlation Heatmaps)  

### 🔹 **2. Clustering & Key Insights**
✔️ Applied **K-Means Clustering** to segment customers  
✔️ Used **Elbow Method & Silhouette Score** for cluster optimization  
✔️ **Denormalized cluster centroids** to bring back real-world spending values  

---

## 📊 Findings & Business Recommendations  

| Cluster | Customer Type | Key Spending Behavior | Business Recommendation |
|---------|--------------|----------------------|-------------------------|
| 1 | **Premium Restaurants** | High Fresh & Grocery spend | Premium ingredient partnerships |
| 2 | **Gourmet Delis** | High Delicatessen spend | Targeted gourmet product promotions |
| 3 | **Cafes & Bakeries** | High Milk & Detergents spend | Focus on dairy & cleaning supply bundling |
| 4 | **Bulk Catering** | High Frozen food spend | Optimize bulk pricing for large suppliers |
| 5 | **Budget Eateries** | Low spending | Introduce discount packages & loyalty programs |

---

## ⚙️ How to Run the Project  

### 🔹 **1. Prerequisites**
- Install R or Python  
- Required Libraries: `tidyverse`, `ggplot2`, `cluster`, `factoextra`  

### 🔹 **2. Clone the Repository**
```bash
git clone https://github.com/yourusername/wholesale-customer-segmentation.git
cd wholesale-customer-segmentation
