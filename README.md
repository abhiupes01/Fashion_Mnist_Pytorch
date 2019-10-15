# Fashion_Mnist_Pytorch
This repo shows the CNN implementation based in pytorch for the fashion mnist dataset. The basic structure of the CNN is : 
Conv(1,16) ==>> BatchNorm ==>> MaxPool ==>> Conv(16,32) ==> BatchNorm ==>> MaxPool ==>> Fully Connected Layers

The Data set could be downloaded from the : https://github.com/zalandoresearch/fashion-mnist
The Overall accuracy achieved in 10 epochs for train is 93% while for test it 91.
