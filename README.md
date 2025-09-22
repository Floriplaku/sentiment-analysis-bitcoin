## Project Title: Bitcoin Tweet Sentiment Analysis

##### TL;DR: Comparative sentiment analysis of Bitcoin tweets using dictionary (VADER), RNN, and Transformer models. Fine-tuned DistilBERT achieves the best performance, striking a balance between accuracy and computational efficiency.

##### Description
This project performs sentiment analysis on a dataset of Bitcoin-related tweets. The analysis uses various Natural Language Processing (NLP) techniques/approaches:
1. Sentiment dictionary (VADER)
2. Recurrent Neural Network (RNN)
3. Pre-trained DistilBERT model
4. Fine-tuned DistilBERT model.

##### Features
- **Preprocessing:** Cleaned and prepared tweets by removing HTML tags, URLs, user mentions, hashtags, unnecessary characters, convert emoji to text etc.
- **Sentiment Analysis:** Applied four different sentiment analysis approaches.
- **Model Evaluation:** Evaluated models using accuracy, confusion matrices, and other classification metrics.

##### Installation

###### Prerequisites
- **Python 3.12.3**
- Jupyter Notebook or JupyterLab


##### Usage
##### Data Preprocessing
The notebook includes comprehensive data preprocessing steps for each model:

- Sentiment dictionary (VADER): Basic text cleaning and preparation for rule-based analysis.
- RNN: Extensive preprocessing including tokenization, stemming, lemmatization etc-.
- DistilBERT: Text cleaning focused on removing irrelevant information like URLs and user mentions.

##### Model Training and Evaluation
The notebook contains sections dedicated to:
- Training the RNN model and fine-tuning the DistilBERT model.
- Evaluating each model's performance using metrics like accuracy, confusion matrix, and ROC-AUC.
- Comparing the models' performance to identify the most effective approach.

##### Results
The notebook compares the four sentiment analysis approaches in terms of accuracy and other performance metrics. Key observations include:

- VADER's efficiency and speed make it a solid choice for quick sentiment analysis.
- The RNN model struggles with complexity and overfitting
- DistilBERT models, particularly when fine-tuned, show strong performance in sentiment classification.

##### This project demonstrates the strengths and weaknesses of different sentiment analysis techniques. Fine-tuned DistilBERT emerges as the most effective model, balancing computational efficiency with high accuracy

##### Contact:
For any questions or feedback, please contact Florian Plaku at florian.plaku@student.hu-berlin.de.
- Author: Florian Plaku
- GitHub: https://github.com/Floriplaku
- Email: florian.plaku@student.hu-berlin.de
- LinkedIn:https://www.linkedin.com/in/florian-plaku-229891121/


