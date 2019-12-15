# Organic-Chemical-Compounds-Classification    
**EDA and MLP model for Organic Chemical Compounds Classification which was a task given by Credicxo**

## Problem Statement  
The given dataset contains details about organic chemical compounds including their chemical features, isomeric conformation, names and the classes in which they are classified. The compounds are classified as either ‘Musk’ or ‘Non-Musk’ compounds.  
Our task is to build a classification model on the given data using any Deep Learning approach that you deem appropriate viz. Multi-Layer Perceptron, CNN, RNN, etc. or we could also use transfer learning approaches through selection of appropriate pre-trained model. The data has to be split in a 80:20 ratio for training and validation datasets. We can perform whatever preprocessing and post-processing operations on the data that may help us improve the performance of your model. We are required to report the performance measures of the model Accuracy( Training and Validation) and Loss(Training and Validation) graphs, F1 score, precision, recall, etc. along with a well detailed report of what models, pre-processing, post-processing approaches we have used and why we chose to use these approaches.  

## Our Solution  
We are able to reach 100% accuracy using little feature engineering like label encoding and applying standard scaler and using only 2 hidden layers and 50 epochs in the ANN.  
Follwing is our Neural Network architechure:  
![model_plot](https://user-images.githubusercontent.com/40590709/70861680-af301080-1f57-11ea-99bd-96ece65e640a.png)



