# keras-flask-image-classifier
A simple implementation for image classifier web application with Keras and Flask. The application allows to upload image file and determines what animal (<b>Cat</b> or <b>Dog</b>) is located on it with using convolutional neural network builded in Keras.


## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
1. Clone this repository
2. `cd keras-flask-image-classifier`
3. `python main.py`
4. Open `http://127.0.0.1:5000/` on your browser
5. Click the file select button and select one of the test images


### DEMO
![Screenshot](demo.png)


### Prerequisites
The application requres some external libarraies to run (flask-1.1.1, pillow-6.2.1, tensorflow-2.0.0, keras-2.3.1, numpy-1.17.3)

All dependencies you can find from requirement.txt and install with:
`pip install -r requirements.txt`


### Image Classifi
For building image classifier model we used Keras with transfer learning (ImageNet) + data augentation and train it with Kaggle dataset.
[a link](https://www.kaggle.com/mitkir/cat-dog-classifier-using-vgg16-tl-da)
