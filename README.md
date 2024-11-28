# Credit Card Reporting Analysis

## Overview
This report provides a comprehensive analysis of credit card performance, including revenue, transaction trends, customer demographics, and spending behaviors. The data is sourced and managed using PostgreSQL, where two key tables—`cc_detail` and `cust_detail`—store credit card and customer details, respectively.

---

## Data Management
- **Database**: PostgreSQL  
- **Tables Created**:
  1. `cc_detail`: Contains all credit card transaction details, including card types, transaction amounts, and interest earned.  
  2. `cust_detail`: Stores customer information such as demographics, job types, and income levels.  

---

## Key Highlights

### 1. Revenue and Transaction Trends
- **Total Revenue**: ₹57M  
- **Total Transactions**: 667K  
- **Quarterly Breakdown**:
  - **Revenue**: Q4 contributed the most at 25.4%, followed by Q3 (25.0%), Q1 (24.6%), and Q2 (24.2%).
  - **Transactions**: Q2 led with 26.0%, while Q3, Q1, and Q4 followed with 25.0%, 24.5%, and 24.5%, respectively.

---

### 2. Spending Insights by Category
- **Bills**: Account for 24.6% of total revenue, the highest category.  
- **Entertainment and Fuel**: Each contributes 17.5%.  
- **Grocery**: 15.8%.  
- **Food**: 14.0%.  

---

### 3. Card Performance
- **Blue Card**: Dominates with 82.4% of revenue (₹47M).  
- **Silver Card**: 10.5%.  
- **Gold Card**: 5.3%.  
- **Platinum Card**: 1.8%.  

---

### 4. Customer Demographics
#### By Job Type:
- **Businessmen**: Contribute 31.6% of revenue.  
- **White-collar professionals**: 17.5%.  
- **Self-employed**: 15.8%.  
- **Government employees**: 14.0%.  

#### By Education:
- **Graduates**: Drive 40.4% of revenue.  
- **High School**: 19.3%.  
- **Uneducated**: 14.0%.  

#### By Income Group:
- **High Income**: 40.4% of revenue.  
- **Medium Income**: 14.0%.  
- **Low Income**: 12.3%.  

#### By Geography:
- **California, New York, and Texas**: Each contributes 12.3% to total revenue.  

---

## Recommendations for Stakeholders
1. **Focus on Blue Card Holders**:  
   With 82.4% of revenue, this segment is crucial. Consider loyalty rewards and premium benefits to retain high-value users.  

2. **Capitalize on High-Spending Categories**:  
   Bills (24.6%), entertainment, and fuel (17.5% each) represent the largest spending areas. Tailor marketing campaigns and offers to these categories.  

3. **Engage High-Value Customer Segments**:  
   High-income earners (40.4%) and graduates (40.4%) are significant contributors. Introduce exclusive services and promotions aimed at these groups.  

4. **Expand Regional Marketing**:  
   Focus on California, New York, and Texas, which together account for 36.9% of revenue. Regional campaigns and partnerships could amplify growth in these areas.  

---

## Usage Instructions
- Open the `.pbix` file in Power BI Desktop to view and interact with visualizations.  
- Use PostgreSQL tables (`cc_detail` and `cust_detail`) to query raw data for advanced analysis or integration into other systems.  

---

## Author
Created by **Gaurav Patokar**.  
For inquiries or collaborations, connect on [LinkedIn](https://www.linkedin.com/in/gauravpatokar) or explore more projects on [GitHub](https://github.com/gauravpatokar).
