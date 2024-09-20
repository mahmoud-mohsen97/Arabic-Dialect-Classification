# Arabic Dialect Classification

This NLP project focuses on predicting the dialect of Arabic texts using advanced machine-learning techniques. Using random forest and Fasttext and LSTM and Transformer models, the project aims to classify Arabic dialects accurately. As the Arabic language is known for its complex grammar and varied letter formations, NLP problems related to Arabic are particularly challenging. Moreover, with numerous countries speaking the language, each country has its unique dialect. Therefore, this project aims to develop a robust model that accurately predicts the dialect based on the input text.

## Dataset
The dataset utilized in this project is a collection of Arabic sentences labeled with their corresponding dialects from five distinct countries, namely Egypt ('EG'), Lebanon ('LB'), Libya ('LY'), Sudan ('SD'), and Morocco ('MA'). It is worth noting that the dataset is imbalanced, with the majority of the data originating from the 'EG' dialect. You can find the original paper of the dataset [here](https://arxiv.org/pdf/2005.06557.pdf).

## Deliverables
1. Data Fetching 
2. Data Preprocessing 
3. Model Training 
4. Deployment 

## Results
for Macro-F1 score:
- The Random Forest Model = 65%
- The fasttext Model = 80%
- The LSTM Model (3 epochs) = 82% 
- The Arabert (transformer) Model (2 epochs) = 87%
