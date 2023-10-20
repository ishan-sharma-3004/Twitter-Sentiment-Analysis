# Twitter-Sentiment-Analysis
Twitter Sentiment Analysis
This project demonstrates how to perform sentiment analysis on twitter data by leveraging various technologies and tools. It involves collecting real time twitter data using the twitter API, processing and analyzing with NLTK, and stroring the results in a postgresql database via Apache kafka.
## Tech Stack
* NLTK-Natural language toolkit: NLTK is used for natural language processig, tokenizing and sentiment analysis of tweets.
* Twitter API and tweepy: we utilize the twitter API to access twitter data and tweepy, a python library to interact with API.
* Apache Kafka:Kafka serves as the message broker and data streaming platform, facilitating the real-time data flow from the twitter API to the database.
* PostgreSQL: PostgreSQL is the relational database used for strong and managing the Twitter data, including the sentiment analysis results.

## Setup Instructions:
* Environment Setup: Start with python setup from the website 'https://www.python.org/downloads'
* Twitter API access: You will need twitter API access. Create a twitter developer account and obtain access keys, tokens, and secrets.
* Kafka installation: install and configure kafka. setup a kafka topic to ingest twitter data.
* Database: Create a postgresql database to store the collected twitter data and sentiment analysis results.
* Database connection: Configure the connection to your postgreSQL database using psycopg2. Update the database credentials in the code.
* NLTK configuration: Ensure NLTK is setup with necessary corpora and models for sentiment analysis.
