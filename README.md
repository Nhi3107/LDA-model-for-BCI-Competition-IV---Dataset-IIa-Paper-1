## Building a LDA classification model for BCI Competition IV-Dataset IIa using the proposed feature selections.
### Main_Analyses.m
- BCI Competition IV—Dataset IIa was put into Matlab and proceeded to be input to the model.
- Performed preprocessing steps by filtering out high-frequency, low-frequency noise and powerline interference.
- The feature used in the model is filter banks.
- To run the model, we used 10-fold cross validation with one-vs-one and one-vs-all methods. Two steps (feature selection and classification) were combined in the classification functions.

Note: 
  
  Dataset IIa: https://bnci-horizon-2020.eu/database/data-sets

This code is only part of the paper: "Evaluation of motor image classification performance of two-class feature selection on two datasets of different sizes" (doi.org/10.3390/app112110388)
