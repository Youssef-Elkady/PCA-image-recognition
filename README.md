
# Description: Using Logistic Regression and KNN wo classify particles as noise or signals based on a few attributes.  

## Approach:  

   Preprocessing: the dataset is not balanced due to technical reasons, so we need to balance it before training the models to avoid biases. So undersampling was used to resample the more dominant class. Also, the features had wildly different ranges to all features were normalized to assure they all converge easily.  
   Training: Logistic Regression and KNN (with diffrent K values) were used to solve this problem and their performances where compared. The models were trained using 10-fold cross validation and the best model was selected based on the average accuracy of the folds.
