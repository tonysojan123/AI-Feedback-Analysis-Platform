AI-Powered User Feedback Analysis Platform
Project Overview
This project is a proof-of-concept platform designed to help product managers understand user feedback from app store reviews. It uses natural language processing (NLP) to perform sentiment analysis and unsupervised topic modeling, transforming thousands of raw reviews into actionable insights. The final output is a design for an interactive dashboard that visualizes these key insights.

Key Features
Data Scraping: Collects app reviews directly from the Apple App Store.

Sentiment Analysis: A machine learning model classifies reviews as either "Positive" or "Negative" with over 91% accuracy.

User Pain Point Discovery: Unsupervised topic modeling (LDA) automatically identifies and groups the main themes and complaints within negative reviews.

Dashboard Design: A high-fidelity dashboard mockup created in Figma, tailored for a product manager to easily view sentiment trends and the top user pain points.

Technologies Used
Programming Language: Python

Data Science Libraries: Pandas, Scikit-learn, NLTK

Web Scraping: app-store-web-scraper

Design Tool: Figma

Project Walkthrough
The project is contained within the main Jupyter Notebook (untitled.ipynb). The key steps are:

Data Collection: Scraped 500+ reviews for the "YouCam Perfect" app.

Data Preparation: Labeled reviews based on star ratings (1-2 stars = Negative, 4-5 stars = Positive).

Text Preprocessing: Cleaned and normalized the text data by lowercasing, removing punctuation, tokenizing, removing stop words, and lemmatizing.

Sentiment Model Training: Trained a Logistic Regression classifier on TF-IDF vectors, achieving 91.5% accuracy on the test set.

Topic Modeling: Applied Latent Dirichlet Allocation (LDA) to the negative reviews to discover 5 key user pain points, including issues with subscriptions, free trials, and paid features.

Dashboard Mockup
The final insights are designed to be displayed in a dashboard for product managers.
