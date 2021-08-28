# Handwritten_digit_classifcation
# Introdcution
MNIST (Modified Institute of Standards and Technology, which 
is a handwritten digit classification .The training dataset consists of 6000 samples images, with 
a size of 784 pixels and the testing dataset consist of 10000 samples images with the size of 
784 pixels.It is multi-class classification where the number of classes in the dataset is 10 (0-9).
Keras library is an open-source library written in python to create and trained neural network that runs on the top of the Tensorflow, 
Theano or CNTK

Convolutionl Neural Network(CNN)
CNN (Convolution Neural Network) is a deep learning algorithm that is mostly used for image 
processing, such as image classification, object detection, etc. In CNN Filters are applied to each 
training image at different resolutions and the output of each convolved image is used as the input to 
the next layer. CNN has different layers, such as the Convolution Layer, Pooling Layer, and Fully 
Connected Layer

# Confusion Matrix
It is an M*M matrix which is an evaluation matrix used for classification problems only, where 
M represents the number of classes.
## Terms used in Confusion matrix:-
* True Positive (TP): When the model predicted positive and in actual it is positive.
* False Positive (FP): When the model predicted positive, but in actual it was negative. It is also 
known as type 1 error.
* True Negative (TN): When the model predicted negative and in actual it was negative.
* False Negative (FN): When the model predicted negative, but in actual it was positive. It is 
known as a type 2 error.
* Precision: Out of the predicted positive class how many you got right.
                     Precision =TP/TP+FP
 * Recall: Out of the positive class, in the dataset, how many you predicted positive class.
                      Recall =TP/TP+TN
 * F1-score: Average weighted of the recall and precision.
       F1=2  * Precision*Recall/Precision + Recall
 
 
# Output
Three layer  is used to trained the model ,with 64 filters, size of the  filters are 3*3 respectively to each layer. The size of the 
max- pooling in each layer is of 2 * 2 matrix with Relu activation function in each layer.

# Accuracy.
CNN model give an accuracy of 99 percent on test data










