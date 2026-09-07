# 🤖 Rule-Based AI Chatbot

A simple and interactive **Rule-Based AI Chatbot built with Python** that uses a predefined knowledge base and rule-based logic to understand user queries and provide relevant responses.

The project demonstrates how conversational systems can be built using fundamental Python concepts such as dictionaries, functions, string processing, conditional logic, regular expressions, and session management.


## 📌 Project Overview

This chatbot is designed to simulate a basic conversational AI system without using external AI or machine learning models.

Instead of generating responses dynamically, it matches user input against predefined rules stored in a knowledge base and returns an appropriate response.

The chatbot also includes several interactive features to make the conversation more engaging and user-friendly.


## ✨ Features

* 💬 Interactive command-line chatbot
* 👋 Greeting and time-based greetings
* 🧠 Predefined knowledge base
* 🤖 Artificial Intelligence questions
* 📚 Machine Learning topics
* 🧠 Deep Learning concepts
* 🐍 Python-related questions and examples
* 📊 Data Science topics
* 😂 Jokes and interesting facts
* 👤 User name detection and memory
* 🕐 Current time command
* 📅 Current date command
* 📜 Conversation history
* 📈 Session statistics
* 🆘 Help command
* 🔄 Clear conversation history
* ❓ Fallback responses for unknown questions
* 🚪 Exit and goodbye commands
* 🎨 Colored terminal interface


## 🛠️ Technologies Used

* **Python 3**
* **Regular Expressions (`re`)**
* **Random Module**
* **Datetime Module**
* **Git & GitHub**

No external AI API or machine learning model is required.


## 📂 Project Structure

```text
Rule-Based-Chatbot/
│
├── chatbot.py
├── knowledge_base.py
├── colors.py
├── .gitignore
└── README.md
```

### File Description

| File                | Description                             |
| ------------------- | --------------------------------------- |
| `chatbot.py`        | Main chatbot logic and user interaction |
| `knowledge_base.py` | Predefined questions and responses      |
| `colors.py`         | Terminal color configuration            |
| `.gitignore`        | Files excluded from Git tracking        |
| `README.md`         | Project documentation                   |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/areeba-muddasar/Rule-Based-Chatbot.git
```

### 2. Navigate to the Project Directory

```bash
cd Rule-Based-Chatbot
```

### 3. Run the Chatbot

```bash
python chatbot.py
```


## 💬 Example Commands

You can interact with the chatbot using questions such as:

```text
hello
help
what is artificial intelligence
what is machine learning
types of machine learning
what is deep learning
what is python
give me a small python code
what is data science
what is pandas
tell me a joke
tell me a fact
```

The chatbot also supports interactive commands:

```text
my name is Areeba
what is my name
time
date
history
stats
clear
bye
```

---

## 🧠 How It Works

The chatbot follows a simple rule-based workflow:

```text
User Input
    ↓
Input Cleaning
    ↓
Name / Command Detection
    ↓
Knowledge Base Matching
    ↓
Generate Predefined Response
    ↓
Store Conversation History
    ↓
Display Response
```

The chatbot first cleans and processes the user's input. It then checks for special commands and predefined rules.

If a matching rule is found, the chatbot selects an appropriate response. If no matching rule exists, a fallback response is displayed.

---

## 📚 Knowledge Base

The knowledge base contains predefined responses for several categories:

* **Greetings**
* **General Conversation**
* **Artificial Intelligence**
* **Machine Learning**
* **Deep Learning**
* **Python**
* **Data Science**
* **Fun & Facts**
* **Help**

This makes it easy to expand the chatbot by adding new questions and responses to `knowledge_base.py`.


## 📊 Session Features

The chatbot maintains basic information during the current session, including:

* Total messages
* Conversation turns
* Unique user inputs
* Session duration
* User name
* Conversation history

Users can also clear the stored conversation history using:

```text
clear
```


## ⚠️ Limitations

This chatbot is **rule-based**, so it can only answer questions that have been predefined in its knowledge base.

It does not use:

* Large Language Models
* Generative AI
* Machine Learning models
* External APIs
* Internet-based search

Therefore, questions outside the predefined knowledge base may result in a fallback response.


## 🔮 Future Improvements

Possible future improvements include:

* Adding more knowledge-base categories
* Improving natural language matching
* Using NLP techniques for better intent detection
* Adding a graphical user interface
* Adding voice input and output
* Integrating a database for persistent memory
* Connecting the chatbot to an AI/LLM API


## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

* Python programming
* Functions and modular code
* Dictionaries and data structures
* String processing
* Regular expressions
* Conditional logic
* User input handling
* Session management
* Error handling
* Git and GitHub
