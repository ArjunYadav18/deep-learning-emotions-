# deep-learning-emotions-
# 🎯 GoEmotions Multi-Label Emotion Classifier

This project fine-tunes a DistilBERT transformer to classify Reddit comments into one or more of 28 emotional categories using the **GoEmotions** dataset released by Google AI.

---

## 📌 Project Overview

- **Goal**: Detect multiple emotions in a given English sentence using multi-label classification
- **Model**: Hugging Face `DistilBERTForSequenceClassification`
- **Loss Function**: `BCEWithLogitsLoss` (Binary Cross-Entropy for multi-label)
- **Evaluation**: Accuracy, Precision, Recall, F1 (Micro/Macro), Sklearn Report

---

## 📁 Folder Structure

