# ML_CNN_ImgClass_Tensorflow

Date: 2017.8

Classify images using CNN(Convolutional Neural Network)

Dependencies: Tensorflow

Data sets: CIFAR10
- Data :60000 32x32 colour images in 10 classes, with 6000 images per class(50000 training images and 10000 test images)
- Categories : airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck

Result: 
- Case1: Training steps :100 / Training Time : 32sec / Result : 36.9%
- Case2: Training steps :1000 / Training Time : 6min 22sec / Result : 60.8%
- Case3: Training steps : 10000 / Training Time : 60min 3sec / Result : 81.5%
- Case4: Training steps : 100000 (100K) / Training Time :10h 32min / Result :86.8%

*MEMO: Tested in Linux(Ubuntu)

*MEMO: Test logs for each case are included

*Reference: http://tensorflow.org/tutorials/deep_cnn/
