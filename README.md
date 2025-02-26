# Next Word Prediction using LSTM

## Overview
This project builds a Next Word Prediction model using Long Short-Term Memory (LSTM), a type of recurrent neural network (RNN). The model is trained on a text dataset to predict the next word given a sequence of words.

## Features
- Tokenizes and preprocesses text data.
- Uses an embedding layer to represent words.
- Implements LSTM layers to capture sequence dependencies.
- Outputs the most likely next word.
- Evaluates model performance using accuracy and BLEU score.

## Requirements
- Python 3.x
- TensorFlow/Keras
- NumPy
- Pandas
- NLTK

## Installation
```sh
pip install tensorflow numpy pandas nltk
```

## Usage
1. Prepare and preprocess a text dataset.
2. Train the LSTM model on tokenized text sequences.
3. Input a seed text to predict the next word.
4. Evaluate the model's performance.

## Example
```python
input_text = "Sherlock Holmes is"
predicted_word = model.predict_next_word(input_text)
print("Predicted word:", predicted_word)
```

## Results
The model generates relevant next-word predictions based on learned patterns from the dataset.

## Future Improvements
- Train on larger datasets for better accuracy.
- Fine-tune hyperparameters.
- Implement attention mechanisms for improved predictions.

## License
MIT License
