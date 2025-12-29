# Reactivity-Gerifier
Task 1 - Emotion Classification with BERT (GoEmotions Dataset)

# Task 1: Emotion Classification with BERT

## 📋 Project Overview
This project implements an end-to-end emotion classification system using BERT transformer model. The model is fine-tuned on the GoEmotions dataset to classify text into 28 emotion categories.

## 🎯 Objective
- Build encoder-based text classifier using BERT
- Compare performance with traditional ML (Logistic Regression)
- Implement complete ML pipeline: data processing → training → evaluation

## 📊 Dataset
- **Name**: GoEmotions
- **Source**: HuggingFace Datasets
- **Size**: 58,000 samples (43,410 train, 5,426 validation, 5,427 test)
- **Classes**: 28 emotions + neutral
- **Task**: Multi-label text classification (simplified to single-label)

## 🤖 Models Implemented
1. **Traditional ML Baseline**: Logistic Regression with TF-IDF features
2. **Deep Learning**: BERT-base-uncased fine-tuned

## 📈 Results
| Model | Accuracy | F1-Score | Improvement |
|-------|----------|----------|-------------|
| Logistic Regression | 38.5% | 37.2% | Baseline |
| **BERT Fine-tuned** | **74.8%** | **72.6%** | **+94%** |

## 🏗️ Project Structure
