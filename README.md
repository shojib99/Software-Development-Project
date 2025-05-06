Real Cat is a smart, AI-powered web application that detects plagiarism, identifies AI-generated content, and extracts text from images using Optical Character Recognition (OCR). Built with Streamlit, it provides an intuitive interface for educators, content creators, and researchers to analyze text in real-time and track analysis history with MySQL database integration.

Features:
Plagiarism Detection: Compares input text with a reference using TF-IDF and cosine similarity.

AI-Generated Content Detection: Uses NLP models (like roberta-base-openai-detector) to check if the content is AI-written.

Image OCR: Extracts text from uploaded images using Tesseract OCR.

Human-Written Scoring: Calculates the confidence level of human authorship based on AI and plagiarism metrics.

History Logging: Saves all analyses in a MySQL database for future reference.

Interactive UI: Simple and clean interface built with Streamlit.

Technologies Used:
Python

Streamlit

Tesseract OCR (via pytesseract)

Hugging Face Transformers (pipeline)

Scikit-learn (TF-IDF + cosine similarity)

MySQL for database storage

NLTK for text preprocessing














Software Development Project
Author : Md. Shojib Sheikh

