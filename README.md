# DeepLearning-for-ComputerVision-with-MATLAB 
[![View Example files for "Deep Learning for Computer Vision with MATLAB" Webinar on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/58030-example-files-for-deep-learning-for-computer-vision-with-matlab-webinar)

These are the example files used in the webinar ["Aprendizaje Profundo para Visión Artificial con MATLAB" - Spanish](https://www.mathworks.com/videos/deep-learning-for-computer-vision-with-matlab-1540981496452.html) ("Deep Learning for Computer Vision with MATLAB").


Deep Learning is an area of Machine Learning that uses multiple nonlinear processing layers to learn useful representations of features directly from data. This webinar shows the fundamentals of Deep Learning for Computer Vision and how to use Convolutional Neural Networks (popularly known as CNNs or ConvNets) to solve object classification/recognition problems.

The source code consists of 3 different examples:
1. Running a trained CNN (/WebcamClassification)
2. Training a CNN from scratch (/CIFARTraining)
3. Fine-tuning a pre-trained CNN. Transfer learning (/TransferLearning)
Examples 1) and 3) make use AlexNet [1]. In order to download the trained CNN [2], run the file downloadAndPrepareCNN.m (if using R2016a) or download AlexNet Network support package (if using R2016b or later).

References:
[1] Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). Imagenet classification with Deep Convolutional Neural Networks. Advances in Neural Information Processing Systems (pp. 1097-1105).
[2] Vedaldi, A., & Lenc, K. (2015, October). MatConvNet: Convolutional Neural Networks for MATLAB. Proceedings of the 23rd ACM International Conference on Multimedia (pp. 689-692). ACM.
