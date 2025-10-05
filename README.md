# hate-speech-detection-using-Memotion3.0

## Project title: Deciphering Memes: Detecting Hateful Speech in Bilingual Hinglish Memes using Contrastive Learning

# Dataset
Primary dataset: Memotion 3.0 (10K annotated Hinglish memes).
Dataset is obtained from: 

# Inputs:
OCR-extracted text (noisy, code-mixed Hinglish).
Meme images.

Labels: Hate vs Non-Hate.

# Models Implemented

# Baselines:
Logistic Regression (TF-IDF + ResNet50).
SVM (TF-IDF + ResNet50).

# Transformer Models:
VisualBERT (BERT + ViT).
VisualBERT (XLM-RoBERTa + CLIP).

# Task A: To predict the hate/non-hate labels for test data.
# Task B: To evaluate the test results obtained by fetching labels from chatGPT and record the metrics. Analyse and evaluate the best model.
