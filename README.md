# Text-Analytics_Basics - NLP

Problem Statement

1.	Take the first and last 10000 review texts each (creating a dataset of 20000 samples). Perform only these steps as part of pre-processing: lowercasing and removing punctuation. Compute IDF of all words in these reviews. Report the top 30 words and bottom 30 words, based on IDF, with their IDF scores.
   
2.	Take the first 10  review texts each from both the categories (20 samples in total). Perform sentence detection using Spacy (or any other toolkit). Each line should have review ID (i.e., line number from the file) and the sentence itself.
   
3.	Take the first 10  review texts each from both the categories. Perform word tokenization, lemmatization, part-of-speech tagging. Use Spacy or any other toolkit. Each line should have a review ID (i.e., line number from the file), token (i.e. word), lemma, and POS tag.
   
4.	Use the entire dataset. Take the first 80% dataset from each of the category for train and remaining 20% for test. On the train set, obtain TFIDF features (with 50K vocabulary) and learn a multinomial Naïve Bayes model. Report the accuracy on the test set for  2 setups, binary classification problem (choose 2 classes) and a five-class classification problem. Define binary classes as one class with review rating (overall) 5 and other class with all other review ratings. Take an equal sample for the other class (same number of samples as those in class with overall=5.0, if needed Accuracy should be reported as class-wise precision, recall and F1.
   
5.	Take the first 1000 “rating-1.0” reviews from each category (2000 in total). Summarize them to 1% (in terms of words) using summa and send across your summary. Also, take the first 1000 “rating-5.0” reviews from each category (2000 in total) . Summarize them to approximately 300 words using summa and send across your summary.
