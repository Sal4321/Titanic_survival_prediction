# Titanic_survival_prediction
Survival prediction from Titanic Dataset. The dataset has been extracted from Kaggle. The goal was to predict survival given the features of passengers.
My approach: 
1st step: Analyze and plot categorical and numerical data

2nd step: dealt with missing values and created new features.

3rd step: Built 4 set of features (raw features, cleaned raw featres, all cleaned features and reduced clean features). Divided each sets of features to train, test and validation sets

4 th step: Used Random Forest to train the all of the models and used gridsearch cv to select best parameters from each sets of features.

5th step: Compared performance of each model on validation datasets and found precision, recall , accuracy and latency of the models. Models with all features turned out to be the best model with 2nd best latency(16 ms) and highest accuracy (83%), and highest precidion and recall.

I got around 80% accuracy on unseen test set using the model with all features.

More works on improving the model will be done in future by including baging/boosting algorithms

The trained models are included as .pkl


