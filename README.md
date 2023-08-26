# Deep_Learning_CNN
The aim of this project is to train the given images with the best possible model and predict the test images with high mean accuracy. The images are divided into fourteen categories. Here, we develop three models in order to cope with the problem: \n
1. OurCNN
2. Fine-tuning with vgg16
3. Fine-tuning with ResNet50.
   
The first step in tackling this problem is to actually know that our model is overfitting. After identifying the problem, we can prevent it from happening by applying Dropout technique. Also, one of the most common techniques, which is used in all our models, is Data Augmentation that can help us if our dataset is too small, or we have overfitting.
