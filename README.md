# campaigns
Python+SQL Campaign Analytics
readme_content = '''
# 📊 Marketing Campaign Analysis Using SQL and Python

## Project Overview
This project explores marketing campaign performance by analyzing a simulated database of customers, campaigns, and campaign results.  
The goal is to practice SQL querying, database management, and data visualization to extract actionable business insights for marketing optimization.

All analysis is performed using **Python**, **SQLAlchemy**, **Pandas**, and **SQLite** within a **Jupyter Notebook**.

## 📂 Project Structure
```
Marketing_Campaign_Analysis/
├── marketing_campaigns.db        # SQLite database with 3 tables
├── marketing_analysis.ipynb      # Jupyter Notebook with data analysis
├── README.md                     # Project description and instructions
├── requirements.txt              # Libraries used in the project
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
Feel free to connect on [LinkedIn](https://linkedin.com/in/yourprofile)!
'''
