# Garanti Chatbot Project

Project Purpose

The primary goal of this project is to automatically scrape the Frequently Asked Questions (FAQ) section of any website, store the scraped questions and answers in JSON format as a dataset, and use this dataset to build a chatbot powered by Large Language Models (LLMs). The chatbot enables users to ask variations of the scraped FAQ questions and provides the correct answer along with the intended question, leveraging the capabilities of LLMs.

As an example, this project includes a chatbot developed using the FAQ data scraped from Garanti Bank’s website.

Features

Web Scraping: Automatically collects FAQ questions and answers from a website.

JSON Dataset: Stores the scraped questions and answers in JSON format.

RAG (Retrieval-Augmented Generation): The chatbot uses the dataset to predict the correct answer and the most relevant question.

Embedding Technology: Extracts semantic meanings from questions and answers for accurate matching and retrieval.

User Interface (UI): A modern and user-friendly web interface for interacting with the chatbot.

Unit Testing: Ensures the correctness and reliability of the implemented functions.

Technologies Used

Python: The primary programming language of the project.

Flask: Used to build the web interface of the chatbot.

BeautifulSoup and Requests: Libraries used for web scraping.

LLM (Large Language Models): Used to understand and predict the most relevant answers.

Faiss: A library for indexing and searching embeddings.

HTML, CSS, and JavaScript: For designing and implementing the web interface.

Pytest: A library for writing unit tests.
