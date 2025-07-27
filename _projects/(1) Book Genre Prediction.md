---
name: Book Genre Prediction
tools: [Python, beautifulsoup, Scikit-learn]
image: https://cdn-icons-png.flaticon.com/512/2232/2232688.png
description: A text classification project that predicts book genres using web scraping and machine learning, achieving 92% accuracy on real-world book descriptions.
---

# Book Genre Prediction

**Book Genre Prediction** is a machine learning project where I scraped over 10,000 book entries from Goodreads to classify them into **fiction** or **non-fiction** based on their descriptions. The goal was to explore how natural language processing and classification models can enhance digital library systems and bookstore categorization.

![preview](https://miro.medium.com/v2/0*Y233bh8widEIPLpn.png)

## How it Works

- Scraped book metadata and descriptions using `requests` and `BeautifulSoup`
- Cleaned and tokenized text data using `NLTK`
- Trained multiple classifiers (Logistic Regression, SVM, Random Forest)
- Achieved up to **92% accuracy** on unseen data
- Built a prototype using Streamlit to allow genre prediction based on custom input

<!-- <p class="text-center">
{% include elements/button.html link="https://github.com/yourusername/book-genre-prediction" text="Learn More" %}
</p> -->
