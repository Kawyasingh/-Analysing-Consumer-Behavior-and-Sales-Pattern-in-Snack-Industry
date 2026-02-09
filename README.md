# Customer Behavior and Sales Pattern Analysis in the Snack Industry

## Project Overview

This data analytics project investigates customer segmentation, purchasing behavior, and sales patterns for a leading chip retailer. The analysis explores various dimensions including customer lifestyle stages, customer types (mainstream, premium, budget), product preferences by size and brand, and seasonal trends. Feature engineering and statistical hypothesis testing were employed to generate actionable insights for improving inventory planning, targeted marketing, and promotional strategies.

## Dataset Description

The analysis uses two primary datasets:

- **Customer Data**: Customer segmentation by life stage (LIFESTAGE) and spending behavior (CUSTOMER_TYPE); ~ 72,000+ records.

- **Transaction Data**: Purchase transactions including product names, quantities, prices, and dates; ~ 2,60,000+ records.

Key points:

- Data spans an entire calendar year.

- Transaction dates required transformation from Excel integer format to datetime.

- Product names contained embedded weight information (e.g., "250g") requiring feature engineering.

## Project Structure
The workflow follows a structured analytics pipeline:

1) Data Preparation
   - Cleaned and feature engineered product names.

   - Fixed transaction date fields.

   - Updated column names for better clarity.

2) Feature Engineering
   - Extracted packet size (grams) from product names.

   - Calculated total sales per transaction and spend per customer.

   - Aggregated sales data across brands, packet sizes, and customer groups.

3) Exploratory Data Analysis (EDA)
   - Examined customer demographic distributions.

   - Analyzed sales performance by brand and product size.

   - Identified seasonal patterns in sales volume.

4) Statistical Analysis
   - Conducted independent two-sample t-tests to assess spending behavior differences between customer groups.

   - Verified significance of observed behavioral patterns.

5) Insights and Strategic Recommendations
   - Synthesized findings into actionable strategies for inventory and marketing optimization.


## Key Insights
- Kettle was the top-selling brand throughout the year.

- 175g packet size dominated sales across all customer segments.

- Budget older families and mainstream young singles/couples were the primary contributors to overall sales.

- Seasonal spikes, particularly around Christmas, suggest strong promotional opportunities.

- Younger mainstream customers demonstrated higher spend-per-transaction, indicating potential for upselling and impulse buying strategies.

## Recommendations
- Focus inventory and promotional efforts around Kettle products and 175g packet sizes.

- Implement segment-specific marketing to target high-value customer groups.

- Scale marketing campaigns and stock replenishment 2–3 weeks before Christmas to capitalize on peak demand.

- Position complementary products strategically to appeal to impulse buying tendencies observed in younger customer segments.

## Tools and Technologies
![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=NumPy&logoColor=white)
![](https://img.shields.io/badge/SciPy-8CAAE6.svg?style=for-the-badge&logo=SciPy&logoColor=white)
![](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)


## Quick Summary
This project showcases how thoughtful data cleaning, feature engineering, and statistical validation can uncover valuable insights hidden within retail transaction data — and how those insights can directly translate into better business decisions.
