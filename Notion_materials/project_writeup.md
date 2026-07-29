# Global Superstore Profitability Analysis

## 1. Project Background

Global Superstore is a multinational retail company operating across multiple markets. Between 2022 and 2025, the company experienced continuous sales growth. However, profit margin failed to improve at the same pace.

This project investigates the underlying causes of declining profitability using SQL, Python and Tableau, with the objective of providing data-driven business recommendations.

---

## 2. Business Scenario

Assume you are working as a Business Analyst for Global Superstore.

Senior management has observed that revenue continues to increase each year, yet overall profitability has stagnated. They would like to understand:

- whether sales growth is translating into profit growth
- which product categories generate the largest losses
- whether aggressive discount strategies are hurting profitability
- which markets require immediate management attention
- whether high-discount orders are associated with higher return rates

The objective is to identify the root causes of declining profit margin and recommend practical business actions.

---

## 3. Dataset Overview

The analysis is based on the Global Superstore dataset.

Three relational tables were used:

| Table | Description |
|--------|-------------|
| Orders | Sales transactions |
| Returns | Returned orders |
| People | Regional managers |

After data preparation, a consolidated analytical table was created using SQL joins to support downstream business analysis.

---

## 4. Analysis Methodology

The project followed a complete business analytics workflow:

1. Data Preparation (SQL)
2. Data Cleaning
3. Annual KPI Analysis
4. Discount Strategy Analysis
5. Product Profitability Analysis
6. Regional Performance Analysis
7. Return Analysis
8. Python Visualization
9. Tableau Dashboard
10. Business Recommendations
---

## 5. Key Findings

The analysis identified several critical business insights:

### 1. Continuous Sales Growth Did Not Translate into Profit Growth

Although total sales increased steadily between 2022 and 2025, profit margin remained relatively flat and even declined slightly in the final year.

This indicates that revenue growth alone was insufficient to improve overall business profitability.

---

### 2. Aggressive Discounting Reduced Profitability

Orders with discounts of 20% or higher consistently generated significantly lower profit margins.

While discounts contributed to higher sales volume, excessive discounting eroded overall profitability.

---

### 3. Product Losses Were Highly Concentrated

Losses were not evenly distributed across all products.

Several sub-categories—including Tables and Bookcases—contributed disproportionately to overall losses and should be prioritized for pricing and product strategy reviews.

---

### 4. Regional Performance Varied Significantly

Certain markets generated strong revenue but comparatively weak profitability.

This suggests that regional pricing strategies, customer behavior and discount policies should be evaluated independently rather than applying a uniform global strategy.

---

### 5. High-discount Orders Showed Higher Return Rates

Orders receiving aggressive discounts were more likely to be returned.

The combination of lower margins and higher return rates further reduced business profitability.

---

## 6. Business Recommendations

Based on the analytical findings, the following business recommendations are proposed:

### Optimize Discount Strategy

Replace blanket discount policies with targeted promotions focused on profitable products and customer segments.

---

### Review Loss-making Product Categories

Conduct pricing and cost analyses for consistently unprofitable sub-categories, particularly Tables and Bookcases.

---

### Strengthen Regional Pricing Management

Implement market-specific pricing strategies instead of relying on a single global discount policy.

---

### Improve Return Management

Monitor high-discount transactions more closely and investigate the underlying causes of increased return rates.

---

### Shift Performance Evaluation

Incorporate profitability metrics alongside revenue growth when evaluating business performance to encourage sustainable growth.

---

## 7. Project Deliverables

This project includes the following deliverables:

- SQL scripts for data preparation and business analysis
- Python notebook for data processing and visualization
- Tableau interactive dashboard
- Business analysis report
- Executive summary
- GitHub repository containing all project resources
---

## 8. Future Improvements

Future enhancements could include:

- Customer segmentation using RFM analysis
- Profit forecasting using predictive models
- Customer lifetime value (CLV) analysis
- Promotional effectiveness evaluation
- Interactive dashboards with drill-down capabilities
- Automated reporting pipelines using Python
---

## Conclusion

This project demonstrates an end-to-end business analytics workflow—from SQL data preparation and business analysis to Python visualization, Tableau dashboard development and business recommendation delivery.

Rather than focusing solely on technical implementation, the project emphasizes solving practical business problems through data-driven decision-making.
