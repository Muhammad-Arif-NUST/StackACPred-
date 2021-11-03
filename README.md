##StackACPred: prediction of anticancer peptides by integrating optimized multiple feature descriptors with stacked ensemble approach

##StackACPred uses the following dependencies:
 * Python 3.6
 * numpy
 * scipy
 * scikit-learn
 * pandas
 * matplotlib
 * MATLAB (R2018a)
 
 

##Guiding principles: **The dataset folder contain both ACP740 and ACP240 dataset.

**feature extraction:
  *  PAAC.m directory contains PseAAC.m.
  * PsePSSM.m contains PsePSSM.m.
  * Seg-PSSM contain Seg-PSSM.m.
   
** feature selection:
  * SVM-RFE+CBR.
  

** Classifier:
  * stacking.py implements stacked ensemble classifier.

  
** Dataset:
  * ACP740_dataset_.txt contains the data of the ACP and non-ACP dataset.  
  * ACP240_dataset_.txt contains the data of the ACP and non-ACP dataset.  
