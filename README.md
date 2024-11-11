This project classifies messages as either "spam" or "ham" (not spam) using Natural Language Processing (NLP) techniques. By implementing an LSTM (Long Short-Term Memory) neural network, we aim to accurately filter out unwanted messages, enhancing the user experience in various communication platforms.

**Methodology**
1. Data Collection: Dataset of SMS messages labeled as "spam" or "ham."
2. Data Preprocessing:
3. Text Cleaning: Removing unwanted characters, lowercasing, and basic preprocessing.
4. Tokenization: Using Keras’s Tokenizer to convert text into sequences of integer tokens.
5. Padding: Ensuring all sequences have the same length for model compatibility.

**6. Model Building:**
Constructed an LSTM model with embedding layers for learning word relationships in sequences.
Compiled with binary cross-entropy loss and the Adam optimizer.
Model Training: Trained the LSTM model on tokenized and padded sequences for spam-ham classification.
Evaluation: Measured accuracy, precision, recall, and F1-score to assess model performance. 
