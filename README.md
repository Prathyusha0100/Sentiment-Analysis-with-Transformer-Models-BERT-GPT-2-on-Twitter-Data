#  Sentiment Analysis with Transformers (BERT, GPT-2)  

This project applies **Transformer-based models** such as **BERT and GPT-2** to perform **sentiment classification** on Twitter data. By fine-tuning a **pre-trained transformer**, the model achieves high accuracy in detecting **positive and negative sentiments** from tweets.

## 🚀 Project Overview  
- **Dataset:** Twitter sentiment dataset (labels: 0 = Negative, 4 = Positive).  
- **Model Used:** Fine-tuned **BERT (or GPT-2 small)** for classification.  
- **Training Method:** Used **pretrained transformer models** and optimized them for sentiment analysis.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score.  

## 📌 Features  
✅ **NLP Preprocessing:**  
- **Text Cleaning:** Removing stopwords, URLs, punctuation.  
- **Tokenization:** Using **BERT & GPT-2 tokenizers** for input representation.  

✅ **Transformer-based Sentiment Classification:**  
- **Fine-tuning a Pre-trained BERT/GPT-2 model** for classification.  
- **Batch training with AdamW optimizer & learning rate scheduling**.  
- **Hyperparameter tuning** to improve model performance.  

✅ **Evaluation & Results:**  
- **Accuracy, Precision, Recall, and F1-score** on test data.  
- **Confusion matrix & prediction visualization**.  

## 📊 Dataset
Dataset: Twitter Sentiment Dataset (Negative: 0, Positive: 4).
Train-Validation-Test Split: 80-10-10.

## 📈 Results
Fine-tuned Transformer Model Accuracy.
Confusion Matrix & Classification Report.
Predictions on sample tweets.
