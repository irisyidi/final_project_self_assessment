# final_project_self_assessment
## Self Assessment 

In the group, I conducted the data exploration analysis, built database, established 3 different machine learning model and created the presentation dashboard. The greatest challenge in the group project is cleaning and transforming the datasets we used because I needed to consider the size of the samples and the effectiveness of the datasets. I overcame the problem by referring the related ETL works and keep improving and upgrading the datasets. 

As for the role I did not play, I mainly reviewed the description in the presentation dashboard and discussed with teammates to make sure that we were in the same direction. 

## Project and Team Summary

We mainly used the slack to communicate and posted the problems we met in the coding process and the timely updates of the process so that everyone of us would be informed. 

The strength of the team is that we were good at communicating our thoughts and thought perspectives from differenct sides. We contributed great time and efforts to the whole group project. 

The topic we selected is the credit score predictions. We want to predict the credit score by the credit history and the loans customers applied for. 

We tried the supervised machine learning model and the deep machine learning model. As the output of the model should be the name or group of class, it is proper for us to use the classification algorithm. In the supervised machine learning model, we use oversampling RandomOverSampler, SMOTE algorithms and the undersampling ClusterCentroids algorithm. we also use the ensemble classifier to predict the risk(BalancedRandomForestClassifier and EasyEnsembleClassifie algorithm). 

After analyzing these three models and based on the results we gathered, we decided that the best machine learning model to use with our dataset is the Ensembled Learning model. This model was the only one whose balanced accuracy score using the balanced random forest classifier surpassed the accuracy score. 
The model's accuracy is 75.6%. the precision scores for Good, Poor and Standard are 0.52%, 0.67% and 0.88, respectively. 
