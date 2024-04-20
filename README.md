# w281_final_galaxy_zoo
notebook data_split                                             -> splitting data into training, validation and testing
notebook image_preprocessing                                    -> explore various types of filtering, try out the parameters and establish the pipelines
notebook pipeline1_SIFT_LR_SVM                                  -> Use the product of pipeline 1 and extract feature from it using SIFT, Kmean and BoVW
notebook pipeline2_HOG_LR_SVM                                   -> Use the product of pipeline 2 and extract feature from it using HOG feature
notebook pipeline3_ResNet_LR_SVN                                -> Use the product of pipeline 3 and extract feature from it using the body of ResNet-50
notebook pipeline_123_classifiers_LR_SVM                        -> Integrite pipeline 1,2,3 and test it out with LDA + LR and non-linear SVM 
notebook pipeline_123_classifiers_LR_SVM_databalacnce_dataset2  -> Data balancing with dataset 2 and test it out with LDA + LR and non-linear SVM 
notebook pipeline_123_classifiers_LR_SVM_databalacnce_dataset3  -> Data balancing with dataset 3 and test it out with LDA + LR and non-linear SVM 
notebook pipeline_123_classifiers_LR_SVM_entiredataset          -> Run the entire dataset and do the grid search
