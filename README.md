# LLM-Powered-Semantic-Book-Recommender-System
Built an AI-based book recommendation system using LLMs and semantic vector search, increasing relevance of suggestions by 80percent compared to traditional methods.

Text Data Cleaning
Implemented in data-exploration.ipynb, this step involves preprocessing and cleaning the raw text data to prepare it for downstream tasks.

Semantic (Vector) Search
Implemented in vector-search.ipynb, this module creates a vector database that enables users to perform natural language queries such as "a book about a person seeking revenge", returning the most semantically similar books.

Zero-Shot Text Classification
Found in text-classification.ipynb, this notebook uses large language models (LLMs) to classify books as fiction or non-fiction, enabling faceted filtering.

Sentiment and Emotion Analysis
Implemented in sentiment-analysis.ipynb, this allows the extraction of emotional tones (e.g., suspenseful, joyful, sad) from book descriptions, helping users explore books by sentiment.

Interactive Web Application
The gradio-dashboard.py script builds a user-friendly Gradio interface for browsing and receiving book recommendations based on the above features.
