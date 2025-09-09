# 🗣️ Abusive Language Detection – Multiclass Text Classification  

## 📌 Introduction  
This project is focused on **multiclass text classification** to detect different levels of abusive language in text.  
Using **TF-IDF features** and a **Naive Bayes classifier**, the model predicts the severity of abusive language in user inputs.  
It has applications in **content moderation, online safety, and conversational AI**.  

---

## 🛠️ Tech Stack  
- **Language**: Python  
- **Libraries**: Scikit-learn, Pandas, NumPy  
- **Techniques**: TF-IDF Vectorization, Naive Bayes Classification, Cross-validation  
- **Validation**: k-Fold Cross Validation (k = 10)  

---

## 👩‍💻 My Contribution  
- Preprocessed and vectorized text data using **TF-IDF**.  
- Implemented a **Naive Bayes classifier** for multiclass prediction.  
- Validated performance using **10-fold cross-validation**.  
- Documented and analyzed classification results.  

---

## 📂 Dataset & Columns  
- `user` – Text input from users  
- `abusive_level` – Classification label:  
  - Not abusive  
  - Ambiguous  
  - Mildly abusive  
  - Strongly abusive  
  - Very strongly abusive  

Dataset reference:  
[Cercas Curry et al., 2021 – ConvAbuse](https://aclanthology.org/2021.emnlp-main.587)  

---

## 📊 Results  
- The model achieved strong performance in identifying abusive content.  
- Naive Bayes proved effective for **text-based abuse classification** with TF-IDF features.  

---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/mattagayi-collab/Aggression_detection_model-main.git
