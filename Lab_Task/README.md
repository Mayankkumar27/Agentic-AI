# Agentic AI – Lab Task 1  
## Fine-tuning a Small Language Model (SLM)
---
## 📌 Objective
The objective of this lab task is to fine-tune a **Small Language Model (SLM)** on a text dataset using **Google Colab**, and to evaluate its performance using appropriate metrics.

---

## 🛠 Tools & Technologies Used
- **Platform:** Google Colab (GPU)
- **Framework:** Hugging Face Transformers
- **Language:** Python
- **Libraries:** transformers, datasets, torch, evaluate

---

## 📂 Dataset
- **Source:** Hugging Face Datasets
- **Dataset Name:** WikiText-2 (`wikitext/wikitext-2-raw-v1`)
- **Description:**  
  WikiText-2 is a high-quality dataset consisting of cleaned Wikipedia articles.  
  It is widely used for training and evaluating language models.

---

## 🤖 Model Used
- **Model Name:** DistilGPT-2
- **Model Type:** Small Language Model (SLM)
- **Number of Parameters:** ~82 Million  
- **Reason for Selection:**  
  DistilGPT-2 is lightweight, efficient, and well below the 3B parameter limit specified in the task.

---

## ⚙️ Methodology
1. Loaded the WikiText-2 dataset from Hugging Face.
2. Tokenized the text data using the DistilGPT-2 tokenizer.
3. Fine-tuned the DistilGPT-2 model using the Hugging Face `Trainer` API.
4. Due to computational constraints of Google Colab, a reduced subset of the dataset and one training epoch were used.
5. Evaluated the fine-tuned model using **perplexity** as the evaluation metric.
6. Tested the model by generating sample text to observe improvements.

---

## 📊 Evaluation Metric
- **Perplexity**
  - Perplexity measures how well a language model predicts text.
  - Lower perplexity indicates better language understanding.
  - The fine-tuned model showed improved perplexity compared to the base model.

---

## 📝 Results & Observations
- Training loss decreased during fine-tuning, indicating successful learning.
- The fine-tuned model generated more coherent and context-aware text.
- Even with limited data and epochs, the model demonstrated noticeable improvement.
- This experiment shows that Small Language Models can be effectively fine-tuned using limited computational resources.

---
---

## ✅ Conclusion
This lab successfully demonstrates the process of fine-tuning a Small Language Model on a text dataset.  
The experiment validates that SLMs can be efficiently adapted for language modeling tasks using Google Colab and Hugging Face tools, making them suitable for educational and real-world applications.
