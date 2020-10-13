# Cryptocurrencies
### CHALLENGE




# APPENDIX - Module 17 Challenge - APPENDIX

Jill commends you for all your hard work. Piece by piece, you have been building up your skills in data preparation, statistical reasoning, and machine learning.

You are now ready to apply machine learning to solve real-world challenges.
In this challenge, you’ll build and evaluate several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company.

**Background** 
Credit risk is an inherently unbalanced classification problem, as the number of good loans easily outnumber the number of risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Your final task is to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

**Objectives**
The goals of this challenge are for you to:

- Implement machine learning models.
- Use resampling to attempt to address class imbalance.
- Evaluate the performance of machine learning models.

**Instructions**

You’ll use the **imbalanced-learn** library to resample the data and build and evaluate logistic regression classifiers using the resampled data. Download the files you’ll need, which include starter code and the dataset:

Download Module -17-Challenge-Resources.zip

You will:

- Oversample the data using the RandomOverSampler and SMOTE algorithms.
- Undersample the data using the cluster centroids algorithm.
- Use a combination approach with the SMOTEENN algorithm.


For each of the above, you’ll:

- Train a logistic regression classifier (from Scikit-learn) using the resampled data.
- Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
- Generate a confusion_matrix.
- Print the classification report (classification_report_imbalanced from imblearn.metrics).
- Lastly, you’ll write a brief summary and analysis of the models’ performance. Describe the precision and recall scores, as well as the balanced accuracy score. Additionally, include a final recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

### Extension
For the extension, you’ll train and compare two different ensemble classifiers to predict loan risk and evaluate each model. Note that you’ll use the following modules, which you have not used before. They are very similar to ones you’ve seen: 
- BalancedRandomForestClassifier and EasyEnsembleClassifier, both from imblearn.ensemble. 
These modules combine resampling and model training into a single step. Consult the following documentation for more details:

- Section 5.1.2. Forest of randomized trees (Links to an external site.)
- imblearn.ensemble.EasyEnsembleClassifier (Links to an external site.)

Use 100 estimators for both classifiers, and complete the following steps for each model:

- Train the model and generate predictions.
- Calculate the balanced accuracy score.
- Generate a confusion matrix.
- Print the classification report (classification_report_imbalanced from imblearn.metrics).
- For the BalancedRandomForestClassifier, print the feature importance, sorted in descending order (from most to least important feature), along with the feature score.
- Lastly, you’ll write a brief summary and analysis of the models’ performance. Describe the precision and recall scores, as well as the balanced accuracy score. Additionally, include a final recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

