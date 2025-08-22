# Twitter Sentiment Analysis (ML vs DL)

This project applies both **classical machine learning** and **deep learning** approaches to perform **sentiment analysis** on Twitter text data.

---

## Project Overview
- **Dataset**: Twitter training dataset (`twitter_training.csv`, `CombinedData.csv`).  
- **ML Model**: Random Forest Classifier with TF-IDF features.  
- **DL Models**:  
  - LSTM with Embedding layer.  
  - BiLSTM with Dropout, BatchNorm, L2 regularization.  
- **Task**: Classify tweets into multiple sentiment categories.  
- **Frameworks**: scikit-learn + TensorFlow/Keras.  

---

## Key Features
- Text preprocessing (lowercasing, cleaning, tokenization).  
- Comparison of ML (Random Forest) vs DL (LSTM, BiLSTM).  
- Regularization: dropout, L2 penalty, batch normalization.  
- Early stopping for better generalization.  
- Classification report (precision, recall, F1 per class).  

---

## Results
- **Random Forest**: ~70% accuracy.  
- **BiLSTM Tuned**: ~72% accuracy, improved macro F1.  

Example Classification Report:
