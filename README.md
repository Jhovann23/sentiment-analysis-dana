# Sentiment Analysis - DANA App Reviews

## 📌 About The Project

This project focuses on performing sentiment analysis on user reviews of the DANA digital wallet application. The purpose of this project is to analyze user opinions and classify reviews based on their sentiment.

The dataset consists of user reviews collected from the DANA application, containing various feedback regarding the application's features, performance, transactions, and overall user experience.

Through text preprocessing and sentiment analysis, the reviews are processed and transformed into structured data that can be used to identify positive and negative user sentiments.

## 🎯 Objectives

The objectives of this project are:

- Analyze user reviews of the DANA application.
- Perform text preprocessing on Indonesian-language reviews.
- Clean and normalize the review text.
- Classify user reviews based on their sentiment.
- Gain insights into user opinions and experiences with the DANA application.

## 📊 Dataset

The dataset contains user reviews of the DANA application.

Some of the attributes include:

- `score` — User rating given to the application.
- `thumbsUpCount` — Number of users who found the review helpful.
- `reviewCreatedVersion` — Application version when the review was created.
- `at` — Date and time when the review was created.
- `replyContent` — Response from the application developer.
- `repliedAt` — Date and time of the developer's response.
- `appVersion` — Application version.
- `text` — Original user review.

Additional columns are generated during the preprocessing stage.

## 🔄 Text Preprocessing

The review text goes through several preprocessing steps before sentiment analysis.

The preprocessing stages include:

1. **Text Cleaning**  
   Removing unnecessary characters, symbols, URLs, and other noise from the review.

2. **Case Folding**  
   Converting all text into lowercase to ensure consistency.

3. **Slang Word Normalization**  
   Converting Indonesian slang or informal words into their standard forms.

4. **Tokenization**  
   Splitting sentences into individual words or tokens.

5. **Stopword Removal**  
   Removing words that provide little meaning for the sentiment analysis.

6. **Stemming**  
   Converting words into their root forms.

## 🧠 Sentiment Analysis

After preprocessing, the cleaned review data is used for sentiment analysis.

The sentiment classification is performed to identify whether a review expresses:

- 😊 Positive sentiment
- 😐 Neutral sentiment
- 😡 Negative sentiment

The results can then be analyzed to understand the overall perception of DANA users.

## 🛠️ Technologies

This project was developed using:

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Sastrawi
- Matplotlib
- Seaborn
- Scikit-learn

## 📈 Analysis

The processed data can be used to perform various analyses, such as:

- Sentiment distribution
- Most frequently used words
- Comparison between rating and sentiment
- User feedback trends
- Common complaints and positive feedback

## 🚀 How to Run

You can run this project using Google Colab or Jupyter Notebook.

1. Clone this repository.
2. Open the `.ipynb` notebook.
3. Upload or provide the required dataset.
4. Run the notebook sequentially from the preprocessing stage to the sentiment analysis stage.


```text
sentiment-analysis-dana/
│
├── sentiment_analysis_dana.ipynb
├── dataset/
│   └── dana_reviews.csv
├── README.md
└── requirements.txt