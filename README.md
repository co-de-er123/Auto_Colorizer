# Auto_Colorizer
Built and trained an autoencoder neural network in Keras using TensorFlow backend for converting old/grayscale images into colored images.
Leveraging deep learning techniques, the model is trained on a dataset of grayscale images paired with their corresponding colored versions.The architecture typically involves a convolutional neural network (CNN) that learns to map grayscale input images to their corresponding color representations.
During training, the model aims to minimize the difference between its predicted colorized images and the ground truth colored images.Once trained, the model can take grayscale images as input and generate plausible colorizations,capturing patterns and relationships learned from the training dataset. The use of TensorFlow facilitates efficient computation on both CPUs and GPUs, making it suitable for large-scale training tasks.
For encoding the input image, used pre-trained VGG-16 model trained on ImageNet Dataset , for decoding the encoded latent representation, used UpSampling Layers from TensorFlow Layers API

