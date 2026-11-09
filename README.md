# Arabic Sentiment Analysis

> Classifies the sentiment of Arabic tweets (positive, negative, neutral, mixed) with an LSTM neural network.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Overview

An end-to-end NLP experiment on Arabic social-media text:

1. Load the ArSAS tweet corpus and explore the label distribution.
2. Clean and tokenize the Arabic text, then pad the sequences.
3. Train an `Embedding → LSTM → Dense` classifier with Keras.
4. Evaluate on a held-out test split.

Arabic sentiment is a hard problem (dialects, sarcasm, short texts). This notebook is a baseline that can be improved with Arabic word embeddings or a pretrained transformer such as AraBERT.

## Files

| File | Description |
| --- | --- |
| `sentiment_analysis.ipynb` | Data loading, preprocessing, model training and evaluation |
| `ArSAS.txt` | ArSAS dataset (tweet text, topic, sentiment label) |

## Run it

```bash
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook sentiment_analysis.ipynb
```

## Dataset

ArSAS: *An Arabic Speech-Act and Sentiment Corpus of Tweets* (Elmadany, Mubarak & Magdy, 2018). It is included for reproducibility. All credit goes to the original authors.

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
