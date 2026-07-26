Markdown
# 🔍 AI-Powered Custom Search Engine

An intelligent, full-stack custom search engine that delivers fast, contextual, and categorized search results. Built using **Python**, **FastAPI**, **Streamlit / HTML-CSS UI**, and advanced natural language processing (NLP) / ranking techniques.

---

## 📌 Features

* 🚀 **Fast & Relevant Search**: Implements custom ranking algorithms and term-weighting to serve top relevant results.
* 🏷️ **Categorization & Filtering**: Dynamic tagging and category filtering for structured query responses.
* 🖥️ **Interactive Web Interface**: Clean, responsive, and intuitive user interface designed for seamless search experience.
* ⚡ **RESTful API Backend**: Powered by FastAPI for quick endpoint execution and easy integration.
* 📈 **Query Processing**: Text normalization, tokenization, stop-word removal, and intent matching.

---

## 🚀 The Development Journey (Day 1 vs. Final Day)

This project evolved significantly across the training program, moving from a foundational prototype to a fully structured, production-ready application:

### 🔹 Day 1: Baseline Prototype & Core Logic
* Developed the basic Python script to handle keyword matching.
* Implemented fundamental text processing (tokenization, lowercasing, and basic stop-word removal).
* Created a simple CLI / basic web script to test search queries against a static dataset.

### 🔹 Subsequent Days: Scalability & Architecture
* **Advanced Ranking & RAG Integrations**: Improved search relevance using structured ranking, term frequency weighting, and vector similarity concepts.
* **Backend Refactoring**: Re-architected the monolithic script into a modular **FastAPI** backend with clear separation of concerns (indexing, searching, and presentation layers).
* **UI/UX Enhancement**: Redesigned the frontend into a modern, user-friendly UI with real-time response rendering and smooth visual layouts.
* **Performance Optimization**: Added indexing mechanisms to speed up query evaluation and reduce lookup latency.

---

## 🏗️ System Architecture

![Architecture Diagram 1](assets/diagram1.png)



---


## 💻 Tech Stack

* **Language**: Python 3.10+
* **Backend**: FastAPI / Uvicorn
* **Frontend**: Streamlit / HTML5 & CSS3
* **Text Processing**: NLTK / Regex / Vector Search Concepts
* **Data Handling**: Pandas / JSON / Vector Indexes

---

## 🛠️ Quick Start & Installation

### Prerequisites
* Python 3.10 or higher
* `pip` package manager

### Steps

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/nooraaljaafar7-star/YOUR-REPOSITORY-NAME.git](https://github.com/nooraaljaafar7-star/YOUR-REPOSITORY-NAME.git)
   cd YOUR-REPOSITORY-NAME
Install Dependencies:

Bash
pip install -r requirements.txt
Run the Backend API:

Bash
uvicorn main:app --reload
Run the User Interface:

Bash
streamlit run app.py
🏛️ Organization & Acknowledgments
This project was developed as part of the hands-on AI & Software Engineering track.

Organization: SDAIA Academy
