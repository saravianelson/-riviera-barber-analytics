# 💈 Riviera Barber — Operational Analytics 
Author: Nelson Saravia
Business: Riviera Barber — Independent barbershop station within Filo Salon, Playa del Carmen, MX
Stack: Python · pandas · matplotlib · seaborn
Status: 🟢 Live — updated weekly with real operational data

## 🧭 Business Context 
Riviera Barber is my own independent barbershop business. I am simultaneously the owner and the analyst.
This project applies a real data analysis pipeline to real operational decisions:

Revenue patterns — which days and services generate the most?
Client retention — who are my best clients and how often do they return?
Operational KPIs — a Monday morning dashboard that guides the week ahead

Every row in this dataset is a real service performed. Every insight drives a real business decision.

Commission structure: Nelson 60% · Business 40% · Tips 100% to barber


## 🚀 What This Project Solves 

Dirty data pipeline: Automated parsing of manual Google Sheets entries (currency symbols, date gaps, separator rows)
Financial logic: Automatic commission recalculation at correct 60/40 split
Business KPIs: Weekly dashboard with Avg Ticket, Revenue by Day, and Retention Rate
Client segmentation: Loyalty tiers — One-time, Returning, Loyal — with revenue attribution per tier
Auto-generated insights: Data-driven recommendations expressed in business language, not just metrics


## 🛠️ Stack 

Python — pandas, seaborn, matplotlib
Google Sheets — operational data source (CAJA, CLIENTES, CIERRE tabs)
Google Colab — development environment
Git/GitHub — version control and Agile project management


## 📁 Project Structure 
riviera-barber-analytics/
│
├── notebooks/
│   └── riviera_barber_analytics.ipynb   # Main pipeline
├── data/
│   └── raw/                             # Weekly CSV exports from Google Sheets
├── .gitignore
├── requirements.txt
└── README.md

## 📈 Roadmap 

 Client churn prediction model (Loyal vs. At-Risk segmentation)
 Demand forecasting for shift optimization
 Interactive Streamlit dashboard
 Power BI integration for non-technical reporting


## 🗂️ Project Board 
Follow the progress of this and other portfolio projects:
https://github.com/users/saravianelson/projects/2

*Nelson Saravia* — Data Analyst
