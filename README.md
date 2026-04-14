# LocalGPT-Generator
A simple local AI text generator that creates human-like responses using TinyLlama — no APIs, runs completely offline.

## 🚀 What it does?

LocalGPT-Generator takes your input (a prompt or message) and generates a natural, human-like response.  
It follows a chat-style format, meaning it understands basic conversation flow and responds accordingly.

For example:
You: What is AI?
Bot: AI (Artificial Intelligence) is the ability of machines to simulate human intelligence, such as learning and problem-solving.


It works by predicting text step-by-step based on your input and previous conversation context.



## 🧩 How it works

- You enter a message  
- The message is formatted into a conversation (User → Assistant)  
- The model processes the input  
- It generates the next sequence of words based on probability  
- The response is returned and displayed  

The conversation history is stored, so responses stay context-aware.


## 📦 Model used

LocalGPT-Generator uses the TinyLlama chat model:

👉 https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0

This is a lightweight (1.1B parameters) chat-optimized model designed for conversational tasks.


## 🛠️ Tech stack

- Python  
- Hugging Face Transformers  
- PyTorch  

