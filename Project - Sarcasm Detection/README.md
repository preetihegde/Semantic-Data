We intend to build a model for Detecting Sarcasm. The Dataset focuses on headlines from reputable news sources— TheOnion for sarcastic content and HuffPost for non-sarcastic content. This approach ensures higher data quality, reduced noise, and improved contextual analysis, as the headlines are professionally written and self-contained, providing a more reliable foundation for sarcasm detection models.

The Folder contains one `.ipynb` file which has code and a `.json` file which contains the dataset. We use glove.6B.50d.txt file for embedding the file is downloaded from - https://www.kaggle.com/datasets/watts2/glove6b50dtxt

### Data
Each record in the Dataset consists of three attributes:
  - is_sarcastic: 1 if the record is sarcastic otherwise 0
  - headline: the headline of the news article
  - article_link: link to the original news article. Useful in collecting supplementary data

### Model
Two different models `Bi-Directional LSTM Model` and `pre-trained BERT Model `were used with the same pre-processing steps and the results were compared.
The built model involved task involved a series of preprocessing steps, including handling contractions, converting text to lowercase, lemmatization, and punctuation removal. These processed texts were then embedded using the GloVe model. 
The experimental phase featured the training of two models: a Bidirectional LSTM model yielded a promising 83% accuracy, while the BERT pre-trained model achieved a reasonable 57% accuracy in sarcasm detection.

