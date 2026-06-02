# BusinessIQ v5 – AI-Powered Business Analytics Assistant

## Overview

BusinessIQ v5 is an AI-powered business analytics assistant built with n8n, Telegram, Google Sheets, and Google Gemini.

The system allows business owners and managers to ask natural-language questions through Telegram and receive instant insights about sales performance, revenue, products, categories, cities, and staff performance.

## Features

- AI-powered business analytics
- Telegram chat interface
- Google Sheets as data source
- Automated sales analysis
- Revenue tracking
- Product performance analysis
- Category performance analysis
- City-wise revenue analysis
- Cashier performance ranking
- Business recommendations engine
- Executive business summaries

## Example Questions

- What is the total revenue?
- What is the top selling product?
- Which product generated the highest revenue?
- Who is the best cashier?
- Which city generated the highest revenue?
- Which category generated the most revenue?
- Show top 5 products.
- Show monthly sales.
- Give me a business summary.
- What are your recommendations?

## Workflow Architecture

Telegram Trigger
→ Google Sheets
→ Analytics Engine (Code Node)
→ Recommendation Engine (Code Node)
→ AI Agent (Google Gemini)
→ Telegram Response

## Analytics Engine

The Analytics Engine calculates:

- Total Revenue
- Total Quantity Sold
- Top Selling Product
- Highest Revenue Product
- Best Cashier
- Top Revenue City
- Top Category
- Best Month
- Top 5 Products
- Category Revenue Breakdown
- Monthly Revenue Breakdown

## Recommendation Engine

The Recommendation Engine generates business recommendations based on sales performance.

## Technology Stack

- n8n
- Telegram Bot API
- Google Sheets
- Google Gemini AI
- JavaScript
- AI Agent Node
- Code Node

## Future Improvements

- Inventory Management Assistant
- Revenue Trend Analysis
- Sales Forecasting
- Multi-Store Support
- PostgreSQL Integration
- Executive Dashboard
- Daily Automated Reports
- AI Memory

## Author

Tasdiq Ayub

Electrical Engineer | Automation & AI Workflow Builder
