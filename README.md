[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaketMunda/dog-breed-prediction/blob/master/dog_vision.ipynb)

# Dog Breed Prediction
Deep learning model for predicting dog breed using Tensor Flow Hub

## About

This is a beginner level project on TensorFlow and TensorFlow hub to understand the concepts and workflow of DeepLearning Models using Unstructured data.

### Workflow

- Getting our data ready
  - Import the data (Turning into Tensors)
  - Create Train set and Validation Set
  - Preprocess the images -> Turn them into Tensors
  - Turning into Batches
- Building a Deep Learning Model
- Training a model on few sample
- Evaluation and Making prediction on few samples
- Visualize and Tests on few samples
- Saving and Loading the Model (trained on few samples)
- Training the model in full data
- Testing and Making predictions on trained model with full data

### Concepts

- Google Colab, GPU usage
- Convert Images into Tensors, covered in Preprocessing of Images
- Batch & Unbatch data
- Data Visualization 
- Transfer Learning
- Keras & its layers and executions
- Tensorboard Callbacks
- Early Stopping
- Epochs
- argmax(), argsort()

### Libraries & Workspace 

- Numpy
- Pandas
- Matplotlib
- TensorFlow
- TensorFlow Hub
- TensorBoard Magic Function (for visualizing performance)
- Image Classfication Model ([mobilenet_v2](https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/5)) for Transfer Learning

### Dataset

[Download from Kaggle](https://www.kaggle.com/competitions/dog-breed-identification)

### Evaluation 

Evaluation will be done on Multi Class Log Loss between the predicted probability and the observed target.

[More Details...](https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation)

### To Do

- [ ] Create a confusion matrix with our models predictions and true labels
