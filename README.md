# 📚 Amazon Review Summarization using NLP 🚀  

📝 **Transforming lengthy customer reviews into concise, meaningful summaries using state-of-the-art NLP techniques!**  

---

## 🌟 Project Overview  
This project focuses on **abstractive text summarization** of **Amazon Fine Food reviews** using **Deep Learning and Transformer-based models**. The goal is to generate **coherent, high-quality summaries** that help in understanding customer feedback efficiently.  

📌 **Key Features:**  
- 🛠 **Data Preprocessing & Cleaning** – Tokenization, stopword removal, and text normalization.  
- 🤖 **Abstractive Summarization** – Implemented using **BART, T5, and custom Seq2Seq models with attention**.  
- 📊 **Evaluation Metrics** – Used **ROUGE and BLEU scores** to measure summary quality.  
- 🚀 **Scalable & Automated Pipeline** – Designed for easy integration with real-world datasets.  

---

## 📂 Dataset  
🔗 The dataset used in this project is **[Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews)** from Kaggle.  
It contains **500,000+ customer reviews**, providing an excellent testbed for NLP-based summarization.  

**Dataset Features:**  
✅ **Review Text** – Full customer reviews  
✅ **Summary** – Human-generated short summaries  
✅ **Product & User Information**  

---

## 🛠 Technologies Used  
✅ **Python** 🐍  
✅ **TensorFlow & Keras** – Deep learning framework  
✅ **Hugging Face Transformers** – Pretrained BART & T5 models  
✅ **NLTK & spaCy** – Text preprocessing and tokenization  
✅ **Pandas & NumPy** – Data manipulation  
✅ **ROUGE & BLEU Scores** – Summary evaluation  

---

## 🚀 How to Run the Project  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/amazon-review-summarization.git
cd amazon-review-summarization
🔬 Model Performance & Evaluation
The models were evaluated using ROUGE and BLEU scores, which measure the similarity between generated and human-written summaries.

## 🔬 Model Performance & Evaluation  
The models were evaluated using **ROUGE and BLEU scores**, which measure the similarity between generated and human-written summaries.  

### 📈 Results:  

| Model                  | ROUGE-1 | ROUGE-2 | ROUGE-L | BLEU  |
|------------------------|---------|---------|---------|-------|
| **BART**              | **0.166** | **0.055** | **0.159** | **0.025** |
| **T5**                | 0.155   | 0.045   | 0.151   | 0.024 |
| **Seq2Seq + Attention** | 0.103   | 0.007   | 0.096   | 0.017 |

✅ **BART outperformed other models, delivering the best-quality summaries!** 🚀  
