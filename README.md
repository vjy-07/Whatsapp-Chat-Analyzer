# 📊 WhatsApp Chat Analyzer

A powerful Streamlit-based web app that provides deep insights into your WhatsApp chats. Upload your chat file and visualize key metrics, patterns, and behaviors — all in one click.

🔗 [Live Demo on Streamlit Cloud](https://whatsapp-chat-analyzer-0.streamlit.app)  

---

## 🚀 Features

This app analyzes exported WhatsApp chats (in `.txt` format) and provides the following features:

- 📈 **Top Statistics**:
  - Total messages
  - Total words
  - Media shared
  - Links shared

- 📆 **Time-based Analysis**:
  - Monthly timeline
  - Daily timeline
  - Most busy day
  - Most busy month
  - Weekly activity heatmap

- 👤 **User-Based Analysis**:
  - Most active users in the chat
  - User message distribution

- 🧠 **Text Analysis**:
  - Word cloud of chat messages
  - Most common words used

- 😂 **Emoji Analysis**:
  - Top emojis used
  - Emoji frequency chart

---
## 🧠 Text Analysis (Multilingual)
This app supports multilingual chats and is optimized to analyze Hinglish, Tenglish, and mixed-code chats using a custom set of stopwords.

☁️ Word Cloud: Most frequent meaningful words in the chat

🏷️ Most Common Words: Excludes common stopwords from:

English

Hindi (in English letters)

Telugu (in English letters)

---

## 📥 How to Export WhatsApp Chat (Android Only)

1. Open the WhatsApp chat you want to analyze.
2. Tap the three-dot menu → More → **Export chat**.
3. Choose **WITHOUT MEDIA** for faster upload.
4. Send the exported `.txt` file to your computer.
5. Ensure the chat is exported with a **24-hour time format** (important for proper parsing).

---

## 🛠️ Setup Locally

```bash
# Clone the repository
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

# Create and activate a virtual environment (Python 3.9 recommended)
python3.9 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```
## 📁 Project Structure
```
WHATSAPP_CHAT_ANALYSIS/
├── app.py               # Main Streamlit app
├── helper.py            # helper functions
├── preprocessor.py      # Data preprocessing logic
├── requirements.txt     # Python dependencies
├── stopwords.txt        # List of stopwords used for word filtering
└── .gitignore           # Git ignore file

```
