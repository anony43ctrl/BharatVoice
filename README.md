# BharatVoice  
**AI-Powered Lok Sabha Speech Retrieval: A Langchain and FAISS-Based Search System**  

## 📌 Overview  
BharatVoice is an **AI-driven document retrieval system** designed to search and extract relevant information from **Lok Sabha speeches**. Built using **Langchain**, **FAISS**, and **various transformer models**, it enables efficient query-based document retrieval with potential for **LLM-powered summarization**.  

## 🚀 Features  
- 🔍 **Efficient Search**: Retrieves the most relevant speeches based on semantic similarity.  
- 📄 **Multi-Model Embeddings**: Supports **MiniLM, MPNet, DistilBERT, and Flan** for document representation.  
- 🏛 **FAISS Integration**: Uses **Facebook AI Similarity Search (FAISS)** for fast and scalable document retrieval.  
- 📝 **NLTK-Based Summarization**: Extracts the most relevant sentences based on keyword matching.  
- 🔧 **Customizable & Extensible**: Ready to be integrated with **LLMs for advanced summarization**.  

## 🏗 Tech Stack  
- **Python** 🐍  
- **FAISS** 🔍  
- **Langchain** 🔗  
- **Sentence Transformers** 🧠  
- **NLTK** 📜  
- **pdfplumber** 📄  

## 🗂 Dataset Source  
The dataset consists of **official Lok Sabha speeches** sourced from:  
🔗 **[eParliament (eparlib.nic.in)](https://eparlib.nic.in/handle/123456789/7/browse?type=date&sort_by=1&order=DESC&rpp=20&etal=-1&null=&offset=0)**  

##🛠 Usage
Enter a query (e.g., "policies on economy"), and the system will:
✅ Retrieve top matching Lok Sabha speeches.
✅ Extract relevant sentences using NLTK-based summarization.
