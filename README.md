# 🚀 Task 5: Auto Tagging Support Tickets Using LLM

## 📌 Overview
This project focuses on automatically classifying customer support tickets into relevant categories using a Large Language Model (LLM). The system leverages zero-shot and few-shot learning techniques to perform text classification without requiring model training.

---

## 🎯 Objective
- Automatically tag support tickets into predefined categories  
- Compare Zero-shot and Few-shot learning approaches  
- Predict top 3 most probable tags for each ticket  

---

## 📊 Dataset
A sample dataset of support tickets was created, containing real-world style customer queries such as:
- Login issues  
- Payment problems  
- Application errors  

This dataset can be replaced with a real-world dataset for scalability.

---

## 🧠 Methodology / Approach

### 🔹 1. Data Preparation
- Created dataset using Pandas  
- Defined relevant categories (labels)  

### 🔹 2. Model Selection
- Used Hugging Face Transformer model: facebook/bart-large-mnli  
- Applied zero-shot classification (no training required)  

### 🔹 3. Zero-Shot Learning
- Classified tickets without providing examples  
- Generated top 3 predicted labels  

### 🔹 4. Few-Shot Learning (Prompt Engineering)
- Improved performance using example-based prompts  
- Helped model better understand classification context  

### 🔹 5. Prediction Output
- Model returns:
  - Top 3 most relevant categories  
  - Ranked predictions  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Hugging Face Transformers  
- Matplotlib  
- Google Colab  

---

## 📈 Results / Observations
- Zero-shot learning provided strong baseline results  
- Few-shot prompting improved accuracy  
- Model successfully predicted multiple relevant tags  
- Useful for automating customer support systems  

---

## 📁 Project Structure
task5-auto-tagging-support-tickets/
│── task5_auto_tagging_support_tickets_llm.ipynb
│── tagged_support_tickets.csv
│── README.md

---

## 💡 Key Learnings
- LLM-based text classification  
- Zero-shot vs Few-shot learning  
- Prompt engineering techniques  
- Multi-class prediction and ranking  

---

## 🔮 Future Improvements
- Use a real-world dataset  
- Fine-tune model for better accuracy  
- Deploy using Streamlit or Gradio  

---

## ✅ Conclusion
Large Language Models can effectively automate support ticket classification without training, making them highly useful for real-world applications.

---

## 🔗 Author
Farwa Afzal  
AI/ML Intern – DevelopersHub
