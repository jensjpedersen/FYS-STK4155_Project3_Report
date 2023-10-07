
# Content  
* ![Random Forest Classifier written in Python](https://github.com/jensjpedersen/FYS-STK4155-Applied_Data_Analysis_and_Machine_Learning/tree/main/Project3)
* ![Project report](./project3.pdf)

# Abstract
The goal in the field of radiomics is to establish links between diagnosis, prognosis and
treatment response, from correlations in quantitative medical image features. Image modal-
ities such as Positron Emission Tomography (PET) suffers from high feature variability
inter scanners and due to different image reconstruction parameters. Knowledge about how
different parameters affects quantitative feature values is needed.
We will try to identify the features that are best able the separate different PET recon-
struction method in a systematic way with the use of Support Vector Machine (SVM).
Feature selection is an important step in the machine learning process because it helps to
reduce the complexity of the model, improve the accuracy of the model, reduce overfitting,
reduce the training time of the model, increase explain ability of the model. Feature selection
helps to identify the most important features that contribute to the prediction and discard
the irrelevant or redundant features.
In the first part we will use random forest and correlation for feature selection to identify
the features with best class separability between reconstruction.
Then we will apply feed forward selection with Suport Vector Machine (SVM) to see
if we are able to correctly predict the class targets. And also validate if or prior features
selection agrees with the results obtained with SVM.
The features performing best in SVM agreed well with the features showing best sperabil-
ity in the random forest and correlation analysis for two of the classification combinations.
The feature combination of histogram min and glcm homogenity produced the best class
separation between reconstruction methods. With the best overall accuracy of 0.817 for
classification of the PT_PET_EARLAC versus PT_PET_WB_Q_CLEAR reconstruction method, indi-
cating most dissimilarity. In a raiomics setting it’s important to be aware that there will be
significant variation in those feature values with respect to different reconstruction methods.
Our methodical approach for quantifying dissimilarity between reconstruction methods was
not suited for the problem, and should not be investigated any further.

