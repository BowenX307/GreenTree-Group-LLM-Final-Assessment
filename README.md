# GreenTree-Group-LLM-Final-Assessment

## Employee Sentiment & Engagement Analysis
This project analyzes employee communication data to assess sentiment trends, detect disengagement risk, and predict emotional patterns over time using natural language processing (NLP) and statistical modeling.

## Project Overview
Using a dataset of internal employee messages, we perform:
- **Sentiment Labeling** using VADER
- **Exploratory Data Analysis (EDA)** to visualize trends and message behavior
- **Monthly Sentiment Scoring** and employee-level engagement ranking
- **Flight Risk Identification** based on negative message patterns
- **Predictive Modeling** using linear regression (trend over time, message length, and message frequency)

## How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
2. Run sentiment labeling and cleaning:
   ```bash
   python sentiment_labeling.py
4. Run predictive modeling：
   ```bash
   python task6_predictive_modeling.py
## Methodology

We began by cleaning and combining the message subject and body text, then applied the VADER sentiment analysis tool to label each message as Positive, Neutral, or Negative. After labeling, we conducted exploratory data analysis (EDA) to uncover patterns in message frequency, sentiment distribution, and employee engagement over time. Monthly sentiment scores were calculated for each employee and used to rank engagement. A sliding 30-day window was applied to identify flight risk behavior based on repeated negative messaging. Finally, we developed several linear regression models to explore and predict sentiment trends using time, message length, and message frequency as features.

## Key Findings

1. Positive messages tend to be longer and more expressive.
2. Employees who send 4+ negative messages within 30 days are flagged as flight risks.
3. Message frequency and emotional composition are strong predictors of sentiment trends.
4. Individual sentiment varies too much to model accurately with time alone.

## Author
BowenXiao, 2025
