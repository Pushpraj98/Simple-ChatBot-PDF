# Simple-ChatBot-PDF
This is a simple PDF reader chatbot which is wok on the Open Ai tool  using streamlit library and  python.This is a Python application that allows you to load a PDF and ask questions about it using natural language. The application uses a LLM to generate a response about your PDF
# How It works?
The application reads the PDF and splits the text into smaller chunks that can be then fed into a LLM. It uses OpenAI embeddings to create vector representations of the chunks. The application then finds the chunks that are semantically similar to the question that the user asked and feeds those chunks to the LLM to generate a response.

The application uses Streamlit to create the GUI and Langchain to deal with the LLM.
#Installation
To install the repository, please clone this repository and install the requirements:
pip install -r requirements.txt

#Usage
To use the application, run the main.py file with the streamlit CLI (after having installed streamlit):

streamlit run app.py
