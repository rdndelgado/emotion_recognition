**Dataset name**: user_reviews.csv  
**Dataset URL**: [https://www.kaggle.com/code/mmmarchetti/play-store-sentiment-analysis-of-user-reviews/input?select=user_reviews.csv](https://www.kaggle.com/code/mmmarchetti/play-store-sentiment-analysis-of-user-reviews/input?select=user_reviews.csv)  
**Total participants**: 7486

**Preprocessing techniques applied**:
- Handling missing values (NaN)
- Tokenization
- Stopwords Removal
- Lemmatization
- Punctuation Removal
- Whitespace Removal
- Feature Labelling
- Word Vectorization

**Type of Modality**: Linguistics modality (text)  
**Type of emotion recognition model used**: Discrete emotion model  
**ML algorithm used**: SVC (Support Vector Classifier)


**Libraries/Tools used**:
- _Pandas_: Used for preprocessing techniques
- _Spacy_: Used for preprocessing techniques
- _String_: Used for preprocessing techniques
- _nltk.sentiment.vader (SentimentIntensityAnalyzer)_: Used for sentiment analysis of the reviews and data labeling
- _TfidfVectorizer_: Used for word vectorization for ML algorithm training
- _Sklearn_: Used for training and evaluating SVC algorithm
- _SVC_: Used for classifying emotion of the reviews

