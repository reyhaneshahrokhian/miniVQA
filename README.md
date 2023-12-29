# IUST-VQA
A simple project derived from miniVQA dataset. The main purpose of this project is providing a simple example of visual question answering tasks. You are expected to implement four models which elaborated upon hereunder.
- Competition Link: [link](https://www.kaggle.com/competitions/minivqaiust/overview)
1. At this part you need to use embedding vectors (word2vec, fasttext) of words in questions as input to a LSTM network. After utilizing information from question, concatenate output data with image features and pass it through a dense layer. Then use a classification function and output a final answer.

2. Now try to extract information from questions with transformer models (distilBERT, BERT, etc).

3. Same as part 1 use LSTM and word embeddings for questions. And use transformers for cross attention between image features and text features.

4. Consider combination of parts 2 and 3. Extract information of questions with transformers and then use cross attention for combination of image and text. Finally, add a classification layer to output the true label.
