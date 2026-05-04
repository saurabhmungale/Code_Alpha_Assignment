# 🤖 Code Alpha Assignment – AI FAQ Chatbot

This repository contains my **Artificial Intelligence internship assignment** from Code Alpha.
The project focuses on building a simple yet effective **FAQ Chatbot** using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

The chatbot is designed to:

* Understand user queries using NLP
* Match them with predefined questions
* Return the most relevant answer

It uses **text similarity techniques** instead of hardcoded responses, making it more flexible and intelligent.

---

## 🚀 Features

* 🧠 Natural Language Processing using spaCy
* 🔍 Text preprocessing (tokenization, lemmatization, stopword removal)
* 📊 TF-IDF vectorization
* 📐 Cosine similarity for response matching
* 💬 Simple and interactive chatbot interface

---

## 🛠️ Tech Stack

* **Python 3**
* **spaCy**
* **scikit-learn**
* **NumPy**

---

## 📂 Project Structure

```
Code_Alpha_Assignment/
│── Chatbot_for_FYQ.ipynb   # Main chatbot implementation
│── README.md               # Project documentation
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/Code_Alpha_Assignment.git
cd Code_Alpha_Assignment
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download spaCy model:

```bash
python -m spacy download en_core_web_sm
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Chatbot_for_FYQ.ipynb
```

Start interacting with the chatbot by typing your queries.

---

## 🧠 How It Works

1. User input is preprocessed
2. Converted into TF-IDF vectors
3. Compared with stored questions
4. Best match is selected using cosine similarity
5. Corresponding answer is returned

---

## 📸 Sample Output

```
User: What is AI?
Bot: Artificial Intelligence is the simulation of human intelligence in machines.
```

---

## 🎯 Learning Outcomes

* Practical implementation of NLP concepts
* Understanding of text vectorization (TF-IDF)
* Experience with similarity-based models
* Hands-on work with real-world chatbot logic

---

## 🔮 Future Improvements

* Add Deep Learning-based models (BERT / Transformers)
* Build a web interface using Flask or Streamlit
* Expand dataset for better accuracy
* Add voice-based interaction

---

## 🙌 Acknowledgment

This project was completed as part of the **Code Alpha Artificial Intelligence Internship**.

---

## 📬 Contact

**Saurabh Mungale**
📧 saurabhmungale99@gmail.com
🔗 www.linkedin.com/in/saurabh-mungale

---

⭐ If you found this project useful, consider giving it a star!
