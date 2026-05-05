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

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/pranavKarthikCu/LLM-Powered-Semantic-Book-Recommender-System.git
cd LLM-Powered-Semantic-Book-Recommender-System
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebooks (in order)
Open and run the notebooks sequentially to prepare the data and build the vector database:
1. `data-exploration.ipynb` — Clean and preprocess the data
2. `vector-search.ipynb` — Build the vector database
3. `text-classification.ipynb` — Classify books as fiction/non-fiction
4. `sentiment-analysis.ipynb` — Extract sentiment and emotion tags

### 4. Launch the Web App
```bash
python gradio-dashboard.py
```
Then open your browser and go to: **http://127.0.0.1:7860**

---
## Requirements
- Python 3.11+
- See `requirements.txt` for all dependencies

![image](https://github.com/user-attachments/assets/69072e1e-b0a7-4b6d-b328-cd8b973ee3fe)
