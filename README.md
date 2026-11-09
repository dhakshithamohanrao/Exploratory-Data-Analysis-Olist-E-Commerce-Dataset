# Olist E-Commerce: Exploratory Data Analysis & Business Insights

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the **Olist Brazilian E-Commerce Dataset**, using Python to investigate customer behaviour, seller performance, product trends, delivery efficiency, payment patterns, and customer satisfaction.

The objective is to identify meaningful business patterns and translate data into actionable insights that can support decision-making in marketing, logistics, inventory planning, and customer experience improvement.

## Dataset

**Source:** [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains multiple interconnected tables representing the e-commerce order lifecycle, from purchase to delivery and customer review.

The analysis uses the following datasets:

- Customers
- Orders
- Order Items
- Products
- Payments
- Reviews
- Sellers
- Product Category Translation

After combining the datasets, the resulting analysis table contains **119,143 rows and 40 columns**.

## Tools & Technologies

- **Python** – Data analysis and processing
- **Pandas & NumPy** – Data manipulation and feature engineering
- **Matplotlib & Seaborn** – Data visualisation
- **Jupyter Notebook / Google Colab** – Development environment

## Data Preparation & Feature Engineering

The project includes data loading, dataset merging, and data quality assessment.

The following derived metrics were created:

- `delivery_time_days` – Time between purchase and actual delivery.
- `approval_time_hours` – Time between purchase and payment approval.
- `delivery_delay_days` – Difference between actual and estimated delivery dates.
- `order_month` – Monthly grouping for sales trend analysis.

The analysis also considers missing timestamps, incomplete product category information, and missing review comments.

## Key Areas of Analysis & Visualisations

### 1. Revenue & Product Performance
- Identified the top 10 product categories by revenue.
- Examined revenue concentration across product categories.
- Highlighted the importance of high-performing categories such as health and beauty.

### 2. Monthly Sales Trends
- Analysed monthly revenue patterns.
- Identified fluctuations and peak sales periods.
- Highlighted November 2017 as the highest-revenue month in the analysis.

### 3. Delivery Performance & Customer Satisfaction
- Compared delivery-time distributions across customer review scores.
- Examined the relationship between delivery speed and customer ratings.
- Investigated how delivery delays relate to customer experience.

### 4. Payment Behaviour
- Analysed the distribution of payment methods.
- Compared the usage of credit cards, boleto, vouchers, and debit cards.
- Identified credit cards as the dominant payment method, followed by boleto.

### 5. Correlation Analysis
- Examined relationships between delivery metrics, payment values, prices, and review scores.
- Used a correlation heatmap to explore associations between operational and customer-related metrics.

### 6. Customer Satisfaction
- Analysed the distribution of customer review scores.
- Compared positive and negative ratings.
- Identified opportunities to investigate low-rated customer experiences.

### 7. Customer Geographic Distribution
- Identified the top 10 customer cities by customer count.
- Explored geographic concentration, particularly in major urban centres such as São Paulo and Rio de Janeiro.

### 8. Seller Performance
- Compared seller order volumes with average delivery times.
- Identified variation in delivery performance across sellers.
- Highlighted opportunities for logistics monitoring and seller performance improvement.

### 9. Customer Revenue Concentration
- Applied Pareto-style analysis to examine cumulative revenue across customers.
- Investigated the contribution of high-value customers to overall revenue.
- Explored opportunities for customer retention and loyalty initiatives.

### 10. Delivery Delays & Order Outcomes
- Categorised delivery performance into early, on-time, and late deliveries.
- Compared delivery timing with order status.
- Explored the relationship between delivery reliability and order outcomes.

### 11. Satisfaction Across Product Categories
- Compared review score distributions across leading product categories.
- Used violin and strip plots to explore differences in customer satisfaction.
- Examined whether revenue performance and customer ratings follow similar patterns.

## Key Findings

The analysis highlights several business patterns:

- Revenue is concentrated in a relatively small number of product categories, particularly health and beauty and watches and gifts.
- Monthly sales fluctuate, with notable revenue peaks in late 2017.
- Delivery time and delivery delays are negatively associated with customer review scores.
- Credit cards represent the most commonly used payment method, followed by boleto.
- Customer reviews show a substantial presence of both high and low ratings.
- Seller delivery performance varies across the marketplace.
- Customer activity is concentrated in major Brazilian cities.
- Revenue contribution varies across customers, highlighting the importance of understanding high-value customer segments.

## Business Recommendations

Based on the analysis, the following actions could support marketplace optimisation:

1. **Improve logistics reliability:** Reduce delivery delays and strengthen delivery performance monitoring.
2. **Optimise inventory and marketing:** Prioritise high-revenue product categories.
3. **Monitor seller performance:** Establish logistics benchmarks and monitor consistently slow-performing sellers.
4. **Improve customer communication:** Provide clearer shipping updates to reduce uncertainty.
5. **Optimise payment experience:** Maintain a smooth credit card checkout while supporting alternative payment methods.
6. **Strengthen customer retention:** Explore loyalty programmes and personalised offers for high-value customers.

## Limitations

- Missing delivery timestamps affect the accuracy of delivery-time and delay calculations.
- Some product category information is incomplete.
- Missing review comments limit the scope of text-based sentiment analysis.
- The dataset does not contain cost, profit, or inventory information, restricting financial and inventory-level analysis.
- The dataset represents historical marketplace activity and may not reflect current business conditions.

## Future Work

Potential extensions of this project include:

- Predictive modelling for delivery delays and customer satisfaction.
- Customer segmentation using RFM analysis or clustering.
- Sentiment analysis of customer review comments.
- Monthly sales forecasting using time-series models.
- Seller segmentation based on delivery performance and product mix.
- Development of a recommendation system using customer and product behaviour.

## Conclusion

This project demonstrates how exploratory data analysis and visualisation can uncover patterns in e-commerce operations and customer behaviour.

By connecting revenue performance, logistics efficiency, payment preferences, seller activity, and customer satisfaction, the analysis provides a foundation for data-driven business decisions and further predictive analytics.

---

**Author:** Dhakshitha Mohan Rao  
**Project:** Exploratory Data Analysis – Olist Brazilian E-Commerce Dataset
