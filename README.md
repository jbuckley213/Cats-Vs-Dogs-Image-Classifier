# Cats-Vs-Dogs-Image-Classifier

Overview
==========
A project that trains a convolutional nerual network that can decipher whether there is a dog or cat in an image.

Dependencies 
==========
* Numpy (http://www.numpy.org/)
* Keras ```pip3 install keras```

Convolutional Network
==========
The network take an input of 64 by 64 pixel images. The images are filter by 32 filters to search for patterns in the pixels. The filters sequences undergo pool which reduces the size of the sequence while keeping the most reconized patterns. There is a second layer where is process repeats. The seqeunces are flattened and the fully connected layer with a single output. The network is compiled and trained. 

