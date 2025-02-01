# 📖 LLM Book Recommender 📚

## Overview  
The **LLM Book Recommender** is a **Machine Learning-based** book recommendation system that utilizes **Large Language Models (LLMs)** for **vector search, zero-shot text classification, and sentiment analysis**. This project allows users to get personalized book recommendations through an interactive **Gradio-based UI**.

---

## ✨ Features  
- **Book Recommendation System** 📚  
- **Vector Search using LLMs** 🔍  
- **Zero-shot Text Classification** 🎯  
- **Sentiment Analysis on Book Descriptions** ❤️  
- **User-friendly UI built with Gradio** 🎨  

---

## 🚀 Technologies Used  
- **Python** 🐍  
- **LangChain** (for managing LLM workflows) 🔗  
- **Hugging Face Transformers** (LLM models) 🤖  
- **FAISS** (Vector database for similarity search) 🗂️  
- **Scikit-learn & Pandas** (for data preprocessing) 📊  
- **Gradio** (for building the interactive UI) 🎭  
- **GitHub** (Version Control) 🌍  

---

## 🏗️ Installation & Setup  

### Clone the Repository  
```sh
git clone https://github.com/MothilalShiva/LLM_Book_Recommender.git
cd LLM_Book_Recommender
```
### Install Dependencies
```sh
pip install -r requirements.txt
Run the Application
python gradio-dashboard.py
```
The Gradio UI will be available at: http://localhost:7860
### 📖 Usage
Enter a book description or select from available options.
The system will use vector search to find similar books.
Predictions are enhanced using zero-shot classification and sentiment analysis.
Get personalized book recommendations instantly!

### 📂 Project Structure
```
LLM_Book_Recommender/
│── models/                     # Pre-trained ML models
│── data/                       # Dataset files
│── main.py                     # Main script for processing LLM queries
│── gradio-dashboard.py         # Gradio UI for recommendations
│── vector-search.ipynb         # Notebook for vector similarity search
│── sentiment-analysis.ipynb    # Notebook for sentiment analysis
│── text-classification.ipynb   # Notebook for zero-shot classification
│── requirements.txt            # Python dependencies
│── README.md                   # Project Documentation
```
📸 Working Demo 
![Video](https://github.com/MothilalShiva/LLM_Book_Recommender/blob/main/working%20demo.mp4)

---

Developed with ❤️ by Mothilal Shiva
🔗 LinkedIn: https://www.linkedin.com/in/mothilal-shiva-41151b228/
