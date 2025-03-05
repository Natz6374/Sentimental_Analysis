---

# **Sentiment Analysis API with Gradio**  

This is a simple **Sentiment Analysis API** built using **Gradio** and **VADER Sentiment Analysis**. It classifies text into **Positive, Negative, or Neutral** based on sentiment scores.  

## 🚀 **Live Demo**  
https://huggingface.co/spaces/nathrath/sentiment_analysis

## 📌 **How It Works**  
- Enter a text sentence in the input box.  
- The model analyzes sentiment using **VADER (Valence Aware Dictionary and sEntiment Reasoner)**.  
- It returns one of the following results:  
  - **😊 Positive** (if sentiment is strong & positive)  
  - **😠 Negative** (if sentiment is strongly negative)  
  - **😐 Neutral** (if sentiment is mixed or neutral)  

## ⚙️ **Installation (For Local Run)**  
If you want to run it locally, install dependencies and start the app:  
```bash
pip install gradio vaderSentiment
python app.py
```
Then, open the **localhost URL** in your browser.  

## 📡 **Deployment on Hugging Face**  
1. Create a new Hugging Face Space (**Gradio SDK**).  
2. Upload the `app.py` and `requirements.txt` files.  
3. Click **"Commit"** and wait for deployment.  

## 🔥 **Example Usage**  
| Input Text | Sentiment Output |
|------------|----------------|
| "I love this product!" | 😊 Positive |
| "This is the worst experience ever." | 😠 Negative |
| "It's okay, not great but not bad." | 😐 Neutral |

## 📜 **License**  
This project is open-source and free to use!  

---
