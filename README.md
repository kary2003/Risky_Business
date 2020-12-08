# 11_Risky_Business

![image](http://blogs.edf.org/energyexchange/files/2017/06/risk_management.jpg)

# Background
In order to assisst online lending companies to mittigate risk:

Using free data from LendingClub I'll Analyse different machine learning models to predict and individuals credit risk: 
   ### * Resampling
  * Oversampling
     * Naive Random Oversampling algorith
     * SMOTE Oversampling algorithm 
  * Undersampling
       * Cluster Centroids algorithm 
  * Combination (Over and Under) Sampling
       * SMOTEENN algorithm
            
  ### * Ensemble Learning
   * Balanced Random Forest Classifier 
   * Easy Ensemble classifier
    
## Ensemble Learning Imports

* import numpy as np
* import pandas as pd
* from pathlib import Path
* from collections import Counter
* from sklearn.metrics import balanced_accuracy_score
* from sklearn.metrics import confusion_matrix
* from imblearn.metrics import classification_report_imbalanced

## Resampling Imports

* import numpy as np
* import pandas as pd
* from pathlib import Path
* from collections import Counter
* from sklearn.linear_model import LogisticRegression
* from sklearn.preprocessing import StandardScaler
* from imblearn.over_sampling import RandomOverSampler
* from imblearn.over_sampling import SMOTE
* from sklearn.metrics import balanced_accuracy_score
  
# Conclussions

## Resampling

Which model had the best balanced accuracy score? 
   * The Smote Oversampling model
   
Which model had the best recall score? 
   * Naive Random Oversampling model
   
Which model had the best geometric mean score? 
   * The Smote Oversampling model

## Ensemble 

Which model had the best balanced accuracy score? 
  * Easy Ensemble Classifier(eec_acc_score = 0.92)
  
Which model had the best recall score? 
  * Easy Ensemble Classifier
  
Which model had the best geometric mean score? 
   * Easy  Ensemble Classifier

What are the top three features?
* Top 3 Features
    * (0.079, 'total_rec_prncp'),
    * (0.059, 'total_pymnt'),
    * (0.056, 'total_pymnt_inv'),



## Files

[Risk-Ensemble Notebook](https://github.com/kary2003/11_Risky_Business/blob/main/credit_risk_ensemble.ipynb)

[Risk-Resampling Notebook](https://github.com/kary2003/11_Risky_Business/blob/main/credit_risk_resampling.ipynb)

[LoanStats](https://github.com/kary2003/11_Risky_Business/tree/main/Resources)



