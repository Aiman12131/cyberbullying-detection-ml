# bilingual-cyberbullying-detection-ml

# 🛡️ Cyberbullying Detection Using Machine Learning

A bilingual machine learning system for detecting abusive social media text in **English and Roman Urdu** using classical NLP and supervised learning models.

## Overview
This project focuses on cyberbullying detection in bilingual social media text, addressing challenges such as slang, sarcasm, informal language, and Roman Urdu spelling variations.

The pipeline uses:
- **TF-IDF n-gram features**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest**
- **Naive Bayes**

Text is classified into:
- **Abusive (1)**
- **Non-Abusive (0)**

## Dataset
The final dataset combines publicly available English and Roman Urdu cyberbullying / hate speech datasets.

- **Total samples:** 46,964
- **Languages:** English + Roman Urdu
- **Labels:** Binary

---

## Methodology
The workflow includes:

1. Text preprocessing  
2. TF-IDF feature extraction  
3. Training multiple ML classifiers  
4. Model evaluation using Accuracy, Precision, Recall, and F1-score  

---

##  Results
| Model | Accuracy | F1-Score |
|---|---:|---:|
| Random Forest | **84.74%** | **84.93%** |
| Logistic Regression | 83.23% | 83.62% |
| SVM | 83.18% | 83.29% |
| Naive Bayes | 80.88% | 82.10% |

**Best Model:** Random Forest

##  Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
---

## 🔮 Future Work
- Transformer-based models (BERT)
- Better Roman Urdu normalization
- Sarcasm and implicit bullying detection
- Explainable AI for predictions
