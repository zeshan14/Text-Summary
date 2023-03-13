Text - Summary 🗒 

This project will take a story/big paragraph as an input and gives out the summary of it. The NLP libraries used in this project break down the text into individual tokens, label each token with its part of speech, identify named entities, analyze sentence structure, determine emotional tone, and assign scores to sentences based on importance and relevance. Ultimately, these libraries are crucial in generating summaries that highlight key entities, capture the overall mood of the content, and select the most critical sentences for inclusion in the summary.

🗄 Table of Contents
app.py 
text_summary.py
index.html
design.css
summary.html

Packages needed
from Flask import flask
import spacy
from spacy.lang.en.stop_words import STOP_WORDS
from string import punctuation 
from heapq import nlargest

💻 Steps to execute
1. Define and implement the text summarization algorithm in text_summary.py.
2. Define the Flask server and routes in app.py, which will handle the incoming requests from the user interface.
3. Create the HTML templates for the user interface, including the main page (index.html) and the summary page (summary.html), and style the templates using design.css.
4. In app.py, define functions that render the HTML templates and process user input, calling the text summarization algorithm implemented in text_summary.py.
5. Run the Flask server by running app.py.
6. Access the web application by opening a web browser and navigating to the appropriate URL (e.g., http://localhost:5000).
7. Interact with the user interface by entering text and submitting it to the server for text summarization.
8. View the summary output on the summary page (summary.html).
