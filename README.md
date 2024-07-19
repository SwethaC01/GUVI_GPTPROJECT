# GUVI_GPTPROJECT

This project involves training a GUVI Generative Pre-trained Transformer (GPT) model using data from GUVI. The model is designed to generate coherent and contextually relevant text based on the input provided.

## Problem Statement
The task is to deploy a fine-tuned GPT model, trained specifically on GUVI’s company data, using Hugging Face services. Students are required to create a scalable and secure web application using Streamlit or Gradio, making the model accessible to users over the internet.The deployment should leverage Hugging Face spaces resources and any database to store the username and login time.

## Domain : 🤖 AIOPS

## Project Overview
The aim of this project is to fine-tune a GPT model with data sourced from GUVI to create a text generation model that can assist in various tasks such as content creation, automated responses, and more.

## 🗃️ Dataset
The dataset used for training the model is collected from various websites. It includes a variety of text data that covers different topics and contexts to ensure a diverse and comprehensive training set.

## 🔄 Model Architecture
The model architecture is based on OpenAI's GPT-2. GPT-2 is a transformer-based model that uses unsupervised learning to generate human-like text. The model has been fine-tuned using the collected dataset to improve its performance on specific tasks.

## Training

The training process involves the following steps:

1. Data Collection: Text data is collected from various websites to create a comprehensive dataset.
2. Data Preprocessing: The text data is cleaned and preprocessed to remove any irrelevant information and format it suitably for training.
3. Tokenization: The text data is tokenized using the GPT-2 tokenizer.
4. Fine-tuning: The GPT-2 model is fine-tuned using the preprocessed and tokenized text data.

## 🛠 Technology and Skills Takeaway
```
Python 3.8+
PyTorch
Transformers (Hugging Face)
Streamlit
Accelarate-u
```
## Fine-tuning Script
Fine-tune the model in Google Colab and export it:

1. Open the Colab notebook and run the training script.
2. Download the fine-tuned model.
   
## 🤗 Upload to Hugging Face

1. Upload the fine-tuned model folder to Hugging Face.
2. You can deploy a Streamlit application through Hugging Face Spaces. 

> [!DISCLAIMER]

> GUVIGPT can make mistakes. The content generated by the model may not always be accurate or appropriate. Please use it responsibly..

## Acknowledgements

https://openai.com/ for developing GPT-2.
https://huggingface.co/ for providing the Transformers library and hosting the model.
Various websites for providing the data used in this project mainly:https://www.guvi.in/

## Deployment

To deploy this project run just click the below link

🚀 - [Hugging Face Model Link]https://huggingface.co/spaces/Swetha15/GUVI_GPT
