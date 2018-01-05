# Food-Image-Classification
#### 1. The objective of this project is to train the Scikit-Learn classifiers with images of Entrée,<br/>
####    Salad and Dessert dishes and be able to predict if a given image is an Entrée, Salad or Dessert.
#### 2. The second part of the project is to take any arbitrary image with different food servings on a table<br/>
####    and then mark sections of theimage containing food. 

## Test Data
#### 1.We have collected 100 images each of Entrée, Dessert and Salad from various cuisines from publicly available images.
#### 2.We have used 100 random images of empty plates, and other images as negative images to train the Scikit-Learn classifier for negative cases.


## Classifying images of food using Scikit-Learn

####  1.Supervised Learning – SVM/SVC classifier was used as the supervised learner to train and predict randomized sample images of Entrée, Salad and Dessert.

##### 2.Unsupervised Learning – KMeans classifier was used as the unsupervised learner to train the same images samples without labels.
 
## Image PreProcessing

#### We have used various image processing techniques before training and testing the classifiers.

#### 1.Image Resizing – All training sample images were resized to 80x80 pixels.

#### 2.Binary Thresholding – All pixel values greater than a given threshold value were set to a fixed value. This was used to mask backgrounds in images that is not part of food.

#### 3.Canny - function used for edge detection

#### 4.Contour Detection – was used to separate out different dishes in a given dining table image with different food servings.

#### 5.HOG – Feature descriptor to convert image data into histogram data.
