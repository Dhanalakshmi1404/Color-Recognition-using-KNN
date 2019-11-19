# Color-Recognition-using-KNN
This project focuses on color classifying by K-Nearest Neighbors Machine Learning Classifier which is trained by R, G, B Color Histogram. It can classify White, Black, Red, Green, Blue, Orange, Yellow and Violet. If you want to classify more color or improve the accuracy you should work on the training data or consider about other color features such as Color Moments or Color Correlogram.Here i use color historam.

Tools : OpenCV

Concepts : OpenCV, Color histogram, EuclideanDistance, k nearest neighbours

You should know 2 main phenomena to understand basic Object Detection/Recognition Systems of Computer Vision and Machine Learning

1.Feature Extraction : Color Histogram

Perform feature extraction for getting the R, G, B Color Histogram values of training images.
Color Histogram is a representation of the distribution of colors in an image. For digital images, a color histogram represents the number of pixels that have colors in each of a fixed list of color ranges, that span the image's color space, the set of all possible colors.

2.Classification : K-Nearest Neighbors Algorithm

K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure (e.g., distance functions). KNN has been used in statistical estimation and pattern recognition already in the beginning of 1970’s as a non-parametric technique.



Calling "feature_extraction.py" to create training data by feature extraction

Calling knn_classifier.py for classification

Now run "color_classification_image.py" to test the model

we can find Training data set from https://github.com/ahmetozlu/color_recognition/tree/master/src/training_dataset. Place all colors in one folder and name it as training_dataset.


