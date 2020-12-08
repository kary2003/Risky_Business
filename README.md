# 11_Risky_Business

![image](http://blogs.edf.org/energyexchange/files/2017/06/risk_management.jpg)

# Background
In order to assisst online lending companies to mittigate risk:

* Using free data from LendingClub I'll Analyse different machine learning models to predict and individuals credit risk: 
    * Resampling
    
        * Oversampling
        
            * Naive Random Oversampling algorithm
            * SMOTE Oversampling algorithm
            
        * Undersampling
        
            * Cluster Centroids algorithm 
            
        * Combination (Over and Under) Sampling
        
            * SMOTEENN algorithm
            
    * Ensemble Learning
    
    
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
  
## Conclussions




## Files

[Risk-Ensemble Notebook](https://github.com/kary2003/11_Risky_Business/blob/main/credit_risk_ensemble.ipynb)

[Risk-Resampling Notebook](https://github.com/kary2003/11_Risky_Business/blob/main/credit_risk_resampling.ipynb)

[Resources](https://github.com/kary2003/11_Risky_Business/tree/main/Resources)



