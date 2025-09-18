
# Arabic Tweet Moderation & Analysis with Gemini API

This project is built to collect Arabic tweets, preprocess them, and analyze them using the Google Gemini API.
The main objectives are:
- Content Moderation → detect harmful vs. safe tweets.
- Sentiment Analysis → classify tweets as positive, negative, or neutral.
- Named Entity Recognition (NER) → extract people, places, and organizations from text.

## Tools

* Python
* Selenium 
* Camel Tools 
* NLTK
* Googletrans / Deep Translator
* Gemini API
* Pandas, Regex, Emoji


## Usage

1. Set scraping parameters in the notebook:
SINCE_TOTAL = '2025-06-01'
UNTILL_TOTAL = '2025-09-18'
LANG = "ar"
PERIOD_DAYS = 1
Email = your email
User Name = your user name
Password = your password

2. Run scraping → collect tweets into a dataset.

3. Preprocess text → cleaning, tokenization, lemmatization, removing diacritics.

4. Call Gemini API → run.

## Outputs

- Cleaned dataset of Arabic tweets.
- Moderation results (safe/harmful classification).
- Sentiment analysis results.
- NER outputs with detected entities.

