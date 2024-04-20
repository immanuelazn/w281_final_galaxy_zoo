# w281_final_galaxy_zoo
- data_split:
    Split the data into training, validation and testing
- image_preprocessing: 
    Explore various types of filtering, try out the parameters and establish the pipelines
- pipeline1_SIFT_LR_SVM: 
    Use the product of pipeline 1 and extract feature from it using SIFT, Kmean and BoVW
- pipeline2_HOG_LR_SVM: 
    Use the product of pipeline 2 and extract feature from it using HOG feature
- pipeline3_ResNet_LR_SVN: 
    Use the product of pipeline 3 and extract feature from it using the body of ResNet-50
- pipeline_123_classifiers_LR_SVM: 
    Integrite pipeline 1,2,3 and test it out with LDA + LR and non-linear SVM 
- pipeline_123_classifiers_LR_SVM_databalacnce_dataset2: 
    Data balancing with dataset 2 and test it out with LDA + LR and non-linear SVM 
- pipeline_123_classifiers_LR_SVM_databalacnce_dataset3: 
    Data balancing with dataset 3 and test it out with LDA + LR and non-linear SVM 
- pipeline_123_classifiers_LR_SVM_entiredataset: 
    Run the entire dataset and do the grid search
