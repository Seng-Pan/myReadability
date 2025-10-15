# 📘 Myanmar Text Readability Project

This project focuses on **Myanmar text readability assessment**, including dataset creation, linguistic feature extraction, and classical machine learning modeling for grade-level classification and regression.

## Quick facts
- **Source:** Textbooks collected from edu4mm — 25 textbooks (1,679 pages).
- **Corpus size:** 10,735 labeled text samples (train/test split shown in report).
- **Features:** lexical & syllable stats, sentence/structural features, POS-based ratios, grade-level vocab ratios, TF-IDF & word embeddings, n-gram perplexities.
- **Top results:** Random Forest Classifier ≈ 82.4% accuracy; Random Forest Regressor baseline R² ≈ 0.80.

## Notes & next steps
- The current dataset is imbalanced across grades — expanding lower-grade samples is recommended.
- Future work: richer Burmese-specific linguistic features and transformer-based models (BERT-like) for better semantic modeling.
