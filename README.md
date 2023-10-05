# Adult_Income_Preds
## This repository has been created to demonstrate the various correlations and trends present in the Adult Income data set found here, https://www.kaggle.com/datasets/wenruliu/adult-income-dataset.

This data set contains information on thousands of respondants ranging from age to education levels to country of origin and many more. I will use this data to predict and show trends in relation to the target, 'income', represented in the dataset as <=50k and >50k.

<img width="283" alt="image" src="https://github.com/ben-fajack/Adult_Income_Preds/assets/134533964/74e7f6ac-a255-4824-9ad4-7dd0bcf19c27">

## **Here we see clearly that the intuitive assumption that increased education tends to increase earnings potential.**

<img width="298" alt="image" src="https://github.com/ben-fajack/Adult_Income_Preds/assets/134533964/41a037be-efb3-4bea-b7b5-18867613f240">

## **Here we see that one of our other intuitive assumptions is also correct for this dataset: income tends to increase as one gets older.**

<img width="421" alt="image" src="https://github.com/ben-fajack/Adult_Income_Preds/assets/134533964/e76fb38b-167b-4346-a988-6e0393a595e3">


## I tested three models on this dataset in an attempt to predict income outcomes based on 14 original features. The three models performed suprisingly simlarly. There was variation in the amount of false positives and false negatives but since the only goal was the overall success rate of placing respondants in the correct binary income bracket, success rate in that regard was the only factor considered in determining the best predictive model.

## The KNN model used here came out on top by outperforming the other two models by a very slim margin. The F-1 score takes into account both false positives and false negatives, giving the user a good idea of overall predictive ability. With an F-1 score of .79, the KNN model was accurately predicting the income set of the respondants just under 80% of the time. This is a solid model that could continue to improve with more good data. 
