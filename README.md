# ai-financial-market-analysis
AI Financial Analytics • Market Insights • Time-Series Analysis • Revenue Forecasting • R&amp;D Spending Analysis
AI Financial & Market Data Analysis (2015–2024)
A 10-year analytics project exploring how AI R&D, revenue, and innovation events influence market behavior.
📌 Project Overview

This project analyzes daily AI, financial, and market data for OpenAI, Google, and Meta from 2015 to 2024.

The dataset includes:

AI R&D Spending (USD millions)

AI Revenue & Revenue Growth %

Major AI Events (GPT releases, Bard, LLaMA, Gemini, DALL·E 2, etc.)

Daily Stock Impact %

10 years of time-series data (10,959 rows)

Goal

To understand how AI investment + product innovation correlate with revenue growth and market reactions.

This project is designed to demonstrate real-world data analysis, financial interpretation, visualization, and insight storytelling.

📦 Dataset

File: ai_financial_market_daily_realistic_synthetic.csv
Rows: 10,959
Period: 2015–01–01 to 2024–12–31
Companies: OpenAI, Google, Meta

Key Columns

Date

Company

R&D_Spending_USD_Mn

AI_Revenue_USD_Mn

AI_Revenue_Growth_%

Event

Stock_Impact_%

⚠️ Synthetic but highly realistic dataset for analytics & portfolio demonstration.

🧠 Key Business Questions

This project answers:

Which company invested the most in AI?

How does AI revenue compare across companies?

What events caused the strongest market reactions?

How did AI revenue growth evolve over 10 years?

What correlations exist between spending, revenue, growth, and stock impact?

📊 Main Findings
1. Total Investment (2015–2024)

Google: ~$423B

Meta: ~$265B

OpenAI: ~$27B

2. Total AI Revenue

Google: ~$285B

Meta: ~$190B

OpenAI: ~$9.5B

3. Correlations

R&D → Revenue correlation: 0.94 (very strong)

Revenue Growth → Revenue: moderate correlation

Stock Impact → Weak correlation (market reacts more to events)

4. Event Impact

Major AI releases correspond with noticeable stock impact shifts.

📈 Visualizations
🔹 R&D vs AI Revenue

🔹 AI Revenue Growth Trend

🔹 Correlation Heatmap

📓 Notebook Summary

The notebook includes:

✔ Data loading & cleaning

Parsing dates

Handling missing values

Creating Year column

Splitting company-level subsets

✔ Exploratory Data Analysis

R&D totals

Revenue trends

Growth rates

Stock impact line charts

Event-based filtering

Correlation heatmaps

✔ Insight extraction

Top events by stock impact

Year-over-year performance

Company comparisons

🛠 Tech Stack

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

🚀 How to Run the Project
1. Clone the repo
git clone https://github.com/<your-username>/ai-financial-market-analysis.git
cd ai-financial-market-analysis

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
jupyter notebook



⚠️ Known Limitations

Dataset is synthetic

Original notebook used absolute paths (fixed using relative paths)

Market reaction is correlational, not causal

📌 Future Improvements

Add time-series forecasting

Build an interactive dashboard (Power BI / Tableau / Streamlit)

Add event-window stock analysis (−3 to +3 days)

Add automated data integrity tests

🤝 About Me

This project demonstrates my skills in:

Financial & market data analysis

Insight-driven storytelling

Time-series analysis

Data visualization

Turning business questions into analytics

I’m actively looking for Data Analyst, Business Analyst, and Marketing Analytics opportunities.
