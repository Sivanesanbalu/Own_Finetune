# 🤖 Fine-Tuning Qwen1.5-0.5B-Chat for Custom Bot Responses

This project focuses on fine-tuning the Qwen1.5-0.5B-Chat model to build a domain-specific chatbot. The chatbot is trained to answer user queries about the location of a device called Spduino


## 📘 Project Overview

The model learns from a small dataset of conversations where users ask questions like “Where is the Spduino?” and the bot replies with consistent, correct answers.

It uses Hugging Face's Transformers and Datasets libraries to simplify the training process.


## 🧠 Model Details

- **Base Model**: Qwen1.5-0.5B-Chat
- **Type**: Causal Language Model
- **Library**: Hugging Face Transformers

The model is capable of understanding context and generating relevant responses based on prompt patterns.



## 📚 Dataset Description

The training dataset consists of multiple user-bot text pairs where the user asks about the location of Spduino, and the bot provides a consistent answer — "A3#1". The dataset follows a conversation style:  
`User: ... \nBot: ...`


## 🛠️ Training Strategy

- Use Hugging Face’s `Dataset` object to prepare the input.
- Tokenize the text data with Qwen’s tokenizer.
- Define training arguments such as batch size, number of epochs, and logging steps.
- Use Hugging Face’s `Trainer` to automate training and evaluation.



## 💾 Output

After training:
- The fine-tuned model is saved locally.
- It can be loaded anytime for chatbot inference.
- The model responds correctly to variations of user questions about Spduino's location.


## 🧪 Application

The chatbot can be used:
- As a customer support assistant in hardware labs
- In embedded systems labs to guide users
- In educational tools to answer predefined queries



## 📬 Contact

**Project Title**: Fine-Tuned Chatbot for Device Assistance  
**Email**: apsiva69@gmail.com

