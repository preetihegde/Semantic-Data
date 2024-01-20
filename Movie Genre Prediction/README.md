### Movie genre prediction 
  - is a task in natural language processing and machine learning where algorithms are trained to classify a given movie into one or more predefined genres based on its textual information.

### DataSet
`train_data.zip`  contains the training file used for this task
The dataset typically includes information such as movie titles, genres, and descriptions. The dataset contains a varied amount of genres such as Drama, Horror, Comedy, etc...

### Data Preprocessing
The preprocessing steps played a crucial role in enhancing the quality of the input data for model training. These steps included stemming, lemmatization, removal of punctuation, and elimination of stopwords. Stemming and lemmatization aimed to reduce words to their root forms, while the removal of punctuation and stopwords helped streamline the textual data, allowing the models to better discern meaningful patterns.

### Models
Several models were employed for the movie genre prediction task, namely Logistic Regression, Random Forest, Support Vector Machine (SVM), and Multinomial Naive Bayes. These models were trained and evaluated based on their accuracy in predicting the correct genres for the given movies.

Upon analysis, Logistic Regression emerged as the top-performing model, achieving the highest accuracy of 58.28%, closely followed by SVM with an accuracy of 58.25%. Random Forest lagged at 49.26%, and Multinomial Naive Bayes achieved a moderate accuracy of 51.50%.
