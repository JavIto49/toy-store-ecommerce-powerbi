# Toy Store E-Commerce Performance Analysis (Power BI)

Project Overview

This project analyzes e-commerce performance across marketing, product, and overall business metrics using Power BI.

The dashboard focuses on:
	•	revenue and order performance
	•	marketing channel effectiveness
	•	conversion behavior over time
	•	product-level profitability and risk
	•	revenue concentration across products

The goal was to build a multi-page dashboard that supports both executive reporting and deeper analysis.

⸻

Dataset

The dataset includes:
	•	website sessions and traffic sources
	•	customer orders and order items
	•	product information
	•	refund data

Key fields include:
	•	website_session_id, order_id, product_id
	•	utm_source, created_at
	•	price_usd, cogs_usd, refund_amount_usd

⸻

Data Model

The model connects website traffic, orders, and product data.

Key relationships:
	•	WebsiteSessions ↔ Orders via website_session_id
	•	Orders → OrderItems → Refunds
	•	Products → OrderItems
	•	Calendar → WebsiteSessions (drives time analysis)

This structure enables both channel attribution and product-level analysis.

⸻

Key Metrics
	•	Gross Revenue
	•	Total Orders
	•	Conversion Rate
	•	Refund Rate
	•	Total Profit
	•	Product Profit Margin
	•	Top Product Revenue Share

⸻

Dashboard Pages

Executive Overview
	•	KPI summary of revenue, orders, conversion, refund rate, and product concentration
	•	revenue by channel and product
	•	conversion trend
	•	key business insight

⸻

Marketing Performance
	•	traffic and conversion metrics
	•	revenue by channel
	•	conversion rate by channel
	•	sessions and orders over time

⸻

Product Performance
	•	revenue and profit by product
	•	product profit margin
	•	refund analysis
	•	top product contribution and risk

⸻

Key Insights
	•	Revenue reached ~$1.94M with a ~6.83% conversion rate
	•	gsearch drives the majority of revenue
	•	untracked traffic has the highest conversion rate
	•	The Original Mr. Fuzzy generates ~62% of revenue
	•	The same product accounts for all refunds
	•	Despite highest profit, it has the lowest profit margin → lower efficiency

⸻

Tools Used
	•	Power BI
	•	DAX
	•	Power Query
