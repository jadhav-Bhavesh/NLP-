# NLP-# 📝 Lab Assignment No. 4- NLP Preprocessing And Text Classification

## 📚 Course Information

- **Course Name:** Deep Learning  
- **Lab Title:** NLP Techniques for Text Classification  
- **Student Name:** Bhavesh Jadhav

---

## 🎯 Objective

The objective of this assignment is to implement NLP preprocessing techniques and build a text classification model using machine learning techniques.

---

## 🎯 Learning Outcomes 
- Understand and apply NLP preprocessing techniques such as tokenization, stopword removal, stemming, and lemmatization.
- Implement text vectorization techniques such as TF-IDF and CountVectorizer.
- Develop a text classification model using a machine learning algorithm.
- Evaluate the performance of the model using suitable metrics.

---

## 📖 Brief Theory

### 🔹 Natural Language Processing (NLP)

NLP enables machines to understand and interpret human language. It involves:
- **Tokenization** – Splitting text into individual words or tokens.
- **Stopword Removal** – Removing common words that don’t contribute much meaning.
- **Stemming** – Converting words to their root forms.
- **Lemmatization** – More accurate root word extraction using grammar rules.

### 🔹 Vectorization Techniques

- **CountVectorizer**: Converts text into a matrix of token counts.
- **TF-IDF Vectorizer**: Weighs tokens based on frequency and importance across documents.

### 🔹 Classification Algorithms

- **Logistic Regression**: A linear model effective for binary/multiclass classification.
- **Naive Bayes (Multinomial)**: A probabilistic classifier well-suited for text data.

---

## 🗂 Datase
- **Name:** AG News Dataset  
- **Source:**  https://en.innovatiana.com/post/best-datasets-for-text-classification 
- **Classes:** World, Sports, Business, Sci/Tech  
- **Attributes:** Title, Description, Label  

---

## 🧠 Models Implemented

### 1. Logistic Regression
- Trained on TF-IDF features.
- Accuracy: **88.62%**
- F1 Score: **0.8862**

### 2. Naive Bayes (Multinomial)
- Trained on CountVectorizer features.
- Accuracy: **88.42%**
- F1 Score: **0.8842**

---

## 📊 Results Summary

| Model               | Accuracy | F1 Score |
|--------------------|----------|----------|
| Logistic Regression| 88.62%   | 0.8862   |
| Naive Bayes        | 88.42%   | 0.8842   |

---
## 📈 Visualizations

- Confusion Matrix for each model
- Accuracy vs F1 Score Comparison Graph

| Logistic Regression | Naive Bayes |
|---------------------|-------------|
| ![Logistic CM](https://github.com/user-attachments/assets/13c0a41d-98a5-4a3b-ac0c-ef60cfe05a3d) | ![Naive Bayes CM](https://github.com/user-attachments/assets/870688c0-2044-4950-9375-74c580e8f0490) |

| Model Comparison |
|------------------|
| ![Comparison Chart](https://github.com/user-attachments/assets/1c5f738b-7052-4eff-ad8f-fc31315b1da9) |


## 🧪 Evaluation Metrics

- **Accuracy** – Overall correctness.
- **Precision** – True positives out of predicted positives.
- **Recall** – True positives out of actual positives.
- **F1 Score** – Balance of precision and recall.
- **Confusion Matrix** – Visual error analysis tool.

---

## 🚀 How to Run

1. Open the notebook in https://colab.research.google.com/drive/1zX34gBsEGVB890RQWFxGCMlaivf5uMDH#scrollTo=qfwaeuSgcupl
2. Upload the `ag_news` folder containing `train.csv` and `test.csv`.
3. Run each cell sequentially.
4. View classification reports, confusion matrices, and comparison graphs.

---

## 🔗 GitHub Repository

👉 https://github.com/jadhav-Bhavesh/NLP
## ⚙️ Project Structure

```bash
├── ag_news/
│   ├── train.csv
│   └── test.csv
├── NLP_Lab_Assignmnent_4 (1).ipynb
├── README.md
└── Output Screenshots/
