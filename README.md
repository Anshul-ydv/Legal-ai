# 🧠 Legal AI Assistant & Summarizer 🏛️

This repository contains two key AI tools for legal assistance:

1. **Legal Chatbot** – An intelligent assistant for answering legal queries based on Indian law.
2. **Legal Summarizer** – A summarization tool for compressing lengthy legal judgments using a fine-tuned BART model.

---

## 📂 Project Structure

```

📁 /legal\_chatbot.ipynb         # Chatbot using Retrieval-Augmented Generation (RAG)
📁 /bartseq2seq.ipynb           # Seq2Seq fine-tuning of BART for summarization
📁 /Legal\_summarizer\_final.ipynb # Final pipeline for summarizing legal documents

````

---

## 🚀 Features

### ✅ Legal Chatbot
- 🔍 Retrieval-Augmented Generation using FAISS
- 📚 Trained on Indian Constitution, IPC, CrPC, etc.
- 🤖 Answers questions across major legal domains
- 📄 Supports document-based Q&A

### ✅ Legal Summarizer
- 🔄 Fine-tuned BART model on Indian Legal Case Law
- 🧾 Extractive + Abstractive summary support
- 🧠 Trained on `d0r1h/ILC` dataset from HuggingFace

---

## 🛠️ Installation

1. Clone the repo:
```bash
git clone https://github.com/yourusername/legal-ai-assistant.git
cd legal-ai-assistant
````

2. Install required packages:

```bash
pip install -r requirements.txt
```

---

## 🧪 Usage

### Run Legal Chatbot:

```bash
# Open the notebook
legal_chatbot.ipynb

# Follow the cells to ingest legal docs and start querying
```

### Run Legal Summarizer:

```bash
# Open the notebook
Legal_summarizer_final.ipynb

# Run cells to load model and summarize documents
```

---

## 📊 Dataset Info

* 📦 Summarizer Dataset: [d0r1h/ILC](https://huggingface.co/datasets/d0r1h/ILC)
* 📚 Chatbot Corpus: Structured QA pairs from Indian law

---

## 📌 Tech Stack

* Python · HuggingFace Transformers · FAISS · PyTorch · Google Colab · NLTK · Sklearn · Streamlit (optional UI)

---

## 💡 Future Improvements

* Add support for multilingual legal queries
* Deploy chatbot as a web app (FastAPI + Streamlit)
* Extend summarization to multi-modal court documents

---

## 🙌 Acknowledgements

* Indian Legal Corpus by [ILC on HuggingFace](https://huggingface.co/datasets/d0r1h/ILC)
* HuggingFace Transformers and Datasets
* OpenAI & FAISS for vector retrieval

---

## 📃 License

This project is open-source under the [MIT License](LICENSE).

---

## ✨ Fun Fact

> “This AI has read more Indian laws than most lawyers.” ⚖️🤖

