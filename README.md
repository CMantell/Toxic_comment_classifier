## About The Project

This project is a NLP Kaggle competition about classifying probabilities on a multi-labeled dataset of toxic comments.  Our team of roughly six members started this project on 1/26/18 and we worked on the project roughly once a week.  The competition ends on 3/20/18.

### Importance Of The Project 

While the Internet can facilitate healthy debate on message boards, there is a huge concern about abuse and harassment in the form of extremely hurtful comments.  Although comment moderators can delete and inform users of breeches of decency and rules for posting comments, these moderators are mostly overwhelmed by the large volume of comments to review.  There are classification models that already exist but they still make errors and do not have the capability to filter out by type of toxic comment.  This would be useful in cases where profantiy is allowed but threats are not.  Therefore, a classification system to detect toxic comments and the type of toxic comment would prove very useful.  

## Project Overview

An Extreme Gradient Boosted (XGBoost) decision tree classifier was built to classify toxic comments using a data set of about 160,000 rows of comments from Wikipedia talk page edits.  This data was multi-labeled across six different binary classes, making each row have only one correct answer out of 64 possible answers.  My model had an accuracy of nearly 92% for correctly classifying these multi-labeled answers and a ROC AUC of 0.9697 for a submission to a Kaggle competition (less than 0.02 than the leader).

> 1. Data acquisition and EDA are in the notebook titled **CMantell_Toxic_Comment_Classification1.**  I plan to use this notebook to explore preprocessing, feature extraction, and feature engineering.  This notebook will also include different models in the future.

> 2. The notebook titled **XGboost model** contains the code for an XGBoosted decision tree classifier.  The data was preprocessed with a TFIDF vectorizer.  I plan to explore the difference between this XGBoosted model versus scikit-learn's GradientBoosted decision tree classifier with predictive performance. 

Last edited: 2/14/18

Contact the author with any questions @ chris.mantell@gmail.com
