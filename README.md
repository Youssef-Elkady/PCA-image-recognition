
# Description:  
Using PCA to reduce the dimensionality of the dataset and then using KNN to classify the images. The dataset used was AT&T Faces dataset. the problem we are solving is face recognition and detection  


## Approach:

PCA algorithm was coded manually from scratch and applied on the Dataset with a different alphas. Then KNN was used to classify the images.   
The models were trained using 10-fold cross validation and the best model was selected based on the average accuracy of the folds.   
the performance was compared between different alphas and different K values. then the models were compared to the built in PCA functions in sklearn to assure the correctness of the implementation.  
Then images from the CIFAR-10 dataset were added ad the non-face images and KNN was used again this time to detect weather there was a face or not in the image.
