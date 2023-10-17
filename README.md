# Breast-Cancer-Prediction-with-ML
Machine learning for medical diagnosis and its accuracy is a key advancement and a predicted trend in the future medical model. My goal is to use machine learning algorithms to diagnose breast cancer and perform performance analysis. Under the supervised machine learning approach, different classifiers are applied to the data sets to predict outcomes. We have used five such classifiers,
SVC()	0.903297
ExtraTreeClassifier()	0.905495
DecisionTreeClassifier()	0.923077
LogisticRegression()	0.938462
BaggingClassifier()	0.945055
GradientBoostingClassifier()	0.951648
RandomForestClassifier()	0.962637
AdaBoostClassifier()	0.964835
on the Breast Cancer WISCONSIN (Diagnostic) data set to observe how accurately they predict the cancerous instances. The classifiers are treated with cross-validation approaches to get exact accuracies. The same is done with different partitions of the data set, and performance analysis is made based on every observation.
It is observed that ADABoostClassifier outperformed all other classifiers and achieved the highest accuracy (96.5%).
All the work is done in the Jupyter Notebook based on python programming language and Scikit-learn library.
