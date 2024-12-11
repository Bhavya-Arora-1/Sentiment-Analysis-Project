

# Sentiment Analysis Project

## Overview
This project focuses on **Sentiment Analysis** to classify sentiments expressed in textual data. It was developed as part of a Data Science certification course. The primary objective is to analyze public sentiment, particularly in the context of the Omicron variant, by processing real-time data from **Twitter**.

## Features
- **Real-time Data Fetching**: Utilizes Twitter's API to fetch real-time tweets.
- **Data Preprocessing**: Cleans and preprocesses textual data for analysis.
- **Machine Learning Models**: Implements classification models to predict sentiment (e.g., positive, neutral, negative).
- **Visualization**: Provides visual insights into sentiment distributions and trends.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK, Tweepy
- **Machine Learning**: Supervised learning algorithms for classification tasks
- **APIs**: Twitter API for data retrieval

## Prerequisites
- Python 3.8+
- Twitter Developer Account (for API keys)

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/Bhavya-Arora-1/sentiment-analysis.git
   cd sentiment-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Add your Twitter API credentials in the `config.py` file:
   ```python
   API_KEY = 'your-api-key'
   API_SECRET_KEY = 'your-api-secret-key'
   ACCESS_TOKEN = 'your-access-token'
   ACCESS_TOKEN_SECRET = 'your-access-token-secret'
   ```

4. Run the notebook:
   ```bash
   jupyter notebook Sentiment_Analysis_Bhavya_Arora.ipynb
   ```

## Results
- Sentiment predictions on real-time tweets.
- Visualizations showcasing sentiment trends over time.

## Contributions
Feel free to fork this repository, submit issues, or open pull requests for enhancements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

