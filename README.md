# README #

This project has been developed for the Images and Videos Analysis class by [t0re199](https://github.com/t0re199) and [adel3roman6](https://github.com/adel3roman6).
       
The project required to perform a **Multi-Class** and **Multi-Label** Classification on an unbalanced dataset. In particulat, the dataset contains frames of film trailer (the number of frames can be different for each film).  
   
In this project the well-known image classification architectures **ResNet34** and **Vgg-16** have been used. Since **PyTorch** has been used as Gradient Computing Library, the above cited architecture were taken from the **TorchVision** Library.   
     
Since the dataset contains unlabeled data too, in order to improve the model's extracted features quality a **self-supervised learning** strategy has been applied during the last epochs of the training process.        