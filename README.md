# AI Document Summarizer

A simple and efficient web application that summarizes large text files, PDFs, and blog content using the LLaMA 3 model via the Groq API.
Built with [LangChain](https://www.langchain.com/), [Streamlit](https://streamlit.io/), and [Groq](https://groq.com/).

## Live App
https://amnarehan-ai-summarizer-app-z6apuh.streamlit.app/

## Features
- Upload `.pdf`, `.txt`, or `.csv` files
- Automatically chunk and summarize content using a large language model
- Responsive and user-friendly interface built with Streamlit
- Fast and efficient responses powered by Groq's LLaMA 3 model

## Tech Stack
- **Frontend & Backend:** Streamlit
- **Language Model Integration:** LangChain with Groq API
- **Text Chunking:** `CharacterTextSplitter` from LangChain
- **Deployment:** Streamlit Cloud
