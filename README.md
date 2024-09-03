LLM Fine-Tuning for NLP Tasks
This repository contains Jupyter notebooks demonstrating the fine-tuning of large language models (LLMs) for various Natural Language Processing (NLP) tasks. Currently, it includes examples for sentiment analysis using LLaMA and relation extraction using Phi-3.
Projects
1. Sentiment Analysis with LLaMA

Model: LLaMA (Meta-Llama-3-8B-Instruct)
Task: Classifying the sentiment of text as positive, negative, or neutral.
Performance Improvement: Approximately 10% increase in accuracy after fine-tuning.
Notebook: llama_fine_tuning_sentiment_analysis.ipynb

2. Relation Extraction with Phi-3

Model: Phi-3 (microsoft/phi-3)
Task: Identifying and extracting relationships between entities in text.
Performance Improvement: Approximately 40% increase in F1 score after fine-tuning.
Notebook: phi3_fine_tuning_relation_extraction.ipynb

Getting Started
Prerequisites

Python 3.7+
PyTorch 1.10+
Transformers 4.25+
PEFT 0.3.0+
Datasets 2.10+
Scikit-learn 1.0+

Installation

Clone this repository:
