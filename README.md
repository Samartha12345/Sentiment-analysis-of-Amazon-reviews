# Sentiment-analysis-of-Amazon-reviews
📄 Description :-This project focuses on building a Natural Language Processing (NLP) model to classify the sentiment of Amazon food reviews as positive or negative. The model employs a combination of advanced text preprocessing techniques, insightful visualizations, and machine learning algorithms to achieve high accuracy.
Model uses LSTM as well as Simple RNN to test which gives better results.

🚀 Features:- 
Data Handling:
Data loading and cleaning using pandas.
Text preprocessing (lowercasing, tokenization, padding sequences).

Model Architecture:
Embedding layer for word embeddings.
SimpleRNN layer for sequential data processing.
Dense layer with softmax activation for multi-class classification.

Training and Evaluation:
Splitting data into training and testing sets.
Training model with validation split and batch processing.
Evaluating model performance with confusion matrix and classification report.
LSTM Layer: Replaced the SimpleRNN layer with LSTM(64), which is better suited for capturing long-term dependencies in sequential data.

💻 Tech Stack:
Programming Language: Python
Libraries: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, Keras

Results:
Achieved Accuray of 89% using Simple RNN Model


