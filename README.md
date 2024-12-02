# Stock-Movement-Analysis
 Telegram Stock Sentiment Analyzer

Overview
This project extracts messages from Telegram stock-related channels, performs sentiment analysis, and uses the insights to predict stock movements. It leverages natural language processing (NLP) and machine learning for predictions.

1.Prerequisites
Ensure the following dependencies are installed:
Python 3.8 or later
Required Python libraries:
asyncio
os
re
nest_asyncio
Telethon
textblob
vaderSentiment
pandas
scikit-learn
You can install the required libraries using the command:
        pip install telethon textblob vaderSentiment pandas scikit-learn nest-asyncio

2. Telegram API Setup
Go to the Telegram API Development Tools and log in.
Create a new application and note down:
API_ID
API_HASH

3.Configuration
Update the following placeholders in the script:
        api_id: Your Telegram API ID (integer).
        api_hash: Your Telegram API Hash (string).
        phone_number: Your Telegram phone number (including country code).
        channel_username: The username of the Telegram channel to scrape messages from.

4. Running the Script
Save the script file (e.g., telegram_stock_analyzer.py).
Open your terminal or Jupyter Notebook.
If you're using Jupyter Notebook, ensure nest_asyncio is applied.

Follow the prompts for logging into Telegram:
Enter the code sent to your Telegram app.
The script will then scrape messages from the specified channel.
