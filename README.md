# Case-Study-ANN-vs-ML-Classification-Problem
A comparative study on the results of an Artificial Neural Network(ANN) with that of an ML classification problem.

##Problem Statement:
This dataset has the features regarding the potability of the water whether it is safe to consume or not.

![image](https://user-images.githubusercontent.com/70081663/120935489-b127f980-c720-11eb-979b-e0b444c11ddd.png)

Dataset link: https://www.kaggle.com/adityakadiwal/water-potability

##Tasks Completed:

1. Explanatory Data Analysis
2. Developing an ANN Model
3. Developing an ML Random Forest Classifier Model.
4. Tuning the Random Forest Classifier Model using RandomizedSearchCV
5. Comparing the results

## Accuracy Results:

1. ANN with outliers - 61%
2. ML before tuning- 64%
3. ML after tuning- 65%
4. ANN without outliers- 64%

## Conclusion:

1. The reason for low accuracy of ANN model can be because of the outlier that are present in the data.
2. We see that even for an Ml algorithm we are getting some where around 65% accuracy.
3. This shows that the ANN which is producing 60% accuracy is 5% behind the ML model.
4. With the removal of the outliers the accuracy of the ANN model increased to 64%.(not recommended)
5. Hence, from this case study we can say that for an structured tabular data ML algorithms perform bettern that ANN model.
