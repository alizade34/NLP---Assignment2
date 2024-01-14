
# Wikipedia Article Classification Project

This project aims to classify Wikipedia articles into medical and non-medical categories using Natural Language Processing (NLP) techniques. The classification is performed based on the textual content of the articles.

## Project Structure

### Data Collection

Wikipedia articles are collected using the Wikipedia API.

Two categories, medical and non-medical, are chosen to create a labeled dataset.

### Text Preprocessing

Text from Wikipedia articles is preprocessed using NLTK for tasks such as tokenization, stemming, and stop-word removal.

HTML tags and special characters are removed to clean the text.

### Feature Extraction

Bag of Words (BoW) representation is used to convert text data into numerical vectors.

CountVectorizer from scikit-learn is employed for feature extraction.

### Model Training

Multinomial Naive Bayes and Logistic Regression classifiers are trained on the labeled dataset.

### Evaluation

Model accuracy and classification reports are generated to evaluate the performance of the classifiers.

## Dependencies

1. `wikipedia`
2. `requests`
3. `nltk`
4. `scikit-learn`

## Usage

To run the project, follow these steps:

1. Install the required dependencies using the following command:

    ```bash
    pip install wikipedia requests nltk scikit-learn
    ```

2. Run the main script for data collection, text preprocessing, feature extraction, model training, and evaluation.

    ```bash
    python main.py
    ```


# NLP---Assignment2
>>>>>>> 541b2a423b967f87ced6ab47f9390d1b96299464
