# Bat Orientation Calls

Welcome to the Bat Orientation Calls project. Our objective is to classify different species of bats based on their orientation calls, represented as spectrogram images. This Jupyter notebook will guide you through our systematic approach, which includes the use of decision tree classifiers, a feedforward neural network (FFNN), and a convolutional neural network (CNN).

We start by loading and preprocessing the spectrogram images, which are visual representations of the frequency content of the bats' orientation calls over time. These images, along with their corresponding labels, form the basis of our classification task. We ensure the images are in an appropriate format, then proceed to explore and understand the data's characteristics and distributions.

Our first model is a decision tree classifier, a tree-like model that makes decisions based on the features extracted from the spectrogram images. We evaluate its performance using metrics such as accuracy, precision, recall, and F1 score. To improve its generalization, we experiment with techniques like pruning, random forests, Bagging, AdaBoost, and Gradient Boosting.

Next, we build a FFNN with three hidden layers and train it on the spectrogram images. We evaluate its performance and compare it with the decision tree classifier. To visualize the FFNN's learning process, we use learning curves and implement strategies like early stopping and dropout to prevent overfitting.

Our final model is a CNN, a type of model specifically designed for image classification. We use the Keras Tuner to automatically configure different CNN models and train them on the spectrogram images. This allows the models to automatically learn and extract features, making them well-suited to the complex task of bat species classification. The CNN's performance is evaluated on the test data and compared with the other models.

In the end, we compare the results of all three models, providing insights into the effectiveness of traditional machine learning and deep learning techniques for classifying bat orientation calls.