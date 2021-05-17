# AI-PROJECT

# Image Compression
This is a simple image memorization, image compression project. In this project I propose a deep neural network approach for mapping the 2D pixel coordinates in an image to the corresponding Red-Green-Blue (RGB) color values.

I have used a sequential model containing two dense layers. First Layer to receive the input data and the next layer to output RGB value.  During the training process, the neural network learns to encode the input image within its layers. Activation functions used is sine and sigmoid. Sine activation function allow us to actively deal with image type data.

I have achieved an accuracy of 99.997 on the training the model. 

**INPUT IMAGE:**

![image](https://github.com/sidharth48-hub/AI-PROJECT/blob/main/input.png)

**OUTPUT IMAGE:**

![image](https://github.com/sidharth48-hub/AI-PROJECT/blob/main/output.png)

# Installation

The demontration script are written Python 3 using Keras with Tensorflow back-end, along with other utility libraries.

## Linux
Install Python 3.
```
sudo apt-get install python3.6
```
Install python module requirements from provided text file.
```
pip install -r requirements.txt
```

## Windows and Mac OS X
Install Python 3.
Install python module requirements from provided text file.
```
pip install -r requirements.txt
```

## Docker version
[Install Docker](https://docs.docker.com/install/#releases)
Build Docker image.
```
sudo make bash GPU=0
```
Clone repository.
Install python module requirements from provided text file.
```
pip install -r requirements.txt
```
