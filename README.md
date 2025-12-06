AUTOMATED QUESTION GENERATION

This project implements an Automated Question Generation (AQG) system using the FLAN-T5 transformer. The model is fine-tuned on a 10k-sample subset of the SQuAD dataset to generate context-aware, meaningful questions from any input text. A clean NLP pipeline handles preprocessing, training, evaluation, and inference, and the project includes a Gradio interface for real-time question generation.

KEY FEATURE

(i) Transformer-based question generation using FLAN-T5 model from Hugging Face

(ii) Fine-tuned on SQuAD v1.1 (10k curated samples)

(iii)BLEU-score based evaluation for performance measurement at different granularity level (1,2 and 3).

(iv) Preprocessing → tokenization → training → inference pipeline

(v) Gradio GUI for interactive question generation 
