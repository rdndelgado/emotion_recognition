Dataset name: user_reviews.csv

Dataset url: https://www.kaggle.com/code/mmmarchetti/play-store-sentiment-analysis-of-user-reviews/input?select=user_reviews.csv

Total participants: 7486

Preprocessing techniques applied:

- Handling missing values (NaN)
- Tokenization
- Stopwords Removal
- Lemmatization
- Punctuation Removal
- Whitespace Removal
- Feature Labelling
- Word Vectorization

Type of Modality: Liguistics modality (text)
Type of emotion recognition model used: Discrete emotion model
ML algorithm used: SVC (Support Vector Classifier)

Libraries/Tools used:

pandas - Used for preprocessing techniques
spacy - Used for preprocessing techniques
string - Used for preprocessing techniques
nltk.sentiment.vader (SentimentIntensityAnalyzer) - Used for sentiment analysis of the reviews and data labelling
TfidfVectorizer - Used for word vectorization for ML algorithm training
sklearn - Used for training and evaluating SVC algorithm
SVC - Used for classifying emotion of the reviews

