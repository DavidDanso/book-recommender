# Build a Semantic Book Recommender with LLMs

Welcome to the **Semantic Book Recommender** project repository! This repository contains all the code and resources needed to, *"Build a Semantic Book Recommender with LLMs."* This repo walks you through building an intelligent book recommendation system powered by large language models (LLMs).

## Course Overview
This project consists of five main components:

1. **Text Data Cleaning**  
   Learn how to preprocess and clean text data to ensure better model performance.  
   📄 Notebook: `data-exploration.ipynb`

2. **Semantic Search and Vector Database**  
   Build a vector database and use semantic search to find books similar to natural language queries, such as "a book about a person seeking revenge."  
   📄 Notebook: `vector-search.ipynb`

3. **Text Classification with Zero-Shot Learning**  
   Use zero-shot classification with LLMs to categorize books as "fiction" or "non-fiction." This enables users to filter books based on categories.  
   📄 Notebook: `text-classification.ipynb`

4. **Sentiment Analysis and Emotion Extraction**  
   Perform sentiment analysis using LLMs to determine the tone of books (e.g., suspenseful, joyful, or sad). This allows users to sort books by their emotional impact.  
   📄 Notebook: `sentiment-analysis.ipynb`

5. **Gradio Web Application**  
   Create an interactive web application with Gradio where users can input queries and receive book recommendations.  
   📄 File: `gradio-dashboard.py`

---

## Project Requirements
This project was developed using **Python 3.12**. Below are the required dependencies:

- [kagglehub](https://pypi.org/project/kagglehub/)
- [pandas](https://pypi.org/project/pandas/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [seaborn](https://pypi.org/project/seaborn/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)
- [langchain-community](https://pypi.org/project/langchain-community/)
- [langchain-opencv](https://pypi.org/project/langchain-opencv/)
- [langchain-chroma](https://pypi.org/project/langchain-chroma/)
- [transformers](https://pypi.org/project/transformers/)
- [gradio](https://pypi.org/project/gradio/)
- [notebook](https://pypi.org/project/notebook/)
- [ipywidgets](https://pypi.org/project/ipywidgets/)

A `requirements.txt` file is provided in the repository to simplify dependency installation.

---

## Setup Instructions

### Step 1: Install Dependencies
Install all dependencies listed in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### Step 2: Configure Environment Variables
Create a `.env` file in the root directory and add your OpenAI API key:
```plaintext
OPENAI_API_KEY=your_openai_api_key
```
Instructions for obtaining the API key are provided in the tutorial.

### Step 3: Download Dataset
The dataset for this project can be downloaded from [Kaggle](https://www.kaggle.com). Follow the instructions in the repository to download and configure the dataset.

### Step 4: Run the Notebooks
Execute the Jupyter notebooks in the following order to complete the tutorial:
1. `data-exploration.ipynb`
2. `vector-search.ipynb`
3. `text-classification.ipynb`
4. `sentiment-analysis.ipynb`

### Step 5: Launch the Web Application
Run the Gradio dashboard to interact with the book recommender:
```bash
python gradio-dashboard.py
```

---

## Features
- **Semantic Search**: Discover books based on natural language descriptions.
- **Category Filtering**: Filter books by "fiction" or "non-fiction."
- **Tone Analysis**: Sort books by emotional tone (e.g., joyful, suspenseful, sad).
- **Interactive UI**: Get recommendations through a user-friendly web interface built with Gradio.

---

Happy coding! 🎉
