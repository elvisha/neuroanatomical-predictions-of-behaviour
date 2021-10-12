# Neuroanatomical Predictions of Behaviour


This repository contains all of the MATLAB and Jupyter Notebook based implementation of the work described in: Dhamala E., Ooi L.Q.R., Chen J., Kong R., Anderson K.M., Yeo B.T.T., Holmes A.J. (In preparation). Intracranial volume correction differentially biases behavioral predictions across neuroanatomical features and populations. 


Keywords: neuroimaging, intracranial volume, sex, age, predictive modelling, behaviour, cognition, neuroanatomical properties, surface area, gray matter volume, cortical thickness
 
This implementation was used to evaluate the effect of ICV correction on sex-independent and sex-specific predictive models of individual cognitive abilities across multiple anatomical properties (surface area, gray matter volume, cortical thickness) in healthy young adults (Human Connectome Project) and typically developing children (Adolescent Brain Cognitive Development). 

Below are descriptions of each Jupyter Notebook: 
01_predictions_sexindependent : optimises, trains, and evaluates sex-independent models to predict individual cognitive abilities based on neuroanatomical properties in children and adults
02_predictions_sexspecific : optimises, trains, and evaluates sex-specific models to predict individual cognitive abilities based on neuroanatomical properties in children and adults
03_nullpredictions_sexindependent : generates null models corresponding to true sex-independent models
04_nullpredictions_sexspecific : generates null models corresponding to true sex-specific models
05_prediction_figs : generates figures visualising prediction accuracies 
06_evaluate_model_significance : evaluates model significance using prediction accuracies from (sex-independent and sex-specific) null and true models
07_featimp_evaluations : evaluates network-level and regional-level feature weights across all (sex-independent and sex-specific) models
