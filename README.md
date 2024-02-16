## AI READER = ARTICLE SUMMARIZER
AI Reader is a Flask web application that allows users to input a URL of an article, which is then summarized and displayed back to the user. The application uses web scraping to extract the content from the supplied URL and natural language processing techniques to generate a summary of the article.

### Installation
---
    git clone the repo
---
create a virtual environment
---
    python -m venv env
    source env/bin/activate
---
install the required dependencies
---
    pip install Flask, requests beautifulsoup4 nltk networkx numpy
---

#### Run the flask app 

---
    python3 app.py
---

#### Access the application in your web browser
---
    http://127.0.0.1:5000/
---

### Usage
Enter the URL of an article in the input field on the homepage.

Click the "Summarize" button to generate a summary of the article.

The summarized content will be displayed on the page.
