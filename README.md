# Sms Spam Detection Nlp

SMS spam detection comparing classic ML, RNN/LSTM/GRU and fine-tuned BERT.

## What it does

Complete spam detection pipeline: EDA, text preprocessing, TF-IDF with classic classifiers, deep learning models (SimpleRNN, LSTM, GRU, BiLSTM), BERT fine-tuning and an LLM explanation engine with a Gradio demo.

## Files

- `sms_spam_detection.ipynb`

## Tools

scikit-learn, TensorFlow, PyTorch, Hugging Face Transformers, sentence-transformers, FAISS, LangChain, Gradio, NLTK

## Dataset

[SMS Spam Collection (Kaggle)](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

The dataset is not included in this repo.

## Results

From the saved notebook outputs:

Random Forest: accuracy 0.9868, spam F1 0.948 | Linear SVM: 0.9677 / 0.884 | Logistic Regression: 0.9665 / 0.879 | SimpleRNN: accuracy 0.970, F1 0.892.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
