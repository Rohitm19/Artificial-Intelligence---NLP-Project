# Sentiment Analysis of News Headlines Using GDELT and NLP

## Project Overview

This project focuses on analyzing the sentiment of global news headlines using the **GDELT Project's Global News API**. The objective is to collect historical news data across various topics such as finance, business, health, and environment, and perform sentiment analysis to uncover patterns and correlations. A special focus is placed on examining the relationship between financial and business news to determine if one influences the other.

### Key Features:
- **Data Collection**: Gather historical headlines from multiple sources using the GDELT API.
- **Sentiment Analysis**: Utilize Natural Language Processing (NLP) techniques to assess the tone and sentiment of articles.
- **Visualization**: Create time-series graphs and correlation plots to showcase insights.
- **Tone Filtering**: Analyze articles based on tone thresholds (positive/negative or emotional intensity).
  
---

## Tools and Technologies
- **Programming Language**: Python
- **Data Processing**: Pandas, JSON
- **API Integration**: GDELT Global News API
- **Logging**: Python's logging module
- **Storage**: CSV files
- **Visualization**: Matplotlib, Seaborn
- **NLP**: Natural Language Toolkit (NLTK) for sentiment analysis

---

## Installation and Setup

### Prerequisites
- Python 3.x installed
- Libraries: `requests`, `pandas`, `matplotlib`, `seaborn`, `nltk`

### Steps to Set Up the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-headlines.git
   cd sentiment-analysis-headlines
