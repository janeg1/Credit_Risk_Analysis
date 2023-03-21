# Credit Risk Analysis Overview

As for this challange we need to help a client to evaluete credit card risk. Today "good" loans outnumber "risky" loans which creates unbalanced classes. We need to train and evaluate this classes. We will be using real life data from Lending Club, which is a lending money company. For this task we will use different libraries and techniques and decide which is more effective based on comparing balanced accuracy score, precision score and recall score.

### Libraries

*imbalanced-learn

*scikit-learn

### Techniques 

*Naive Random Oversampling

*SMOTE Oversampling

*Undersampling

*Combination (Over and Under) Sampling

*Ensemble Learners

*Balanced Random Forest Classifier

# Results

1. Naive Random Oversampling ( balanced accuracy score = 0.65, 
                               precision score = 0.99,
                               recall score = 0.62 )

2. SMOTE Oversampling ( balanced accuracy score = 0.66, 
                               precision score = 0.99,
                               recall score = 0.68 )

3. Undersampling ( balanced accuracy score = 0.66, 
                               precision score = 0.99,
                               recall score = 0.40)
                               
4. Combination (Over and Under) Sampling ( balanced accuracy score = 0.54, 
                               precision score = 0.99,
                               recall score = 0.57 )                               
                               
5. Ensemble Learners ( balanced accuracy score = 0.79, 
                               precision score = 0.99, 
                               recall score = 0.87 )
                               
6. Balanced Random Forest Classifier ( balanced accuracy score = 0.93, 
                               precision score = 0.99, 
                               recall score = 0.94 )     
                               
 # Summary
 
Based on numbers provided we can conclude that last ( Balanced Random Forest Classifier) will be the best model to use, as we strive for number close to 1, to show best results. between all 3 scores this model shows the best results.
