# Persian Question Answering System using BERT and TF-IDF
This project is a complete question and answer system that uses pre-trained BERT, XLM-RoBERTa and other pretrained networks and also TF-IDF models to find the exact answer to a user's question in Persian text. The system uses the PQUAD dataset, which is similar to SQUAD but with Persian text.
The input of this project is a question, and the exact answer to that question is found and returned through the following steps:
1- Finding the document related to the user's question
2- Finding the paragraph related to the user's question
3- Finding the exact answer from the selected paragraph using Machine Reading Comprehension

## Requirements
Python 3.6 or higher
PyTorch 1.7 or higher
transformers 4.2.2 or higher
scikit-learn 0.24.2 or higher
pandas 1.1.5 or higher
tqdm 4.59.0 or higher
