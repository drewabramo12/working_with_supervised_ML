# working_with_supervised_ML

## Overview

The purpose of this project is to show the difference in ways to fit models for machine learning and to determine which is the best option for determining an algorithm for credit risk.

## Results

- Balanced Random Forest

![Balanced Random Forest](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/BalancedRandomForest.PNG)

- AdaBoost

![AdaBoost](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/EasyEnsembleAdaBoost.PNG)

- Naive Random Oversampling

![Naive Random Oversampling](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/NaiveRandomOversampling.PNG)

- SMOTE

![SMOTE](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/SMOTE.PNG)

- SMOTEENN

![SMOTEENN](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/SMOTEENN.PNG)

- Undersampling

![Undersampling](https://github.com/drewabramo12/working_with_supervised_ML/blob/main/Images/Undersampling.PNG)

## Summary

Based on the different models that were run and the significant imbalance in the difference between high risk and low risk samples, it is tough to recommend any machine learning models. All are highly capable of recoginizing low risk but are particularly bad at recognizing high risk loans. There appears to be a very low level of precision for all high risk algorithms. Looking at the recall it can however be seen that Adaptable boosting has the highest percentage. This implies that it does for the most part find the majority of the high risk loans but then also confuses low risk loans as being in this said group as well.

I would recommend using the adaptable boosting machine learning model as an algorithm that combs for potential high risk loans and then is passed to a human interface for double checking. I would also be interested in seeing how a secondary machine learning model would fair with the potential high risk loans that were determined by the first machine learning model.