# FinFeed - The Financial News Pulse

FinFeed is a Python-based financial news aggregator project. FinFeed collects news articles from popular financial news websites and performs sentiment analysis on them. FinFeed then providing users with aggregated news along with sentiment analysis scores and keyword tagging.

FinFeeds aim is to help users stay informed about financial news and trends, enabling them to make more informed investment decisions.

## Features

- **Web Scraping** - Utilizes Python web scraping libraries to extract financial news articles from popular financial news websites.
- **Sentiment Analysis** - Implements natural language processing (NLP) techniques for sentiment analysis of news articles, providing users with insights into the sentiment associated with each news article.
- **Keyword Tagging** - Tags news articles with relevant keywords, allowing users to quickly identify articles of interest.
- **Friendly User Interface (UI)** - Provides a friendly UI to display aggregated news articles, sentiment analysis scores, and keyword tagging.

## Technical Stack

- **Python** - Used for the backend.
- **BeautifulSoup** - Python library used for web scraping to extract information from HTML files.
- **Natural Language Toolkit (NLTK)** - Python library used for natural language processing tasks such as sentiment analysis.
- **Flask** - Used for serving the application.
- **HTML/CSS/JS** - Used for designing and styling the UI.
- **SQLite** - Used for storing metadata about collected news articles.

## Installation

1. Clone the repository: `git clone <url>`
2. Navigate to the project directory: `cd <project_dir>`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python3 app.py`
5. Access the application in your web browser at `http://localhost:5000`

## Usage

- Upon accessing the application, users can view aggregated financial news articles along with sentiment analysis scores and keyword tagging.
- Users can search for specific keywords or topics to filter news articles.
- Clicking on a news article will display more details and sentiment analysis for that article.
