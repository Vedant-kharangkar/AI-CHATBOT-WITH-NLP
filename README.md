# AI-CHATBOT-WITH-NLP

**COMPANY: CODTECH IT SOLUTIONS

NAME:VEDANT AVINASH KHARANGKAR

INTERN ID:CT06DH1250

DOMAIN: PYTHON PROGRAMMING

DURATION:6 WEEKS

MENTOR: NEELA SANTOSH**

---

# DESCRIPTION OF TASK

---

# 🤖 AI Chatbot with NLP

## 📌 Project Overview

This project, **AI Chatbot with NLP**, demonstrates how to build a **simple yet intelligent conversational chatbot** using core Natural Language Processing techniques in Python.  

The bot reads from a knowledge base (`data.txt`), processes user input, and provides context-aware responses by comparing semantic similarity using **TF-IDF** and **cosine similarity**.  

> 💬 The chatbot can greet users, understand queries, and simulate basic conversations — making it an ideal project for beginners learning NLP, Python, or chatbot development.

The entire logic is implemented in **Python** and executed using **Google Colab**, a cloud-based notebook environment that’s great for experimentation and interactive learning.

---

## 🧰 Tools & Technologies Used

- **Language**: Python 3  
- **Libraries & Frameworks**:
  - `NLTK` – For tokenization, lemmatization, and preprocessing  
  - `Scikit-learn` – For `TfidfVectorizer` and `cosine_similarity`  
  - `Random`, `String` – For utilities like punctuation handling and random greeting replies  
- **Code Editor**: Google Colab (no setup required, browser-based)

---

## 🔄 Workflow

### ✅ Step 1: Data Ingestion
- Load `data.txt` as the chatbot's knowledge base  
- Convert text to **lowercase** for uniformity

### ✅ Step 2: Tokenization
- Tokenize into **sentences** and **words** using:
  ```python
  nltk.sent_tokenize()  
  nltk.word_tokenize()

### ✅ Step 3: Text Normalization
Remove punctuation using string.punctuation

Apply lemmatization via WordNetLemmatizer to convert words to base form

### ✅ Step 4: Greeting Recognition
Recognizes greetings like "hi", "hello", "whassup"

Responds with random friendly phrases using a predefined dictionary

### ✅ Step 5: Intelligent Response Generation
Vectorize sentences using TF-IDF

Use cosine similarity to compare user query with known sentences

Respond with the most relevant sentence or a fallback "I don’t understand" message

### ✅ Step 6: Interactive Chat Loop
The chatbot runs in a continuous loop

Ends gracefully when user types "bye" or "thank you"

---

## 🎯 Learning Objectives

Through this project, users will learn:

How to tokenize and preprocess text using NLTK

Importance of lemmatization and punctuation removal in NLP

 How to use TF-IDF to convert text to numerical format

How to compute semantic similarity using cosine similarity

How to create an interactive chatbot in Python using a loop

---

## Use Cases & Applications

Educational Tools – Teach basic NLP concepts

FAQ Chatbots – Static info bots for websites/helpdesks

Customer Support – Extendable to real-time assistance

Personal Assistants – Foundation for voice/text-based AI assistants

College Projects – Ideal academic project for demonstrating NLP workflows

---

## Future Enhancements

Add contextual conversation with RNNs or Transformers

Build a web interface using Flask or Streamlit

Support multiple languages with translation APIs

Store chat history with SQLite or Firebase

Add voice input/output using speech_recognition and pyttsx3

---

## Code Execution (Google Colab)

To run the chatbot:

1. Open Google Colab

2. Upload data.txt to the Colab environment

3. Paste the chatbot Python code into a new notebook cell

4. Run all cells in order

5. Start interacting with the chatbot using text input

---

# output 

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/37772699-adbf-496f-8a83-6f909917f42d" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/e56282b2-be7e-4e4b-89ec-726bc50643fc" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/325ed030-fa60-4e8f-8df9-34cd0e05c39b" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/b4834fac-0241-4b30-8882-e40fc08decd4" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/744748ed-2768-4797-90ec-0604d71f442e" />

