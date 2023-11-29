# Kaggle-Competition-NLP-disasterTweets

Competition Overview:

🚀 Welcome to my submission for the Kaggle competition "Natural Language Processing with Disaster Tweets." In this challenge, we delve into the fascinating world of tweets, leveraging Natural Language Processing (NLP) to distinguish between tweets about real disasters and those that aren't. The objective is to create a robust model that excels in predicting disaster-related content.

Solution Highlights:

🔍 Data Exploration & Preprocessing:

Meticulous handling of missing values, including the creation of a 'has_location' binary feature.
Strategic handling of NaN values in the 'keyword' column, ensuring data integrity.

✨ Text Preprocessing Mastery:

Utilized NLTK for advanced text preprocessing, encompassing URL removal, special character handling, punctuation removal, tokenization, and stemming.

🌐 Feature Extraction with TF-IDF:

Extracted meaningful features from processed text using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
Ensured the model comprehends the significance of each word in tweets.

🚄 Modeling with SVM:

Employed a robust Support Vector Machine (SVM) model for classification.
Fine-tuned hyperparameters using GridSearchCV, optimizing the SVM configuration.

Achievements:

🏆 Attained an impressive F1 score of 0.79926 on the public leaderboard.
🌟 Demonstrated the efficacy of SVM in accurately identifying disaster-related tweets.

Next Steps:

Open to collaborative discussions and feedback for continuous improvement.
🙌 Happy coding! 🚀📊 #NLP #KaggleCompetition #DisasterTweetsPrediction #DataScienceWin
