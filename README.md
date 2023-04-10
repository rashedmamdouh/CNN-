Flower Classification
Objectives 1. Become familiar with CNNs models and transfer learning. 2. Applying fine-tuning and analyzing the performance of different classifiers on a large
image dataset.
1 Problem Statement
Using a petals to metals dataset, which is a dataset for flower classification. We’re
classifying 104 types of flowers based on their images drawn from five different public datasets.
Some classes are very narrow, containing only a particular sub-type of flower (e.g. pink prim￾roses) while other classes contain many sub-types (e.g. wild roses).
2 Data
2.1 Download the Dataset and Understand the Format
(a) Download the dataset from the class’s Microsoft Teams.
(b) Write my own function that loads an image and visualize some images from different
classes.
(c) Display the number of samples in each class.
2.2 Split Data
(a) Split the training data into 90% training and the rest for validation.
(b) Use the validation data during training as validation set.
(c) Use the test data only for model evaluation, don’t introduce it at any step during training.
2.3 Data Preprocessing
The pixel values in images must be scaled prior to providing the images as input to a deep
learning neural network model during the training or evaluation of the model.

3 Build CNN Models
I required to build my own network from scratch and use two or more famous archi￾tectures. It is also required to tune the hyper-parameters of these models on the validation set.
I saved my model after each epoch so it can be loaded later for further training or
evaluation.
(a) Simple model of my own
Build a simple CNN model on my own using 2D convolutions, pooling layers, etc.
(b) Famous CNN Architectures
I used the following architectures:
(a) VGG
(b) ResNet
(c) GoogLeNet
(c) Transfer Learning
Use pretrained weights for the architecture instead of training the network from scratch.
ImageNet is the mostly used dataset in pretraining CNN architectures.
(d) Ensemble
Integrating more than one model using ensemble could enhance the performance of clas￾sification.
4 Big Picture
Compare between the performance of the different models by realizing the following on the
testing data.
• Compute the accuracy and Macro F-Score for each model.
• Plot the confusion matrices and find the most confusing classes.
5 Report
My report contains the following:
(a) Plots of the performance results obtained in the evaluation part.
(b) Comparison and analysis of the performance results across models and different hyperpa￾rameters.
(c) Success and failure cases of the model should be presented as well. (Plot the images)
