# handmade-machine-learning

Personal challenge : fully re-code some machine learning algos : Random forests (including xgboost), svm, etc..

## The code is inspired by the logic of sklearn, but is much simpler:
  - common terminology and workflow (model instanciation, model.add_layer, model.fit, model.predict etc..) but simplified
  - less features implemented
  - less checks, exceptions, tricky cases allowed, etc.
  - probably much less computionaly efficient
  
## Implemented so far:
  nothing !

## In the first phase we will focus on SVM:
  - hard margin algorythm without kernel (i.e. classify only lineary separable data)
  - soft margin (with simple hinge function)
  - kernel trick with simple kernels : prolynomials
  - classifiers only
 
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
