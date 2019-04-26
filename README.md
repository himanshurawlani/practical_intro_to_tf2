# Practical Introduction to TensorFlow 2.0
This repository introduces the new Tensorflow 2.0 in a practical way by building an image classifier which classifies 5 classes of flowers. It covers the following:
1. Downloading and preprocessing data using TensorFlow Datasets
* Checking out available datasets and their features
* Downloading the dataset (tfds.load()))
* Pre-processing the dataset
* Visualizing the dataset

2. Building and training an image classifier model using Keras high level API
* Building a simple CNN in Keras
* Visualising the model
* Compiling and training the model
* Training the model using data augmentation
* Using TensorBoard inside notebooks

3. Downloading and fine-tuning InceptionV3 pre-trained model
* Downloading pre-trained model
* Adding classification head
* Training the classification head
* Fine tuning the model

4. Serving the trained model using TensorFlow Serving
* Tensorflow Serving installation
* Starting TensorFlow Serving
* Making REST requests
* Parsing the response

Read the Medium article explaining the above concepts in detail [here](https://medium.com/@himanshurawlani/getting-started-with-tensorflow-2-0-faf5428febae?source=friends_link&sk=216dd7c2de38e8344737221768126b14).
