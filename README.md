# HackInIndia-Team-NelsonNmurdock
# Prediction of cardiovascular diseases by building an AI pipeline using multiple ML Algorithms and using feature extraction and structuring.
In this repo we've the code for all the normal models used to predict a person has cardiovascular disease or not. And along with that the HRFLM folder has the HRFLM.py file that contains the code for hrflm algorithm along with the model tree of the normal models.

Explanation: 

We're calculating the metric loss by each of the models namely Random Forest, Decision Tree, KNN, Deep learning, and SVM's. After the metric loss is calculated the algorithm with the least metric loss is selected.
After this a permutation combination of the features are done in pandas dataframe and for each group the metric loss is measured(This is done as there are 13 features in the cleveland UCI dataset). The group of features bearing the least metric loss is then used as training features in the HRFLM model. 

Acoording to studies normal models bear a prediction accuracy of 66.7%, HRFLM alone gives 88.7%, and the method mentioned above in our idea gives approximately 98.6%, which can be the highest amount of accuracy received in the cardiovascular disease domain.

Note: HackInIndia folder consists of a dummy django web application. Normal models folder consists of the normal models(Random Forest, Decision Tree, KNN, Deep learning, and SVM's) codes and the proposed model contains the code for HRFLM algorithm. The dataset used for this project is also uploaded in this repo.

# Thank You...!! 
