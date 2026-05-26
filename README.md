# Next Word Predictor using LSTM & GRU

## Overview

This project is a Deep Learning based Next Word Prediction system built using LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) networks.
The model is trained on Shakespeare's Hamlet dataset from the NLTK Gutenberg corpus and predicts the next probable word for a given text sequence.

The project also includes a Streamlit web application for interactive next-word prediction.

---

## Features

* Text preprocessing using TensorFlow Tokenizer
* N-gram sequence generation
* Sequence padding
* LSTM based next word prediction
* GRU model implementation
* Streamlit web interface
* Model saving and loading
* Tokenizer serialization using Pickle

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* NLTK
* Streamlit
* Pickle

---

## Dataset

The dataset used in this project is:

* Shakespeare Hamlet Text
* Source: NLTK Gutenberg Corpus

---

## Project Workflow

1. Load Hamlet dataset using NLTK
2. Perform text preprocessing
3. Generate input sequences
4. Apply tokenization and padding
5. Build LSTM and GRU models
6. Train the model
7. Predict the next word
8. Deploy using Streamlit

---

## Model Architecture

### LSTM Model

* Embedding Layer
* LSTM Layer
* Dropout Layer
* LSTM Layer
* Dense Output Layer

### GRU Model

* Embedding Layer
* GRU Layer
* Dropout Layer
* GRU Layer
* Dense Output Layer

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Next_Word_Predictor_LSTM_DeepLearning.git
```

Move into the project directory:

```bash
cd Next_Word_Predictor_LSTM_DeepLearning
```

Create virtual environment:

```bash
python -m venv venv
```

Activate virtual environment:

### macOS/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Streamlit App

```bash
streamlit run app.py
```

---

## Example Prediction

Input:

```text
To be or not to be
```

Predicted Output:

```text
and
```

---

## Project Structure

```text
├── app.py
├── hamlet.txt
├── next_word_lstm.h5
├── tokenizer.pickle
├── requirements.txt
├── README.md
└── notebooks/
```


---

## Author

Vedant Uplap

---
