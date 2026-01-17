# Project README

## 📌 Description

This project demonstrates how to generate text embeddings using **LangChain HuggingFace Endpoint Embeddings**, compare them using **cosine similarity**, and retrieve the most relevant document. It loads environment variables, generates embeddings for documents and a query, and identifies the closest semantic match.

---

## ⚙️ Setup Instructions

Follow the steps below to set up and run this project on your local machine.

### 1️⃣ Clone the Repository

```bash
git clone 
cd genai-mini-projects
cd document-similarity
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

Activate the venv:

* **Windows:**

```bash
venv\\Scripts\\activate
```

* **Mac / Linux:**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Create `.env` File

Create a `.env` file in the project root and add required environment variables:

```
SECRET_KEY=your_secret_key
API_KEY=your_api_key
...etc
```

### 5️⃣ Run the Project

Explain here how to start the server or script, for example:

```bash
python document_similarity.py
```
