# 🧠 Exploring-Text-Summarization-Quality-A-Case-Study

## 📌 Introduction
This project demonstrates how to use the **Pegasus** model from Hugging Face to perform abstractive summarization on long-form text. It evaluates the generated summaries using both lexical (ROUGE) and semantic (BERTScore) metrics.

## ✨ Features
- Generates summaries using `google/pegasus-cnn_dailymail`, fine-tuned for news articles.
- Evaluates summary quality with:
  - **ROUGE**: Measures word overlap.
  - **BERTScore**: Measures semantic similarity.
- Simple and modular Python script.

## ⚙️ How It Works
1. Loads the Pegasus model and tokenizer.
2. Summarizes the input text using beam search.
3. Calculates ROUGE and BERTScore between original and generated text.
4. Displays precision, recall, and F1 scores for each metric.

## 🧩 Technologies Used
- `transformers`: For loading Pegasus model and tokenizer.
- `datasets`: Useful for text handling.
- `rouge_score`: For ROUGE metric computation.
- `bert_score`: For evaluating semantic similarity.

## ✅ Results
- The model produces concise summaries that retain the core meaning of the original text.
- ROUGE highlights surface-level similarity.
- BERTScore confirms semantic fidelity.
- Together, they provide a balanced evaluation of summarization quality.
