
**📊 Twitter Sentiment Analysis (LSTM)**

This project analyzes tweets and predicts whether the sentiment is positive or negative using an LSTM (Long Short-Term Memory) neural network.

**Features**
Preprocessed tweet text using NLP techniques
Tokenized and padded sequences for deep learning
Built LSTM model for sequence learning
Trained model on large Twitter dataset
Evaluated performance on test data
**📂 Dataset**
Dataset: Sentiment140 (Kaggle)
Contains 1.6 million tweets
**Labels:**
0 → Negative
1 → Positive
**🛠️ Technologies Used**
Python
Pandas, NumPy
NLTK
TensorFlow / Keras
**⚙️ Project Workflow**
Data Collection
Dataset downloaded from Kaggle
Data Preprocessing
Lowercasing text
Removing URLs, mentions, punctuation
Tokenization
Stopword removal
Text Encoding
Tokenizer used to convert text into sequences
Padding applied to make equal length sequences
Model Building
Embedding Layer
LSTM Layer
Dense Output Layer
Model Training
Trained on training dataset
Validated on test dataset
Evaluation
Accuracy and loss metrics used
**🧠 Model Architecture**
Embedding Layer
LSTM Layer
Dense Layer with activation function
**📈 Results**
LSTM captures sequence and context better
Improved performance compared to traditional ML models
Suitable for real-world sentiment analysis
