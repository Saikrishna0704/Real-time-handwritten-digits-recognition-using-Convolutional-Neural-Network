# Real-time-handwritten-digits-recognition-using-Convolutional-Neural-Network

# Environment
* Colab
* Tensorflow
* Keras
* Numpy
* Pandas
* Matplotlib
* Sklearn
* Seaborn
* OpenCV

# Data set
The MNIST data set (Modified National Institute of Standards and Technology database) has 70,000 handwritten images, which is divided into training data set of 60,000 images, and a testing data set of 10,000 images. Each digit in the data set is normalized and centered in a gray-level image with size 28 * 28, or with 784 pixels. All the pixels are stored in csv files, training files has 60,000 rows * 785 columns and testing files has 10,000 rows * 785 columns. Few sample images from MNIST data set are shown in the below figure.

![Dataset_2](https://user-images.githubusercontent.com/83408384/116880542-c43a3c00-ac3f-11eb-85e0-a0c37f687222.png)

# Convolutional Neural Network Model 

|               | Layers                        | 
| ------------- |:-----------------------------:| 
| CL1           | Convolutional Layer 1         | 
| ML1           | Max Pooling Layer 1           |   
| CL2           | Convolutional Layer 2         | 
| ML2           | Max Pooling Layer 2           |  
| CL3           | Convolutional Layer 3         | 
| FL1           | Dropout & Flatten Layer 1     |   
| DL2           | Dense Layer 1                 | 
| DL2           | Dense Layer 2                 | 

![Diagram](https://user-images.githubusercontent.com/83408384/116879811-c51e9e00-ac3e-11eb-8397-f2f37c774aad.png)
 

# Output
A real time handwritten scanned image was taken and uploaded in the Google Colab.
The trained model recognized the digits from the image and displayed another image with digital numbers.

![Capture](https://user-images.githubusercontent.com/83408384/116871250-9d750900-ac31-11eb-8293-dbf662b2cc66.PNG)
