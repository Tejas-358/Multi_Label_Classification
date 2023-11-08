# Multi-Label Text Classification with Deep Learning

This repository contains code for a text classification model built with deep learning techniques. The model takes user input text and predicts labels associated with it. It uses a pre-trained deep learning model and a text preprocessing pipeline to make predictions.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following dependencies installed:

- Python (>= 3.6)
- Required Python libraries (Keras, NLTK, NumPy, scikit-learn, etc.)
- Pre-trained model file (`model5.h5`)
- Tokenizer file (`tokenizer.pkl`)
- MultiLabelBinarizer file (`mlb5.pkl`)

### Installing

1. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/your-username/text-classification.git
Install the required Python libraries:

bash
Copy code
pip install -r requirements.txt
Place the pre-trained model (model5.h5), tokenizer (tokenizer.pkl), and MultiLabelBinarizer (mlb5.pkl) files in the project directory.

Run the script:

bash
Copy code
python predict_labels.py
Usage
The text_preprocessing function is used to preprocess the input text. It removes non-ASCII characters, Roman numerals, punctuation, digits, and stopwords.

The predict_labels_for_text function predicts labels for the provided text. It preprocesses the text, tokenizes it, and uses the pre-trained model to make predictions.

When running the script, you can input text, and the script will output the predicted labels for that text based on the pre-trained model.

Configuration
You can adjust the following parameters in the code:

threshold: You can adjust the threshold for label prediction probability.

max_sequence_length: You can adjust the maximum sequence length for padding input sequences.
