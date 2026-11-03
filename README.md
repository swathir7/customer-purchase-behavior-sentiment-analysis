# Customer Purchase Behavior & Sentiment Analysis

An end-to-end e-commerce analytics project combining customer purchase behavior analysis, SQL-based data management, Natural Language Processing (NLP), sentiment analysis, and interactive Power BI dashboards to derive actionable business insights.

## Project Overview

Understanding customer behavior and satisfaction is essential for improving e-commerce performance and customer retention. This project analyzes e-commerce transaction data and customer reviews to uncover purchasing patterns, evaluate customer sentiment, and investigate factors influencing customer satisfaction.

Using Python, SQL, NLP techniques, and Power BI, the project transforms raw transactional and review data into meaningful business insights.

## Business Objectives

- Understand customer purchasing patterns and transaction trends.
- Identify top-performing products and product categories.
- Analyze customer reviews using Natural Language Processing.
- Classify customer feedback based on sentiment polarity.
- Investigate the relationship between delivery performance and customer satisfaction.
- Develop interactive dashboards to support data-driven business decisions.

## Tech Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Database | MySQL |
| Query Language | SQL |
| NLP & Sentiment Analysis | TextBlob |
| Data Visualization | Microsoft Power BI |
| Data Processing | CSV, Jupyter Notebook |

## Dataset

The project uses e-commerce transactional and customer review datasets, including data from the Brazilian E-Commerce Public Dataset by Olist.

The datasets cover:
- Customer purchase and transaction information.
- Customer reviews and feedback.
- English-translated customer reviews.
- Processed data for dashboard development.

## Project Workflow

### 1. Data Management & SQL Analysis

- Worked with structured e-commerce datasets.
- Used SQL for database creation, data retrieval, joins, aggregations, and analytical queries.
- Integrated relevant customer purchase and review information for analysis.

### 2. Customer Purchase Behavior Analysis

Used Python (Pandas and NumPy) to explore:

- Customer purchasing patterns.
- Order and transaction trends.
- Product and category performance.
- Revenue distribution.
- Customer purchasing activity.

### 3. Sentiment Analysis Using NLP

Applied Natural Language Processing techniques to understand customer feedback.

- Prepared customer reviews for text analysis.
- Used English-translated customer reviews.
- Applied TextBlob to calculate sentiment polarity.
- Categorized reviews into Positive, Neutral, and Negative sentiments.
- Explored customer opinions and satisfaction patterns.

### 4. Delivery Performance & Customer Satisfaction

Analyzed delivery-related factors and their potential influence on customer satisfaction.

- Examined delivery performance.
- Compared estimated and actual delivery timelines.
- Investigated the relationship between delivery delays and customer review scores.
- Identified potential areas for improving the customer experience.

### 5. Power BI Dashboard

Developed an interactive Power BI dashboard to present key analytical findings through visualizations.

The dashboard supports exploration of:

- Customer purchase trends.
- Sales and revenue patterns.
- Product performance.
- Customer review sentiment.
- Customer satisfaction indicators.
- Delivery performance.

## Repository Structure

```text
customer-purchase-behavior-sentiment-analysis/
│
├── olist dataset/
│
├── Customer Purchase Behavior and Sentiment Analysis.ipynb
│
├── cust_pur_details.sql
│
├── customer_purchase_data.csv
│
├── customer_reviews_data.csv
│
├── updated_review_data.csv
│
├── olist_powerbi_final.csv
│
├── PowerBI Dashboard.pbix
│
└── README.md
```

## Key Business Questions

1. What are the purchasing patterns and transaction trends among customers?
2. Which products and categories perform best?
3. What is the distribution of positive, neutral, and negative customer sentiment?
4. How do delivery delays influence customer satisfaction?
5. What insights can e-commerce businesses use to improve customer experience and retention?

## Business Applications

The analysis can help e-commerce businesses:

- Understand customer purchasing behavior.
- Identify customer satisfaction issues.
- Improve delivery and fulfillment processes.
- Monitor product and category performance.
- Make informed, data-driven business decisions.

## Future Scope

- Implement RFM-based customer segmentation.
- Develop customer churn prediction models.
- Apply advanced NLP techniques for deeper review analysis.
- Build customer lifetime value (CLV) prediction models.
- Develop automated reporting and analytics pipelines.

