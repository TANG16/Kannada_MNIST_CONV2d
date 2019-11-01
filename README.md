# Kannada_MNIST_CONV2d

Classifying handwritten digits using a Convolutional  Neural Network and Data Augmentation:

This notebook is my second iteration of the Kannada MNIST dataset I found on Kaggle. I decided to start from scratch because I wanted to try using a CNN and implementing data augmentation.

My previous attempt resulted in accuracy scores in the 90%s on the validation set; however, I received accuracy scores in the 60%s on the holdout set. This made me think that I either didn't have enough data to train on, or the data in the holdout set wasn't an accuracte representation of the training data. My previous notebook compared neural networks of just Dense layers (2x50, 2x100, 3x50, and 3x100).

Since this is a dataset on digits, I think I will be able to improve accuracy scores by using a CNN and augmenting the data through rotations, shearing, etc.

Results : CNN and data augmentation improved accuracy on the holdout set by 15% and 4%.
