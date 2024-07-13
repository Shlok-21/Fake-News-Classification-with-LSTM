# Fake News Classifier with LSTMs

This project is my exploration into building a model to classify news articles as real or fake using Long Short-Term Memory (LSTM) networks.

## What I Learned

I explored the capabilities of LSTMs in capturing sequential information within text data. This project provided a hands-on experience to understand the intricacies of:

- **Data preprocessing**: The importance of cleaning, tokenizing, and padding text data for effective model training.
- **LSTM architecture**: Experimenting with different LSTM configurations to optimize performance.
- **Model evaluation**: Assessing the model's accuracy, precision, recall, and F1-score to gauge its effectiveness.

## Cheatsheet

### Overall Process to Build a Network from Scratch

1. **Data Collection**
   - Gather a dataset containing labeled news articles (real or fake).

2. **Data Preprocessing**
   - Clean the text data (remove special characters, lowercasing, etc.).
   - Tokenize the text (convert words to numerical tokens `one_hot` ).
   - Pad sequences to ensure uniform input size for the LSTM network.

3. **Building the LSTM Model**
   - Import necessary libraries (e.g., TensorFlow, Keras).
   - Initialize the model.
   - Add an embedding layer to convert tokens into dense vectors of fixed size.
   - Add one or more LSTM layers to capture sequential patterns.
   - Add dense layers for classification.

4. **Compiling the Model**
   - Choose an appropriate optimizer (e.g., Adam).
   - Select a loss function (e.g., binary cross-entropy for binary classification).
   - Define metrics for evaluation (e.g., accuracy).

5. **Training the Model**
   - Split the data into training and validation sets.
   - Train the model using the training data.
   - Monitor the model's performance on the validation set.

6. **Evaluating the Model**
   - Assess the model's performance using metrics such as accuracy, precision, recall, and F1-score.
   - Generate a classification report and confusion matrix for detailed analysis.
