# 🤖 BERT Sentiment Classification on Short Reviews

This project uses a **pre-trained BERT model** (`bert-base-uncased`) from Hugging Face to perform sentiment classification on small input sentences or review snippets.

## 🔍 Project Overview

I started by experimenting with short text reviews using a pre-trained transformer model. The model was able to predict sentiment for each input sentence **without training** — just using its built-in knowledge.

### 📥 Input
Small review sentences (like product reviews, comments, or movie feedback).

### 📤 Output
- 🌟 **Star Ratings**: Scaled from 1 to 5
- ✅ **Sentiment Labels**:
  - Positive
  - Neutral
  - Negative

## ⚙️ How It Works

- Uses Hugging Face's `transformers` pipeline
- Loads `bert-base-uncased` sentiment model
- Applies on sample sentences to generate predictions
