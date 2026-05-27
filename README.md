# AI NEws Summarizer Agent with voice integration

An AI-powered News Summarizer Agent built using Python, Google Gemini API, NewsAPI, and Text-to-Speech technology.

This project fetches news articles, generates concise AI summaries using Gemini, and converts the summaries into voice output.

---

# Features

- Latest news fetching using NewsAPI
- AI-generated summaries using Gemini AI
- URL-based news article summarization
- Voice generation from summaries
- CSV export support
- Interactive Jupyter Notebook workflow
- Retry and delay handling for API stability

---

# Technologies Used

- Python
- Jupyter Notebook
- Google Gemini API
- NewsAPI
- newspaper3k
- gTTS
- pandas

---

# Project Workflow

User enters news URL
        ↓
Article extraction
        ↓
Gemini AI summarization
        ↓
Voice generation
        ↓
Audio playback

---

# Project Structure

```text
AI-Voice-News-Summarizer/
│
├── audio/
├── data/
├── notebooks/
├── requirements.txt
├── README.md

```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-voice-news-summarizer.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# API Setup

## Gemini API

Get API Key from:

https://aistudio.google.com/app/apikey

---

## NewsAPI

Get API Key from:

https://newsapi.org/

---

# Run Project

```bash
jupyter notebook
```

Open:

```text
news_summarizer.ipynb
```

Run all cells sequentially.

---

# Future Improvements

- Multi-language voice summaries
- Streamlit web app
- Telegram bot integration
- Sentiment analysis
- Personalized news recommendations

---

# Contributors

- Sanu Yadav
- Aaditya Thakur

---

