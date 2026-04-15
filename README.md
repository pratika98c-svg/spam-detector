# Email Spam Detector

A beginner machine learning project that detects 
spam messages using Naive Bayes classification.

 About The Project
This project classifies SMS messages as spam or ham 
(not spam) using the Multinomial Naive Bayes algorithm.
Built as part of learning Classical Machine Learning 
during my university coursework.

The model is trained on real SMS data and achieves 
97-99% accuracy on test data.

 Libraries Used
- Pandas - loading and managing the dataset
- Scikit-learn - building and training the ML model
- NLTK - text preprocessing and stopwords removal
- Matplotlib - data visualization
- Re - cleaning text using regular expressions

Dataset
SMS Spam Collection Dataset
- 5572 real SMS messages
- Labeled as spam or ham (not spam)
- 4825 ham messages and 747 spam messages

 How It Works
1. Load the SMS dataset
2. Clean the text - lowercase, remove punctuation, 
   remove stopwords
3. Convert text to numbers using CountVectorizer
4. Train Multinomial Naive Bayes model
5. Evaluate accuracy on test data
6. Test with custom messages

 Results
- Accuracy: 97-99%
- Algorithm: Multinomial Naive Bayes
- Train/Test Split: 80/20

 How To Run
1. Open the notebook in Google Colab
2. Run all cells in order (Cell 1 to Cell 8)
3. Type your own message in Cell 8 to test

 What I Learned
- Text preprocessing using NLTK
- Converting text to numbers using CountVectorizer
- Training and evaluating a Naive Bayes classifier
- Understanding spam vs ham classification
- Handling imbalanced datasets

