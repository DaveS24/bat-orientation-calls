# Bat Orientation Calls

The "Bat Orientation Calls" project aims to classify bat types using spectrograms in image format as input. The project utilizes both a decision tree classifier and a convolutional neural network (CNN) to achieve this task. The process followed in this Jupyter notebook is as follows:
<br></br>

**Loading and Preprocessing the Images with their Labels**

The first step in our project is to load the spectrogram images and their corresponding labels. Spectrograms are visual representations of sound that display the frequency content of an audio signal over time. These spectrograms are used as input data for the classification task. The images are preprocessed to ensure they are in a suitable format for our machine learning models.
<br></br>

**Data Exploration**

Before we begin modeling, we explore our data to understand its characteristics and distributions. This step helps us gain insights into the data and informs our choice of models and preprocessing steps.
<br></br>

**Setting up a Decision Tree Classifier**

We first set up a decision tree classifier, a machine learning algorithm that uses a tree-like model of decisions and their possible consequences. The decision tree classifier is trained on the features extracted from the spectrogram images, learning patterns and rules from the training data to make predictions on unseen data.
<br></br>

**Analyzing Decision Tree Results**

After training the decision tree classifier, we analyzed its performance using various metrics such as accuracy, precision, recall, and F1 score. We also visualized the decision tree to grasp the size of it. The decision tree classifier showed decent performance, but it had some limitations. For instance, it tended to overfit the training data, leading to lower performance on the test data. To mitigate this, we experimented with techniques such as pruning the tree and random forests as well as using ensemble methods like Bagging, AdaBoost, and Gradient Boosting. These methods helped improve the model's generalization ability and resulted in better performance on the test data.
<br></br>

**Setting up a CNN Model**

Next, we set up a convolutional neural network (CNN), a deep learning model specifically designed for image classification tasks. CNNs are capable of automatically learning and extracting features from images, making them well-suited for our bat type classification task. The CNN model is trained on the spectrogram images, allowing it to learn complex patterns and relationships between different bat types.
<br></br>

**Analyzing CNN Results**

After setting up and training the CNN model, we evaluated its performance on the test data. The CNN model showed excellent performance, outperforming the decision tree classifier by far. This is likely due to the CNN's ability to automatically learn and extract features from the spectrogram images, which are more complex and high-dimensional than the features used by the decision tree classifier. We visualized the learning curves of the model to understand its learning process and diagnose issues such as overfitting or underfitting. We also used techniques such as early stopping and dropout to prevent overfitting and improve the model's generalization ability. The results from the CNN model demonstrated the power of deep learning for image classification tasks.
<br></br>

**Comparing Results**

Finally, we analyze and compare the performance of the different models. This comparison provides insights into the effectiveness of traditional machine learning algorithms and deep learning models in the context of bat orientation calls classification.
<br></br>

By following this process, the project aims to explore and compare the performance of different machine learning approaches for bat type classification.