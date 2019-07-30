# digitRecognition3
Digit recognition

<h2>Data Source and Datasets:  </h2>
<p>The ​MNIST dataset​ is an acronym that stands for the Modified National Institute of Standards and Technology dataset.  
It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9. 
</p>
<h2>● Data Source​ :  </h2>
○ http://yann.lecun.com/exdb/mnist/ <br>  
■ Number Of images: 60000  <br>
■ Pixel of images: 28x28    <br>
<h2>● Dataset Link​ :</h2>  <br>
○ http://yann.lecun.com/exdb/mnist/<br>  

<h3>Code Requirements </h3>
<p>1. you can install Conda for python which resolves all the dependencies for machine learning.</br>
2. install tensorflow ,  in conda -> $ conda install tensorflow </br>
3. install keras ,  in conda -> $ conda install keras</br>
4. install opencv ,  in conda -> $ conda install opencv</br>
5. handWritingRecognition.py require data set data.csv for training and test</br>
6. application.py require devanagari_model.h5 model for classify the characters.
</p>
<h3> Technique Used </h3>
<p> I have used convolutional neural networks. I am using Tensorflow as the framework and Keras API for providing a high level of abstraction. </p>
<h3> Architecture</h3>
<p> CONV2D --> MAXPOOL --> CONV2D --> MAXPOOL -->FC -->Softmax--> Classification </p>
<p>
<h3>Python Implementation </h3>
1.Dataset- MNIST dataset  <br>
2.Images of size 28 X 28  <br>
3.Convolutional Network Support added. <br> 
<h3> Experimental Values : </h3>
<h4>■ Training  :<h4>
training data of mnist with 10 Epochs 
<h4> ■ Test Set Size :<h4>test  data  of mnist  
<h4>■ Accuracy: <h4> 98.730%  
