# Classify Electric Moped Reviews - Rating classification practical project using Machine Learning and Neural Network.

The goal of this project is to develop a model that can predict whether the ratings came from owners or non-owners of the mopeds.
I used models of machine learning algorithms and neural networks to achieve this.

Background

EMO is a manufacturer of electric motorcycles. EMO launched its first electric motorcycle in India in 2019.
The product team has been asking website users to rate the motorcycles. 
The product team wants to extend the survey. But they want to be sure they can predict whether the ratings came from owners or non-owners.

Dataset

I used a publicly available dataset from Data Camp.  The dataset contains rating information about mopeds collected by the product team and has 1500 rows and 8 columns.
The dataset includes information such as the reviewer owns the moped or not, review month, web browser used by the user leaving the review, reviewer age, 
value for money, overall rating.

Data Pre-processing

I performed several pre-processing steps to prepare the data for classification. This included replacing missing values, converting data type,
scale the  features values and feature selection.

Model Selection and Training

I experimented with two machine learning algorithms, Logistic Regression and Gradient Boosting Classifier. 
I also used MLPClassifier and I developed a neural network model using TensorFlow. 
I evaluated the models using cross-validation and selected the best-performing model for further optimization.

Model Optimization

I used grid search to tune the hyperparameters of the selected models, including penalty, learning rate and max depth. 

Results

The best model was MLPClassifier who achieved an accuracy of 75% on the test set. The model was particularly effective at identifying reviews received from
owners of the mopeds, achieving an F1 score of 0.79.
