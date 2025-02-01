# 📚 LLM Book Recommender 🚀

This project implements an intelligent book recommendation system using **Large Language Models (LLMs)** to provide **personalized book suggestions** based on user preferences and book descriptions.

## 🔍 Project Overview

The **LLM Book Recommender** processes a dataset of books, cleans and analyzes the data, and leverages **LLMs** for various tasks, including **vector search**, **zero-shot text classification**, and **sentiment analysis**. The final output is an **interactive dashboard** where users can get book recommendations tailored to their interests.

---

## 📂 Repository Structure

📁 `.idea/` - PyCharm project configuration files  
📄 `.gitignore` - Files and directories ignored by Git  
📄 `README.md` - Project documentation  
📊 `books_cleaned.csv` - Dataset after initial cleaning  
📊 `books_with_categories.csv` - Books with categorized labels  
📊 `books_with_emotions.csv` - Books annotated with emotions  
🖼 `cover-not-found.jpg` - Placeholder image for missing book covers  
📜 `data_exploration.ipynb` - Data exploration and cleaning notebook  
🖥 `gradio-dashboard.py` - Gradio-based interactive dashboard  
📜 `sentiment-analysis.ipynb` - Sentiment analysis using LLMs  
📜 `text-classification.ipynb` - Zero-shot text classification  
📜 `vector-search.ipynb` - Building and querying the vector database  

---

## ⚙️ Key Components & Methodologies

### 🛠 1. Data Collection & Preparation
✅ **Dataset**: Contains book descriptions and metadata  
✅ **Cleaning**: Handling missing values, removing short descriptions, and preprocessing data  

### 🔎 2. Vector Search with LLMs
📌 **Embeddings**: Generating vector representations of book descriptions  
📌 **LangChain**: Using LangChain for processing text with LLMs  
📌 **CharacterTextSplitter**: Splitting book descriptions into manageable chunks  
📌 **Vector Database**: Storing and querying book embeddings for recommendations  
📌 **Book Recommendations**: Retrieving books based on similarity scores  

### 🎯 3. Zero-Shot Text Classification
📌 **Hugging Face Models**: Using LLMs for classifying books without training data  
📌 **Category Prediction**: Assigning categories to books based on their descriptions  
📌 **Performance Check**: Evaluating the accuracy of classification results  

### ❤️ 4. Sentiment Analysis
📌 **Emotion Detection**: Extracting emotional tones from book descriptions  
📌 **Fine-Tuned Models**: Using LLMs optimized for sentiment analysis  

### 🌐 5. Interactive Dashboard with Gradio
📌 **Gradio UI**: Building an intuitive web interface for book recommendations  
📌 **User Input**: Accepting user preferences to personalize book suggestions  
📌 **Live Demo**: Running the dashboard locally to explore recommendations  

---

## 🚀 Getting Started

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/MothilalShiva/LLM_Book_Recommender.git
cd LLM_Book_Recommender

###🔹 2. Set Up the Environment
Ensure Python is installed on your system.

Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:

pip install -r requirements.txt
333🔹 3. Run the Gradio Dashboard

python gradio-dashboard.py
Access the dashboard at 👉 http://localhost:7860
