# Hybrid Approach for Predicting Heart Failure using Machine Learning

## 📌 Introduction :
The research aims on prediction of a heart failure using different machine learning algorithms and hybrid fusion techniques like majority voting of the best performing classifiers. This paper focuses on a majority based algorithm which uses the 3 best performing machine learning models out of the 10 selected machine learning models such as Logistic Regression, Decision Tree, Random Forest, Bagging Classifier, Gradient Boosting Classifier, Extreme Gradient Boosting Classifier, Extreme Gradient Boosting Random Forest, Extra Trees, Categorical Boosting Classifier and K-Nearest Neighbours. The top 3 classifiers are selected on the basis of their accuracy, f1-score and training time required. The minimum accuracy and F1-score score threshold is set to 90% so as to achieve better real world performance of the algorithm in terms of the ability to produce higher accuracy as well as the low time complexity. The proposed model combined the 3 best performing models using the voting method which yielded an Accuracy of 96.67%, a F1-Score of  95.24% and an AUC Score of  95% on the used data set.

## 🎯 Purpose of the Project:
Along with the large datasets, machine learning algorithms can be proved much more effective and accurate in determining various predictions regarding a specific medical record. This helps in providing more information to educate the patients regarding their diseases. Classification based models are of great use in these conditions wherein a disease has to be detected based on multiple medical parameters. This deals with the binary classification problem is to predict the likelihood of a patient dying due to heart failure by considering the various parameters as per the data set.

## ℹ About the Dataset
The data set has been taken from the UCI Machine Learning Repository: Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

## 👨‍💻 Technology Stack
- Flask
- HTML
- CSS
- Scikit-Learn
