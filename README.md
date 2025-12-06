**AUTOMATED QUESTION GENERATION SYSTEM**
 
This project implements an Automated Question Generation (AQG) system using the FLAN-T5 transformer. The model is fine-tuned on a 10k-sample subset of the SQuAD dataset to generate context-aware, meaningful questions from any input text. A clean NLP pipeline handles preprocessing, training, evaluation, and inference, and the project includes a Gradio interface for real-time question generation.

**KEY FEATURES**

>Transformer-based question generation using FLAN-T5 model from Hugging Face
>Fine-tuned on SQuAD v1.1 (10k curated samples)
>BLEU-score based evaluation for performance measurement at different granularity level (1,2 and 3).
> Preprocessing → tokenization → training → inference pipeline
> Gradio GUI for interactive question generation 

**RESULTS ANALYSIS**
1. The given figure shows comparision of T5 model against different models such as BERT, rule based and template based approaches. BLEU scores of granularity level 1-gram,2-gram and 3-gram are used for this purpose. The granularity level indicates number of matching sequences
<img width="900" height="184" alt="image" src="https://github.com/user-attachments/assets/22b850d5-17d3-4084-a7f5-bc1c91e7b8dd" />




2. Overall BLEU Score Pie Chart displaying proportional distribution of scores.
Template-Based (gray): 18%, Rule-Based (blue): 21%, T5-Small (orange): 25% (highlighted),
BERT-Based (green): 27%. T5-Small achieves competitive overall performance while excelling in other
critical dimensions
<img width="779" height="619" alt="image" src="https://github.com/user-attachments/assets/58898ec6-0085-40f6-8ef6-3a3640e8ba68" />



3. Performance Metrics Bar Chart comparing four dimensions across all methodologies
<img width="1293" height="843" alt="image" src="https://github.com/user-attachments/assets/7a9c62ba-5cca-4fb1-abfe-fa2c4a248e63" />
