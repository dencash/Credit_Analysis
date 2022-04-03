# Credit_Analysis

## OVERVIEW

The purpose of this project is to oversample and undersample data to compare new machine learning models that will predict credit risk. I used RandomOverSampler and SMOTE to oversample, and ClusterCentroids to undersample. The performance of the models will be analyzed and a recommendation for which, if any, should be used to predict credit risk


## RESULTS

# Naive Random Oversample Results:

![Random](https://user-images.githubusercontent.com/89025577/161407761-9474e299-5cda-432f-8e68-54f1a4d7c988.jpg)

# SMOTEEN Oversample Results:

![smote](https://user-images.githubusercontent.com/89025577/161407764-2ea698fe-9ac6-4e84-8b9c-ab2c9dca4432.jpg)

# CLusterCentroids Undersample Results:

![Cluster](https://user-images.githubusercontent.com/89025577/161407773-cfc0e183-da3d-4721-9e34-ee9341f4f89c.jpg)

# Over and Under Combination Results:

![combo](https://user-images.githubusercontent.com/89025577/161407784-d1111b33-3a15-490b-99e0-1ca2f1818e9b.jpg)


# Balanced RandomForestClassifier Results:

![Balanced_RFC](https://user-images.githubusercontent.com/89025577/161407869-6cb20647-9ead-4b05-aca4-2b6cc049682b.jpg)



# EnsembleAD Results:

![ensemble_adboost](https://user-images.githubusercontent.com/89025577/161407872-1fb511c1-593e-4c8e-8608-675e916846f0.jpg)


## SUMMARY

After Analyzing the data, naive random oversample appears to have the highest accuracy score of 65.3%, while SMOTEEN comes in close with a score of 65.1%. I would recommend the naive random oversample to use for credit risk. However, I would not protest if the company uses SMOTEEN, as it is very close in proximity regarding accuracy. 
