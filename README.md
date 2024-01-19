# Predict medical condition based on health characteristics

## INSPIRATION:
   In every family we see, about our  family members who have grown old and even ourselves we want to know their medical condition so that in right time we can take right action otherwise some time it can be late . For majority of persons it is not easy that they can checkup everyday their medical condition but what happen if they can know their medical condition from their health characteristics. And in foreign country there are more digital wrist worn gadget which can tell about medical condition of any user .

## Introduction:
   This project involves the development of a model which is trained by  health characteristics data collected from wrist-worn watch or any other gadget or gathered from any patients and then it can  gives the output that a person has any medical issues for the given  health characteristic of that person.
 This is based on ML algorithms and some model like random forest or XGboost and others.
## Methodology:
 This holds several steps:
(a)It can be considered as binary class classification problem based on health  characteristics values . Model predict the probability of medical condition P(h) that person has any medical issues or not .And then it compares against a threshold q.
If P(h) >= q then person has otherwise not. 
(b)First we will visit all health characteristic variables and if any variable has categorical value then we will convert it in numeric form .
(c)We will check outliers.
(d)We will select a model. There are several model like
- Random Forest Model
- Gradient Boosted Trees  Model
- Cart Model
- Distributed Gradient Boosted Trees Model
(e)Then we will do hyperparameter tuning.
(f)Train our model and apply roc and auroc and the use this model for test data.

## Goals:
  Mid Evaluation:
- To acquire the required skillset to build model .
- Gain greater experience of using ML algorithms on practical datasets(from Kaggle)
- Performing necessary data collection and data cleaning.
  
ULTIMATE GOAL:
- To increase the accuracy of the prediction of the model.
- And make the model better so that its performance could become good .

## Reference:
(1)https://www.researchgate.net/publication/321734295_Age-Related_Diseases_and_Clinical_and_Public_Health_Implications_for_the_85_Years_Old_and_Over_Population
(2)https://www.kaggle.com/competitions/icr-identify-age-related-conditions/overview
      


