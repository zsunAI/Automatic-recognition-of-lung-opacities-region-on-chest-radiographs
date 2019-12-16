# Automatic-recognition-of-lung-opacities-region-on-chest-radiographs
  肺部不透明区域识别
  
  We presents a deep learning method based on Residual Neural Network (ResNet) for lung opacities region recognition. Using multiple deep residual networks, more spatial information is included, and the boundary of opaque lung regions can be obtained more accurately. Specifically, a residual neural network with a depth of 23 layers (ResNet-23) is pre-trained on large-scale medical image data sets to extract the features of the depth convolution layer of chest radiograph (CXR) images, and the feature vectors are obtained by batch normalization. Then the feature vectors are transformed into a probability map with a depth of 1 through a convolution layer. Next, the up-sampling is carried out to restore the same size as the input image. Finally, the development of related system interface are completed, which can input a lung image and output the recognition function of whether the opacities region exist or not.

  Using the open RSNA pneumonia challenge data set, 550 images were evaluated with the proposed framework. The correct detection rate of opacities region was 96.2%, and the intersection-over-union was 0.762. At the same time, compared with the existing VGGNet and GoogLeNet, the ResNet-23 framework used in this paper can produce better recognition performance with simpler network complexity and solve the problem of recognition of opaque areas in CXR images.
  
 ![image](https://github.com/1579477793/Automatic-recognition-of-lung-opacities-region-on-chest-radiographs/blob/master/result/a1.jpg)
  ![image](https://github.com/1579477793/Automatic-recognition-of-lung-opacities-region-on-chest-radiographs/blob/master/result/b1.jpg)

![image](https://github.com/1579477793/Automatic-recognition-of-lung-opacities-region-on-chest-radiographs/blob/master/result/c.jpg)


![image](https://github.com/1579477793/Automatic-recognition-of-lung-opacities-region-on-chest-radiographs/blob/master/result/d.jpg)
![image](https://github.com/1579477793/Automatic-recognition-of-lung-opacities-region-on-chest-radiographs/blob/master/result/e.jpg)
