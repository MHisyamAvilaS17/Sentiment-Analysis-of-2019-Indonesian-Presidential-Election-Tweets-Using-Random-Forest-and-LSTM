# Sentiment-Analysis-of-2019-Indonesian-Presidential-Election-Tweets-Using-Random-Forest-and-LSTM
This project analyzes public sentiment on the 2019 Indonesian Presidential Election using Random Forest and LSTM Algorithm. The dataset consists of tweets related to the election, which are processed through text preprocessing, vectorization (TF-IDF &amp; Word2Vec), and classification models.

🚀 Key Features

1. Text Preprocessing: Includes tokenization, stopword removal, stemming, lemmatization using KBBI, and Named Entity Recognition (NER).

2. Feature Extraction: Implements TF-IDF and Word2Vec for vectorization.

3. Model Training: Uses Random Forest and LSTM with hyperparameter tuning.

4. Performance Evaluation: Metrics include Accuracy, Precision, Recall, and F1-Score.

5. Model Testing: Evaluates the performance of Random Forest and LSTM models on sentiment classification tasks


🔧 Installation

1. Clone the repository:
git clone https://github.com/MHisyamAvilaS17/Sentiment-Analysis-of-2019-Indonesian-Presidential-Election-Tweets-Using-Random-Forest-and-LSTM.git
cd sentiment-analysis

2. Install dependencies:

pip install -r requirements.txt

3. Prepare the dataset(tweet.csv)


📜 More Information

The combination between LSTM and TF-IDF vectorization was not included in this code, as LSTM requires sequential data input, making it incompatible with TF-IDF features. Additionally, this combination yielded the lowest accuracy during preliminary tests.
