# 📱 Data Science Capstone – SwiftKey Next-Word Prediction Project  
**Johns Hopkins University – Coursera | Data Science Specialization**

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![NLP](https://img.shields.io/badge/NLP-Text%20Mining-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Project Summary

This repository contains my end-to-end implementation of the **Johns Hopkins University Data Science Capstone**, created in partnership with **SwiftKey**.

The aim is to build a **Next-Word Prediction Model** similar to predictive text engines used in smartphone keyboards.  
Given a phrase such as:

> **"I went to the"**

the model should predict likely next words such as:

> **"gym"**, **"store"**, **"restaurant"**

This project uses **Natural Language Processing**, **text mining**, **language modeling**, and **web app deployment** to create a functional predictive text application.

---

# 🔍 Project Objectives

This capstone mirrors real-world data science workflow:

### **1️⃣ Task 0 – Understanding the Problem**
- Learn how predictive text works  
- Study SwiftKey’s use case  
- Explore the HC Corpora dataset  

### **2️⃣ Task 1 – Data Acquisition & Cleaning**
- Load Blogs, News, and Twitter data  
- Handle encoding, noisy text, foreign language  
- Create a reproducible sampled dataset  

### **3️⃣ Task 2 – Exploratory Data Analysis**
- Tokenization  
- Word counts, sentence structure  
- Frequency distributions  
- N-gram distribution patterns  

### **4️⃣ Task 3 – Modeling**
- Build **unigram, bigram, trigram, 4-gram models**  
- Apply smoothing methods (Add-k, Kneser-Ney, Good-Turing)  
- Implement **backoff**, **Stupid Backoff**, and **probability ranking**  

### **5️⃣ Task 4 – Prediction Engine**
- Given user input → return top-k next-word predictions  
- Optimize for runtime (sub-100ms responses)  
- Export models using **joblib / RDS**  

### **6️⃣ Task 5 – Data Product**
- Create a live web application that predicts the next word  
- Python (Flask / Streamlit) OR R (Shiny – original spec)  

### **7️⃣ Task 6 – Presentation**
- Create a 5-slide deck explaining  
  - Data  
  - Model  
  - Evaluation  
  - App  
  - Business case  

---

# 📂 Dataset

This project uses the **HC Corpora** dataset provided by Coursera:

Download link (required by project):  
👉 https://d396qusza40orc.cloudfront.net/dsscapstone/dataset/Coursera-SwiftKey.zip



