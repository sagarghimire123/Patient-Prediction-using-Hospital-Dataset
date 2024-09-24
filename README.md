# Patient-Prediction-using-Hospital-Dataset
This assignment focuses on practical machine learning and multi-modal modeling
(using text, categorical, and numeric data and handling missing data - note “multi-modal” usually
refers to images, text, and audio, but I prefer to extend use here). Please find
“8k_diabetes_v2.csv” on Blackboard and you will be using the features in this data (all but
“readmitted”) to predict the target (“readmitted”). The grading for this assignment is outlined
below.
# Part A: Model Code and Exploration 

                          1. Perform Exploratory Data Analysis (EDA) and discuss the data and what you observe
                          prior to beginning modeling and how impact how to proceed 
                          
                          2. Pre-processed categorical data for use in the model and justified pre-processing
                          method. Note this may be different for each algorithm you try. 
                          
                          3. Pre-processed numerical data appropriately including handling missing data and
                          justified methods used. Note this may be different for each algorithm you try. 
                          
                          4. Implement a model to make predictions using text data using tf-idf 
                          
                          5. Use model stacking to incorporate tf-idf predictions for the text field
                          (diag_desc_combined) in the downstream algorithm 
                          
                          6. Perform experimentation for multiple modeling algorithms and justify why you
                          selected the experiments you chose 
                          
                          7. Final model selection and discussion of your model choice and the model weaknesses
                          (generally, where model doesn’t perform well, etc.)

# Part B: Model Performance 

This section your grade will be entirely based on the performance of your model. Please submit a
“<lastname>_<firstname>_pred2.csv” with the predictions of readmission for the sample I
share 5 days before the submission deadline. We will use AUC as our performance metric.
# Please see the grading table below:
                      AUC Points
                      >=.6 25
                      >=.62 50
                      >=.63 60
                      >=.64 70
                      >=.65 80
                      >=.66 90
                      >=.67 100
