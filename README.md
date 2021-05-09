# foodpanda_test

1. Here I used Matthews correlation coefficient (MCC) for performance evaluation. MCC is a measure of the quality of binary classifications, introduced by biochemist Brian W. Matthews in 1975. MCC is useful when the two classes are of very different sizes, and that’s why I choose it. Then I use 5-fold cross validation and mean MCC of 5 experiments to evaluate model performance. Resampling methods are performed on the training set after splitting the 5-fold datasets.

2. AUC-ROC curve is a performance measurement for the classification problems at various threshold settings. ROC is a probability curve and AUC represents the degree or measure of separability. It tells how much the model is capable of distinguishing between classes. Higher the AUC, the better the model.
AUC is a good metric, espacially in ranking senario.
In addition, MCC is also a good evaluation metric here coz it performs well at imbalanced datasets.

3. Unfortunately, I can not get into the top 100 of the private leaderboard. My best private score is 0.86447, which ranked 317.
