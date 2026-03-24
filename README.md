# 🤖 NLP Chatbot Using Python  
A simple and lightweight NLP Chatbot built using **Python**, **NLTK**, and **text similarity matching**.  
This chatbot understands user queries by matching them with predefined intents and responds accordingly — all **without external JSON files** (intents are embedded inside the script).

---

## 📌 Project Overview

This project demonstrates how to build a basic **rule-based NLP chatbot** using:

- Text preprocessing (tokenizing + stemming)
- Bag-of-words vectorization (CountVectorizer)
- Cosine similarity for intent matching
- Hard-coded intents stored internally
- Simple conversational flow

This chatbot can understand greetings, farewells, questions about the bot, jokes, study tips, motivation, and more.

It is fully extensible — just add new intents to the list inside the script!

---

## 🧠 Features

✔️ Offline chatbot (no API required)  
✔️ Embedded intents — no JSON loading  
✔️ NLTK-based preprocessing  
✔️ Cosine similarity text matching  
✔️ Easy to customize & extend  
✔️ Beginner-friendly code  

---

## 📂 Project Structure


nlp-chatbot/
│
├── chatbot.py
├── requirements.txt
├── README.md
│
├── images/
│ ├── cover.png
│ └── demo.png
│
└── data/
└── intents_conversation.txt


---

## 🖼️ Screenshots

### 🔹 **Project Cover Image**

<img width="1536" height="1024" alt="NLP chatbot with Python and robot" src="https://github.com/user-attachments/assets/0d3bc757-5f80-465c-93a2-757e0084ec08" />

### 🔹 **Chatbot Demo**

<img width="730" height="390" alt="Conversation" src="https://github.com/user-attachments/assets/f05c4e4b-6be4-4ed8-9d23-e210d96cec02" />

<img width="690" height="107" alt="conv 2" src="https://github.com/user-attachments/assets/8ee25aad-c4f8-4565-b8e1-1795141a5985" />

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https:/https://github.com/gaurigiri777-prog/github.com//nlp-chatbot.git
cd nlp-chatbot

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Chatbot

python chatbot.py

🛠 Tech Stack

Component	              Technology
Language	              Python

NLP	                    NLTK

Vectorization           CountVectorizer

Similarity Matching	    Cosine Similarity

Model Type	            Rule-based chatbot


🧩 How It Works (Simplified)

1. User input is cleaned, tokenized, and stemmed

2. All patterns (training phrases) are vectorized

3. A random response from that intent is sent back

4. If no pattern matches → default fallback response


📈 Future Enhancements

Add GUI (Tkinter or Streamlit)

Add real-time speech recognition

Add deep learning (RNN / Transformers)

Add conversation logging

Expand the intents database

🤝 Contributing

Pull requests, improvements, and ideas are always welcome!

Feel free to open an issue or suggest features.


📜 License

This project is open-source under the MIT License.

⭐ If you find this project helpful, please give it a star on GitHub!

---
