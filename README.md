# Stock-Price-Movement-Prediction-using-News-Headlines

Problem Statement : Prediction of Stock Price Movement based on top 25 News Headlines.

Methadology used : NLP. Post Cleaning the news headlines for irrelevant non-characters and stopwords, it is converted into vectorized format using BAG OF WORDS model. Then this data is used to train RandomForest Classifier model and Bernoulli Naive Bias Model.
                   Bernoulli is selected out of all Naive Bias models because vectorized data contains only 0 and 1. 
                   
Hyperparameter Tuning: to reduce calculation time and to remove redundant features, max_feature is then set to 50,000 for BAG OF WORDS model.

Conclusion: The model accuracy increased by 1 percent with reduced number of features, and calculation time too reduced. Naive-Bias Bernoulli model gave best test accuracy of 86 percent.
