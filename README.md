<html>
<body>
<h1> using neural network  to recognize handwritten digits</h1>
<div id="introduction">
    <h2>Overview</h2>
    <p>In this project we'll build a simple neural network and train it, on a GPU-enabled server, to recognize handwritten digits using the MNIST dataset. Training a classifier on the MNIST dataset is the hello world of image recognition, you should have a basic understanding of the<strong> Multilayer Perceptron</strong> class of neural network.</p>
    <p>MNIST contains 70,000 images: 60,000 for training and 10,000 for testing. The images are grayscale, 28x28 pixels, and centered to reduce preprocessing and get started quicker. </p>
    <p> Keras is a high-level neural network API focused on user friendliness, fast prototyping, modularity and extensibility. It works with deep learning frameworks like Tensorflow, Theano and CNTK, so we can get right into neural networks without a lot of fuss.</p>
    <p>Let's get started by setting up our environment with Keras using Tensorflow as the backend.</p>
<h3> 1 .explanation of the project</h3>
<p>Firstly, we will import required keras libraries</p>
<h4> 2 .Preparing the Dataset </h4>
<p>Now we'll load the dataset using this handy function which splits the MNIST data into train and test sets.</p>
<p>(X_train, y_train), (X_test, y_test) = mnist.load_data()</p>
<h4>3 .Result</h4>
<p>Classical fully connected neural networks retrieved 98.01% accuracy whereas convolution neural networks did exceed the 99% accuracy limit. That is an incredible result.</p> 
<img src="https://user-images.githubusercontent.com/33552284/34998116-7e5d8090-fade-11e7-94c5-0436b4457e3e.PNG"/>
<img src="https://user-images.githubusercontent.com/33552284/34998734-2d38c9f2-fae0-11e7-9ea3-2c84fad109c0.PNG"/>

    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
