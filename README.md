# handmade-machine-learning

Personal challenge : fully re-code some machine learning algos : Random forests (including xgboost), svm, etc..

## The code is inspired by the logic of sklearn, but is much simpler:
  - common terminology and workflow (model instanciation, model.add_layer, model.fit, model.predict etc..) but simplified
  - less features implemented
  - less checks, exceptions, tricky cases allowed, etc.
  - probably much less computionaly efficient
  
## Implemented so far:
  - linear SVC :
    - loss options : hinge, suared_hinge
    - penalty options : l1,l2
    - kernel : only linear

## Next steps:
  - kernel trick with simple kernels : prolynomials
  - create a pedagogical tutorial notebook about linear SVC
 
## To be coded later :
  - more for svm :
    - SV regressors
    - more hinge options
    - more kernels : rbf
    
  - regressors/classifiers with ridge/lasso/elasticnet

  - decision trees
    - simple decision trees
    - adaboost/xgboost
   
  - unsupervized:
    - k-mean
    - pca
