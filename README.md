# Bilingual NLP Sequence Classification

This project was developed as part of CPC353 (Natural Language Processing) coursework. The goal is to build and evaluate models for sequence classification tasks across **English, Malay** datasets.

## 📂 Project Overview
- **Languages Covered**: English, Malay
- **Tasks**:
  - Data loading and preprocessing
  - Tokenization with `TweetTokenizer`
  - Sequence padding
  - Model training and evaluation

## ⚙️ Features
- **Data Preprocessing**
  - Handles train, dev, and test datasets
  - Tokenization and sequence padding
- **Modeling**
  - Implemented NN/LSTM-based models -> **Siamese Neural Network**
  - Trained with GPU for efficiency
- **Evaluation**
  - Reports accuracy, loss, and performance metrics on test data

## 🛠️ Tech Stack
- Python  
- NLTK (TweetTokenizer)  
- TensorFlow / Keras (for deep learning models)  
- NumPy, Pandas  

## 🚀 Usage
1. Place datasets (`train.en`, `train.my`, `train.cl`, `dev.en`, etc.) in the working directory.
2. Update dataset paths inside the notebook if necessary.
3. Run the Jupyter Notebook (preferably with GPU runtime).
4. Evaluate the trained model on test datasets.

## 📊 Results
- Achieved competitive performance across bilingual datasets.
- Demonstrated effective preprocessing and sequence modeling techniques.
