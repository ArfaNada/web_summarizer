Webpage Summarizer using Hugging Face

This project is a simple Python tool that scrapes website content and generates concise summaries using a Hugging Face LLM model. It automates text extraction, cleaning, and summarization directly from any webpage URL.

⚙️ Tech Stack

Python

BeautifulSoup  for web scraping

Hugging Face Transformers for text summarization

Google Colab for running the notebook

🚀 How It Works

The user provides a website URL.

The script scrapes and cleans the webpage text.

A pre-trained Hugging Face model (e.g., Mistral 7B) generates a summary of the content.

📦 Example Usage
display_summary("https://example.com")

🧾 Output

A short, coherent summary of the webpage content.# web_summarizer
