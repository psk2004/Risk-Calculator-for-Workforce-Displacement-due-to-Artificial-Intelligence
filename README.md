# 🌐 AI Workforce Risk & Opportunity Calculator (2020-2026)

An interactive data tool built with **Python** and **Streamlit** that analyzes global workforce displacement risks and the economic "wage premium" of AI upskilling across 10+ industry sectors.

## Project Overview
This project bridges the gap between raw data analysis and actionable business intelligence. It uses a global dataset to project automation risks and displacement percentages through 2026, while highlighting the salary incentives for workers who transition into AI-augmented roles.

## Repository Structure
* **`workforce_displacement.ipynb`**: The "Research & Development" phase. Contains the full data pipeline, including:
    * Analytical cleaning (reducing dimensionality from 23 to 21 high-impact features).
    * Exploratory Data Analysis (EDA) on automation trends.
    * Feature engineering for the predictive logic.
* **`workforce_displacement.py`**: The "Production" script. A clean, optimized Python file that powers the interactive Streamlit dashboard.
* **`cleaned_workforce_data.csv`**: The refined dataset used for high-performance app retrieval.

## Key Features
* **Predictive Risk Modeling:** Calculates automation probability based on industry and national income group.
* **Upskilling Insight:** Dynamically calculates the average "AI Wage Premium" to show the financial benefit of technical adaptation.
* **Global Scope:** Analyzes trends across diverse regions and income levels, from High-Income to Lower-Middle-Income nations.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Streamlit, Matplotlib, Seaborn
* **Environment:** Google Colab & Localtunnel for cloud-based deployment

## Dashboard Preview
<img width="1115" height="682" alt="AI Workforce Risk Calculator" src="https://github.com/user-attachments/assets/d8d93bae-c1f9-4c90-bcda-3eb8470e6d79" />
