# plagiarism_detector

## Overview

Plagiarism Detector project for the Udacity Nanodegree.

A PyTorch NN binary classifier was trained on data (answers in text form that were labelled
"plagiarised" or "not plagiarised". 

The trained model was fit using a SageMaker estimator object, and deployed to an endpoint for prediction.

The resulting model was tested using a test dataset and the accuracy was measured.

## Note

This project was implemented in a SageMaker notebook instance, with data uploaded to an S3 bucket.
