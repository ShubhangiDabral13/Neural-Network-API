
# Keras - Python Deep Learning Neural Network API



![alt text](https://s3.amazonaws.com/keras.io/img/keras-logo-2018-large-1200.png)

Consist of the detail oriented notes with code on **Keras - Python Deep Learning Neural Network API** By [**DeepLizard**](https://deeplizard.com/)

## Table Content:
* [**Why Keras?**](https://github.com/ShubhangiDabral13/Neural-Network-API/edit/master/Keras#Why-Keras-?)
* [**Tensorflow Integration**](https://github.com/ShubhangiDabral13/Neural-Network-API/edit/master/Keras#Tensorflow-Integration)
* [**Difference In Imports**](https://github.com/ShubhangiDabral13/Neural-Network-API/edit/master/Keras#Difference-In-Imports)
* [**How to Install Keras**](https://github.com/ShubhangiDabral13/Neural-Network-API/edit/master/Keras#How-to-Install-Keras)
* [**Course Content**](https://github.com/ShubhangiDabral13/Neural-Network-API/edit/master/Keras#Course-Content)

## Why Keras?

Keras was developed with a focus on enabling fast experimentation. Because of this, it's very user friendly and allows us to go from idea to implementation with only a few steps.

**Now, the question arises why keras? Why not other neural Network API?**

Well knowing more than one API will put more tools in your skill set, and demonstrating this will make you a more valuable candidate., but once you learn one, it is relatively easy to catch on to another. Sometimes, one API may have an advantage over the others for a particular implementation.

## Tensorflow Integration

Keras was originally created by **François Chollet.** Historically, Keras was a high-level API that sat on top of one of three lower level neural network APIs and acted as a wrapper to to these lower level libraries. These libraries were referred to as Keras backend engines.

You could choose TensorFlow, Theano, or CNTK as the backend engine you’d like to work with.

* TensorFlow
*   Theano
*   CNTK
Ultimately, TensorFlow became the most popular backend engine for Keras.

Later, Keras became integrated with the TensorFlow library and now comes completely packaged with it.

![alt text](https://i0.wp.com/neptune.ai/wp-content/uploads/keras_metrics-3.png?fit=1920%2C1377&ssl=1)


Now, when you install TensorFlow, you also automatically get Keras, as it is now part of the TensorFlow library.


## Differences In Imports

From a usability standpoint, many changes between the older way of using Keras with a configured backend versus the new way of having Keras integrated with TensorFlow is in the import statements.

For example, previously, we could access the Dense module from Keras with the following import statement.

           from keras.layers import Dense
           
Now, using Keras with TensorFlow, the import statement looks like this:

          from tensorflow.keras.layers import Dense
          
          
**Before TensorFlow Integration**

        import keras
        from keras.models import Sequential
        from keras.layers import Activation
        from keras.layers.core import Dense
        from keras.optimizers import Adam
        from keras.metrics import categorical_crossentropy
        from keras.preprocessing.image import ImageDataGenerator
        from keras.layers.normalization import BatchNormalization
        from keras.layers.convolutional import Conv2D
        
**After TensorFlow Integration**

          import tensorflow
          from tensorflow import keras
          from tensorflow.keras.models import Sequential
          from tensorflow.keras.layers import Activation, Dense, BatchNormalization, Conv2D
          from tensorflow.keras.optimizers import Adam
          from tensorflow.keras.metrics import categorical_crossentropy
          from tensorflow.keras.preprocessing.image import ImageDataGenerator
          
          
## How To Install Keras

**Linux Setup**

To simplify installation and avoid library conflicts, TensorFlow recommends using a TensorFlow Docker image with GPU support, as this setup only requires the NVIDIA GPU drivers to be installed.

TensorFlow has a [guide](https://www.tensorflow.org/install/docker) with all the corresponding steps to get this set up.

**Windows Setup**

For windows follow the [guide](https://www.tensorflow.org/install/gpu). A detailed overview is given about it.

## Course Content

PART 1: ARTIFICIAL NEURAL NETWORK BASICS

     Section 1: Intro to Keras and neural networks
               Processing data
               Building and training neural networks
               Validation and inference
               Saving and loading models
     Section 2: Convolutional Neural Networks (CNNs)
                Image processing
                Building and training CNNs
                Using CNNs for inference
     Section 3: Fine-tuning and transfer learning
                Intro to fine-tuning and VGG16 model
                Implement fine-tuning on VGG16 model
                Using fine-tuned models for inference
                Intro to MobileNet
                Fine-tuning MobileNet on custom data set
     Section 4: Additional topics
                Data augmentation
                Keras' image labeling implementation
                Achieving reproducible results
                Learnable parameters
                
PART 2: NEURAL NETWORK MODEL DEPLOYMENT

     Section 1: Deployment with Flask
                Introduction to Flask and web services
                Build a simple Flask app and web app
                Send and receive data with Flask
                Host neural network with Flask
                Build neural network web app to interact with Flask service
                Integrating data visualization with D3, DC, Crossfilter
                Alternative ways to access neural network from Powershell and Curl
                Information privacy and data protection
      Section 2: Deployment with TensorFlow.js
                Introduction to client-side neural networks
                Convert Keras model to TFJS model
                Set up Node.js and Express
                Build UI for neural network web app
                Host a neural network with TFJS
                Explore tensor operations through image processing
                Examine tensor operations with debugger
                Broadcasting tensors
                Efficiency of hosting MobileNet in the browser
             
 Detail notes for each section with code is given in their respective folder names.
 
 
 #### Shubhangi Dabral (ShubhangiDabral13)
<a href="https://twitter.com/Shubhi_Dabral"><img 
src="https://news.wjct.org/sites/wjct/files/styles/medium/public/201407/v65oai7fxn47qv9nectx.png" align="left" height="50" width="50" ></a>
<a href="https://www.linkedin.com/in/shubhangi-dabral-b79705145/"><img src="https://cdn2.iconfinder.com/data/icons/simple-social-media-shadow/512/14-512.png" align="left" height="60" width="60" ></a>


 
