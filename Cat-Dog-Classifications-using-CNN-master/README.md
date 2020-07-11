# Cat-Dog-Classifications-using-Keras-Tensorflow-CNN
Google Colaboratory link for this project : https://colab.research.google.com/drive/1XyDaJ37_pllGA0TZKeXeideJxFVHn66J?usp=sharing

As data set is quite big so mentioning the Dataset link to download from :
 - https://www.kaggle.com/arpitjain007/dog-vs-cat-fastai

This is a project or a app to classify whether images contain either a dog or a cat.

![Architeture](https://user-images.githubusercontent.com/61824566/86999298-e6a22b00-c1cf-11ea-8cfd-257793e1f890.PNG)


Layers needed by CNN : 

* Conv2D :- Basic Convolutional layer . Here we will be using a 64 neuron layer.

![filters](https://user-images.githubusercontent.com/61824566/86999309-eefa6600-c1cf-11ea-86ab-d5610193ce23.PNG)

* Dense :- Dense layer is needed by every neural network to finally output the result however every once in while using a Dense layer helps in making model learn.

* MaxPooling :- CNN has a concept of max pooling. After every convoulution we get some values in a kernel. However in max pooling we select max kernel value.

![pooling](https://user-images.githubusercontent.com/61824566/86999323-f3bf1a00-c1cf-11ea-8cd5-35c15fbd2840.PNG)

* Flatten:- Conv2D layer returns doesn't return a flatten data hence we need Flatten layer before feeding it into final Dense layer

![flattening](https://user-images.githubusercontent.com/61824566/86999318-f15cc000-c1cf-11ea-9b6f-51872415433d.PNG)


Note :
A convolutional network receives a normal color image as a rectangular box whose width and height are measured by the number of pixels along those dimensions, and whose depth is three layers deep, one for each letter in RGB. Those depth layers are referred to as channels.

 - RGB layers of an image :
 
 ![RGB](https://user-images.githubusercontent.com/61824566/86999330-f6217400-c1cf-11ea-89ec-d24967ff20c2.PNG)
