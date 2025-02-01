# 📚 LLM Book Recommender

## 📝 Overview

The **LLM Book Recommender** is a project that leverages **Large Language Models (LLMs) 🤖** and **vector search 🔍** to provide book recommendations. The system processes and cleans book descriptions, classifies them into categories, analyzes sentiments, and utilizes vector search for recommendations. A user-friendly interface is built using **Gradio 🎨** to interact with the recommender system.

## 📂 Project Structure

The repository contains the following files and directories:

📁 `.idea/` – Project-specific settings for PyCharm.  
📄 `.env` – Environment variables for the project.  
🚫 `.gitignore` – Specifies files to be ignored by Git.  
📖 `README.md` – Project documentation.  
📜 `books_cleaned.csv` – Cleaned book descriptions dataset.  
📊 `books_with_categories.csv` – Dataset with categorized books.  
📜 `books_with_emotions.csv` – Sentiment analysis results.  
🖼️ `cover-not-found.jpg` – Placeholder image for books without covers.  
📊 `data_exploration.ipynb` – Jupyter notebook for data analysis.  
🖥️ `gradio-dashboard.py` – Script to launch the **Gradio UI**.  
📈 `sentiment-analysis.ipynb` – Notebook for sentiment analysis.  
📜 `tagged_description.txt` – Tagged book descriptions file.  
📚 `text-classification.ipynb` – Notebook for book classification.  
🔍 `vector-search.ipynb` – Notebook for vector search implementation.  

## 🛠️ Methodology

The project follows these key steps:

### 1️⃣ Data Acquisition & Preparation 📥  
✔ Collected a dataset of book descriptions.  
✔ Cleaned data to handle missing values & removed short descriptions.  

### 2️⃣ Data Exploration 🔬  
✔ Analyzed patterns of missing data.  
✔ Examined the number of categories in the dataset.  

### 3️⃣ Text Classification 🎯  
✔ Used **pre-trained LLMs 🤖** for **zero-shot text classification** to categorize books.  
✔ Leveraged models from **Hugging Face 🤗** for classification tasks.  

### 4️⃣ Sentiment Analysis ❤️  
✔ Performed **sentiment analysis** on book descriptions using fine-tuned LLMs.  
✔ Extracted **emotions and sentiments** associated with each book.  

### 5️⃣ Vector Search for Recommendations 🔍  
✔ Split book descriptions using `CharacterTextSplitter`.  
✔ Built a **vector database** to store book embeddings.  
✔ Implemented **vector search** to recommend similar books.  

### 6️⃣ User Interface with Gradio 🎨  
✔ Developed an **interactive Gradio dashboard** for users to input preferences and receive book recommendations.  

## 🚀 How to Run

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/MothilalShiva/LLM_Book_Recommender.git
cd LLM_Book_Recommender
2️⃣ Set Up the Environment 🌍
Ensure Python 🐍 is installed.
Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install required dependencies:
pip install -r requirements.txt
3️⃣ Run the Gradio Dashboard 🖥️
python gradio-dashboard.py
Open the provided local URL to access the dashboard.
🛠️ Dependencies
The project relies on the following Python libraries:

📦 pandas – Data manipulation and analysis.
📦 numpy – Numerical computations.
📦 transformers – Pre-trained LLMs from Hugging Face.
📦 scikit-learn – Machine learning utilities.
📦 gradio – User-friendly UI framework.
📦 faiss – Efficient vector search operations.
Developed with ❤️ by Mothilal Shiva LinkedIn: https://www.linkedin.com/in/mothilal-shiva-41151b228/
