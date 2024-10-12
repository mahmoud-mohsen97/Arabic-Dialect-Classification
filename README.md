# Arabic Dialect Classification

This project focuses on classifying Arabic dialects using various machine learning models, including Random Forest, FastText, LSTM, and AraBERT (Transformer). The goal is to predict the dialect of Arabic texts, which is a challenging task due to the diverse grammar and dialectical variations in the Arabic language.

## Dataset
The dataset contains Arabic sentences labeled with dialects from five countries: Egypt (EG), Lebanon (LB), Libya (LY), Sudan (SD), and Morocco (MA). The dataset is imbalanced, with most samples from the Egyptian dialect. The original dataset and research paper can be found [here](https://arxiv.org/pdf/2005.06557.pdf).

## Pipeline
1. Data Preprocessing: Text cleaning, tokenization, and handling of imbalanced data.
2. Model Training: Implementation of multiple models to classify the dialect.
3. Evaluation: Macro-F1 score used to evaluate model performance.

## Results
- Random Forest: 65% Macro-F1
- FastText: 80% Macro-F1
- LSTM: 82% Macro-F1 (3 epochs)
- AraBERT: 87% Macro-F1 (2 epochs)

## Deployment
The trained model can be further deployed to classify Arabic dialects in real-time applications.
