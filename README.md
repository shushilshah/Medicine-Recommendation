Project Name: Medicine Recommendation System

######################################

Project Description:
This project is about the health recommendation system based on the user or patient's symptons. The user provides occuring or facing symptoms to the system as an input. Then the system analyze that symptoms and checks that the provided
symptons exit within the datasets or not. If yes, then the system provide necessary description about the disease like disease name, disease description, precaution of disease, medication and workout for that disease and also what diet should to follow.

#######################################

Project Workflow:

1. Data Collection
2. Data Analysis
3. Data Preprocessing
4. Models fitting
5. Model selection
6. Deployment

#################### Workflow Description ###########################

1. Data Collection:
   The data is collected from kaggle site for the learning purposes. The dataset consists of 8 csv files each with their seperate working purpose.

2. Data Analysis:
   The data is then analyzes to move further ahead by choosing what columns will be needed. But, in this case all the columns are necessary for the modelling purposes.

3. Data Preprocessing:
   The data is preprocessed by applying several techniques like data shape, presence of null values, data describe, data info and other.

4. Models fitting:
   The preprocessed data is then fitted with several models like random forest classifier, SVC, gradient boosting classifier,
   K-neighbors and Multinomial models.

5. Model selection:
   Among the several fitted models, multinomial model is selected for the evaluation prupose as it provides the best accuracy among other.

6. Deployment:
   The fitted model and after the right evaluation of samples of disease with model then the model is integrated with front-end using Flask framework.
