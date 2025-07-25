# price_pridiction
Predicting Stock Price Movements with News Sentiment
This project analyzes the relationship between financial news sentiment and stock price movements using the Financial News and Stock Price Integration Dataset (FNSPID).
It integrates Natural Language Processing (NLP) for sentiment analysis and technical indicators (Moving Average, RSI, MACD) to discover how news tone affects stock returns.

Project Objectives
Perform sentiment analysis on financial news headlines.

Calculate technical indicators (MA, RSI, MACD) for selected stocks.

Compute daily stock returns and analyze their correlation with sentiment scores.

Provide actionable insights for predictive analytics and investment strategies.

Key Features
Exploratory Data Analysis (EDA): Publisher activity, sentiment distribution, and publication trends.

Technical Analysis: Moving Average, RSI, and MACD calculations.

Sentiment Analysis: Headline polarity scoring using TextBlob.

Correlation Analysis: Pearson correlation between sentiment and daily returns, with heatmap & scatterplots.

Folder Structure
bash
Copy
Edit
├── data/                   # Datasets (financial news + stock prices)
├── notebooks/              # Jupyter notebooks for EDA & analysis
├── scripts/                # Modular Python scripts
├── tests/                  # Unit tests
├── .github/workflows/      # CI/CD setup
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
└── report.pdf              # Final project report
Setup Instructions
Clone the repository:


git clone <your-repo-url>
cd price-prediction-
Create a virtual environment:

python -m venv .venv
source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
Install dependencies:


pip install -r requirements.txt
Usage
Run EDA:


jupyter notebook notebooks/eda.ipynb
Run technical & correlation analysis:


jupyter notebook notebooks/technical_analysis.ipynb
Results
Correlation: Positive correlation between sentiment scores and daily stock returns.

Visuals: Heatmap of correlations and scatterplots (sentiment vs returns).

Report: Final Academic Report

