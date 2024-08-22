## Overview of the analysis

The purpose of this particular jupyter notebook analysis is to evaluate and determine if someone is a credit risk. Taking into account their income, loan size, if they have defaulted on loans
previously, will all factor into this analysis and model's predictions. The prediction this model is trying to make is whether or not the loan about to be given out is healthy or high risk. 
Isolating "loan status" as the X variable allowed me to use the logistic regression model to make those predictions. 

## Results

Using the logistic regression "model, fit, predict" method, as expected, I was able to determine that this model is exellent at predicting if a healthy loan is about to be given out.
The precision score for "healthy loans was 100%. HOwever, the high risk predictions seemed to be a bit overly cautious when predicting high risk loans. Meaning, that there are some 
borrowers out there that with an adjusted model would be considered "healthy", instead this model is defining them as "high risk". But overall, 87% precision is not faulty by any 
stretch of the imagination.

## Summary

In summary, this model was very effective. When it comes to assessing credit risks, it can be best to err on the side of caution. If there were an argument to be made as to what
prediction is more important to have the highest precision possible, it would be the "healthy" loans. In the eyes of a creditor, its better to flag non-credit risks as credit risks, 
than to issue "healthy" loans to high credit risks. This is the way to better ensure loans get paid. 
