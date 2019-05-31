## Machine Learning Project ##
This is a project in a machine learning course on using SVM, MLP and logistic regression on land cover and land use data.                   
The notebooks in this repository was done as part of a project related to an introductory machine learning course on Aarhus University.                                                                                                                      
The project used the following notebook as a guideline/tutorial:

https://github.com/sentinel-hub/eo-learn/blob/master/examples/land-cover-map/SI_LULC_pipeline.ipynb

That notebook uses a model called LightGBM to classify land-use and land-cover in Slovenia.

This project implemented selected scikit-learn models on the same data to see how those models perform compared to each other and to the LightGBM model. Therefore, the first part of the notebooks in this repository is an exact replica of the original notebook where the LightGBM model was used.   

The following scikit-learn models were used:

-Support Vector Machine (SVM)

-Multi-layer Perceptron (MLP)

-Logistic Regression (LogRes)

The final results are summed up in the following:
 
<b>Overall accuracy , F1 score</b>

SVM:         90,3%     ,   89,0%

MLP:         90,9%     ,   90,0%

LogRes:      90,4%     ,   89,2%

LightGBM:    92,4%     ,   91,9%

The results show that the scikit-learn models predict quite similarly, while the LightGBM model have a slightly better accuracy and f1 score. 
Another note to make is that the SVM model took several hours to run, whereas MLP, LogRes and LightGBM ran smoothly and took only a few minutes to process. 
