# Human-Activity-Recognition-using-Machine-Learning
This project is a case study for Human Activity Recognition using data collected by smart devices (smartphones and smart watches). Experiments were done on volunteers within an age bracket of 19-48 years. Each person performed six different activities (Walking, Walking upstairs, Walking downstairs, Sitting, Standing, and Laying) while wearing a smartphone on the waist. The smartphones contained Accelerometer and Gyroscope sensors that were measuring the body orientation and motion in reference to the ground. The data was collected by these smart devices and sent to a remote cloud server. The downloaded data was provided by New England College (USA) in their Machine Learning Course.

The aim is to reduce the dimensionality of the data, and train a classification model that can accurately identify the activity being performed.

## Models used
* Quadratic Discriminant Analysis (QDA)
* K-Nearest Neighbors (KNN)
* Random Forest (RF)
* Support Vector Machines (SVM)
* Artificial Neural Network (ANN)
* Extreme Gradient Boosting (XGBoost)

## Key Processes
* Data Preprocessing: This processes involved cleaning and scaling the data for PCA, and reducing the data dimensionality using PCA.
* Model Training: This phase involved training and tuning the various Classification models mentioned, with cross-validation to control overfitting, and evaluating the performance of the models trained across the cross-validation folds.
* Model Evaluation and Validation: The best performing model (SVM) was used to make predictions on test data, and a confusion matrix was used to calculate various evaluation metrics like Accuracy, Sensitivity and Precision.

## Results
The best model (SVM) had a validation accuracy of 81.79%. The model also had good Precision for five of the classes i.e. LAYING (0.82), SITTING (0.82), STANDING (0.83), WALKING (0.81), and WALKING UPSTAIRS (0.84), which was impressive.

## Tools and Libraries
RStudio (tidyverse, caret, parallel, parallelMap). Please install the specified packages prior to running the R markdown. Note that running the markdown will take a few hours. I've uploaded the knitted pdf version of the markdown file.
