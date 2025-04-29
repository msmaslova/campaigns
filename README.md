# 📊 Marketing Campaign Analysis Using SQL and Python

## Project Overview
This project explores marketing campaign performance by analyzing a simulated database of customers, campaigns, and campaign results.  
The goal is to practice SQL querying, database management, and data visualization to extract actionable business insights for marketing optimization.

All analysis is performed using **Python**, **SQLAlchemy**, **Pandas**, and **SQLite** within a **Jupyter Notebook**.

## 📂 Project Structure
## Project Structure
```
Marketing_Campaign_Analysis/
├── marketing_campaigns.db         # SQLite database
├── marketing_analysis.ipynb       # Jupyter Notebook with full analysis
├── images/                        # Folder with visualization images
│    ├── open_vs_click_rate.png
│    ├── top_campaigns.png
│    ├── top_customers.png
│    ├── funnel_analysis.png
│    ├── cohort_heatmap.png
│    ├── rfm_segmentation.png
├── README.md                      # Project documentation
├── requirements.txt               # List of used libraries
```

## 🛠 Technologies Used
- **Python** (Pandas, SQLAlchemy, Matplotlib, Seaborn, Faker)
- **SQLite** (Local Database)
- **Jupyter Notebook**

## 📋 Database Tables
| Table | Description |
|:------|:------------|
| `campaigns` | List of marketing campaigns with names, start dates, and budgets |
| `customers` | Information about customers (name, age, city) |
| `campaign_results` | Interaction records: opened, clicked, purchased |

## 🧐 Key Questions Answered
- What are the open and click rates for each campaign?
- Which marketing campaigns led to the most purchases?
- Who are the most active customers across campaigns?

## Key Analyses Conducted

### Funnel Analysis
We analyzed the customer journey from message delivery to final purchase. The funnel shows the drop-off at each stage (Opened, Clicked, Purchased).

![Funnel Analysis](images/funnel_analysis.png)

### Cohort Analysis
We grouped customers by the month of their first campaign interaction and tracked purchases over time. This reveals customer retention patterns and repeat purchase behavior.

![Cohort Heatmap](images/cohort_heatmap.png)

### RFM Analysis
We segmented customers based on Recency, Frequency, and Monetary value of their purchases. This helps identify Champions, Loyal Customers, and At-Risk segments.

![RFM Segmentation](images/rfm_segmentation.png)

### Basic Campaign Performance Metrics
We calculated Open Rates and Click Rates for each marketing campaign and identified the best-performing campaigns and most engaged customers.

![Open vs Click Rate](images/open_vs_click_rate.png)

![Top Campaigns](images/top_campaigns.png)

![Top Customers](images/top_customers.png)

## 📈 Key Insights
- Identified campaigns with the highest engagement rates.
- Highlighted campaigns that generated the most purchases.
- Found the top customers who engaged in multiple campaigns.
- Provided business recommendations based on customer behavior and campaign performance.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open `marketing_analysis.ipynb` in Jupyter Notebook.
4. Run the notebook to generate insights and visualizations.

## 📬 Contact
Created with ❤️ by Mariia Maslova  
Feel free to connect!
'''
