# Malicious-DoH-Traffic-Prediction
#### With the help of MI(Mutual Information) and GA(Genetic Algorithm) Feature Selection methods, a CIC(Canadian Institute for Cybersecurity) dataset was filtered and used to train several Machine Learning Models such as Random Forest Classifer, Decision Tree Classifier, K-Nearest Neighbours Classifier and Logistic Regression Classifier.
#### All the models were then compared to each other on accuracy measures such as Accuracy_score, Precision_score, Recall_score, ROC_AUC_scores, etc. A deep learning model Artifical Neural Network(ANN) was also trained with the feature selected dataset, and at last compared with the other ML models. 
#### The result of the comparison was that Random Forest Classifier was the most accurate model followed by Decision Tree Classifier with MI and GA feature selected dataset, whereas on the original feature dataset, Decision Tree Classifier showed the most accurate results.
#### The libraries used are:
1. numpy
2. pandas
3. matplotlib.pyplot (for graph plotting)
4. sklearn (for Mutual Information and all the ML models)
5. tensorflow (for ANN model)
6. genetic_selection (for Genetic Algorithm)
