# Webpage Summarizer using Hugging Face

This project is a Python-based tool that scrapes textual content from a webpage and generates a concise summary using a Large Language Model (LLM) from Hugging Face. It automates the full pipeline—from text extraction and cleaning to summarization—using a simple function call with a webpage URL.

## ⚙️ Tech Stack

* **Python**
* **BeautifulSoup** – Web scraping and HTML parsing
* **Hugging Face Transformers** – Text summarization using pre-trained LLMs
* **Google Colab** – Notebook-based execution environment

## 🚀 How It Works

1. The user provides a webpage URL.
2. The script fetches and parses the HTML content.
3. Irrelevant elements (scripts, styles, etc.) are removed and the text is cleaned.
4. A pre-trained Hugging Face summarization model (e.g., **Mistral 7B**) generates a concise summary of the webpage content.

## 📦 Example Usage

```python
display_summary("https://example.com")
```

## 🧾 Output

* A short, coherent, and readable summary of the webpage’s main content.

## 📌 Notes

* Designed for educational and prototyping purposes.
* Works best on text-heavy webpages (articles, blogs, documentation).
* Model choice can be swapped easily depending on available compute resources.
