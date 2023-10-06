# Dog Breed Identification

![image](Dog-Breed.png)

This project is targets making different dog breed identification model using -

- 1. Custom CNN with 3 classes breed ~ `97%` accuracy
- 2. MobileNet_v2 with ~1000 and full-dataset ~ `0.9987` accuracy
- 3. Inception_resnet_v2 with full dataset ~ `0.85` accuracy
- 4. Streamlit app for deployment

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.x and TensorFlow Hub.

## 1. Problem

Identifying the breed of a dog given an image of a dog.

When I'm sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

## 2. Data

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data 

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set (these images have labels).
* There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them). 

## Model

1. CNN ~ Custom Convolutional Neural Network with Tensorflow
2. MobileNet_v2 from Tensorflow_hub
3. Inception_resnet_v2 from keras.application

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for suggestions, bug reports, or improvements.

## License

This project is licensed under the [MIT License](LICENSE).
