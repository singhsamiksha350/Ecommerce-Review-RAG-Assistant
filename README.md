# Ecommerce-Review-RAG-Assistant

## Overview
An AI-powered Retrieval-Augmented Generation (RAG) application designed to analyse customer reviews from the Women's E-Commerce Clothing Reviews dataset.

The project combines semantic search, natural language processing, and Generative AI to retrieve relevant customer feedback and generate context-grounded insights.

## Tech Stack
- Python
- Pandas and NumPy
- Sentence Transformers (all-MiniLM-L6-v2)
- Google Gemini API
- Matplotlib
- Google Colab

## Key Features
- Customer review data cleaning and preprocessing
- Local semantic embeddings
- Similarity-based review retrieval
- Gemini-powered question answering
- Source review ID references
- Customer sentiment and rating analysis
- Department-wise rating insights

## Architecture
1. Customer reviews are cleaned and preprocessed.
2. Sentence Transformers generates local embeddings.
3. Relevant reviews are retrieved using semantic similarity.
4. Retrieved reviews are passed to the Gemini API.
5. Gemini generates answers grounded in the retrieved reviews.

## Dataset
Women's E-Commerce Clothing Reviews dataset.

## How to Run
1. Open the notebook in Google Colab.
2. Add your Gemini API key to Colab Secrets as `GEMINI_API_KEY`.
3. Upload the dataset CSV when prompted.
4. Run the notebook cells in order.

**Note:** The dataset is not included in this repository. Embeddings are generated locally, while Gemini is used for answer generation.
