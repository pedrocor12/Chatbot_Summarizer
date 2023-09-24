# Chatbot Summarizer README

## Overview

Chatbot Summarizer is a powerful application that lets users upload documents in various formats like PDF, DOCX, or TXT. It then chunks and embeds the document, allowing users to ask questions about the content, and get accurate and concise answers.

## Features
- **Multiple Document Formats**: Supports PDF, DOCX, and TXT files.
- **Dynamic Chunking**: Allows users to specify the chunk size for processing.
- **Embeddings**: Uses OpenAI embeddings for accurate text representation.
- **Ask Questions**: Users can ask questions about their uploaded content.
- **Embedding Cost Calculator**: Calculates the embedding cost based on the document's content.
- **Chat History**: Retains a history of asked questions and their respective answers for reference.

## Requirements
- OpenAI API Key: For using the OpenAI embeddings.
- Dependencies: You need to have the required Python libraries mentioned in the code, such as `streamlit`, `tiktoken`, `dotenv` and others.

## Setup & Run

1. **Environment Variables**:
   - Ensure you have a `.env` file with the required API keys or provide them directly in the Streamlit interface.
   - Use the `OPENAI_API_KEY` variable for the OpenAI API key.

2. **Installation**:
   ```bash
   pip install streamlit tiktoken python-dotenv
   
   or

   pip3 install -r requirements.txt
   
   # Install other dependencies as required.I was using python3.11.1 while working in this project
   ```

3. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Launch the Streamlit application.
2. Enter your OpenAI API Key in the sidebar.
3. Upload the document you want to analyze.
4. Set your preferred chunk size.
5. Add your data, and wait for it to process.
6. Ask questions related to the uploaded content in the provided text box.
7. Get concise answers instantly.
8. View the chat history to track your questions and their respective answers.

## Links

- Project repository: [https://github.com/pedrocor12/Chatbot_Summarizer]
  
## Project running 

![image](https://github.com/pedrocor12/Chatbot_Summarizer/assets/57505565/f6d93038-efbf-4191-bbe8-6d50b648ddc3)

## Question , answer and chat history with previous questions

While diving into the 80-page GDPR regulation, I found myself wishing for an easier way to get to the heart of such a lengthy document. That's when the idea hit me: what if there was a tool that could quickly summarize big documents, highlighting the key points? With that spark of inspiration, I decided to create this application to help others, like myself, save time and get straight to the essentials. However, any document can be used , I will be adding more functionality to support wikipedia search and other types of documents in the future.

![image](https://github.com/pedrocor12/Chatbot_Summarizer/assets/57505565/d240881e-5058-4536-9651-19bc93a51eeb)


