## Ensemble Machine Learning Models



[Ensemble models](https://blog.statsbot.co/ensemble-learning-d1dcd548e936) in machine learning operate on a similar idea. They combine the decisions from multiple models to improve the overall performance. 


Ensemble learning helps improve machine learning results by combining several models. This approach allows the production of better predictive performance compared to a single model. That is why ensemble methods placed first in many prestigious machine learning competitions, such as the Netflix Competition, KDD 2009, and Kaggle.



**Ensemble methods are meta-algorithms that combine several machine learning techniques into one predictive model in order to decrease variance (bagging), bias (boosting), or improve predictions (stacking).**


#### **Ensemble methods can be divided into two groups:** 

 - **sequential** ensemble methods where the base learners are generated sequentially (e.g. AdaBoost).
The basic motivation of sequential methods is to exploit the dependence between the base learners. The overall performance can be boosted by weighing previously mislabeled examples with higher weight.

 - **parallel** ensemble methods where the base learners are generated in parallel (e.g. Random Forest).
The basic motivation of parallel methods is to exploit independence between the base learners since the error can be reduced dramatically by averaging.
