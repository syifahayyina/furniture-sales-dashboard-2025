# 2025 Furniture Sales Dashboard

## Project Overview
This project presents an interactive furniture sales dashboard built with Looker Studio, using Excel for data preparation and exploratory analysis. It analyzes 10,000 orders from January to December 2025 to uncover insights into revenue trends, product and category performance, regional contribution, and order completion. The goal is to help business stakeholders understand what drives revenue and where opportunities lie.

## Dataset Description
The dataset contains 10,000 furniture orders from January to December 2025. Each record represents one order, with a status of Completed, Cancelled, or Refund.
* Order : order_id, sales_date, Status
* Product: product_name, category
* Customer and location: customer_name, Kota
* Metrics: price, quantity, discount, total, shipping_fee, total_sales

## Project Objectives
1. Track monthly revenue trends and identify the peak and lowest months
2. Summarize overall performance : total revenue, total orders, completion rate, and average order value
3. Identify the categories and products that contribute the most revenue
4. Compare units sold against revenue share to find low-volume but high-revenue products, and vice versa
5. Evaluate revenue cities

## Visualizations Included
* KPI Summary : Total revenue, total orders, completion rate, and average order value (AOV)
* Line Chart : Monthly revenue trend
* Pie Chart : Transaction status (completed, cancelled, refund)
* Bar Chart : Top 5 products by revenue, Units sold vs revenue share by product, and Revenue by city
* Donut Chart : Revenue share by category
* Interactive Filters : Filter by month

## Tools Used
* Microsoft Excel : Data cleaning and pivot tables for exploratory analysis
* Looker Studio : Interactive dashboard
* GitHub : Documentation

## Key Insight
* Monthly revenue is relatively flat in the first half of the year, peaks in August, then declines toward the end of the year, with November as the lowest month.
* About 90% of orders are completed, and cancellations and refunds are low and consistent across categories and cities.
* Bedroom, Living Room, and Kitchen are the top revenue-generating categories, together contributing about 83% of total revenue.
* Kitchen Set is the top-performing product, followed by Kasur and Lemari Sliding.
* Units sold are spread evenly across products, but a few high ticket items such as Kitchen Set, Kasur, and Lemari Sliding contribute a much larger share of revenue.
* Revenue is fairly balanced across cities. Jakarta Utara ranks highest and Bekasi lowest, with only small gaps between them.
