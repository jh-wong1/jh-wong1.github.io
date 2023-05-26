My next task is to classify AI generated image compare to real image. As the quality of AI-generated images has rapidly increased, leading to concerns of
authenticity and trustworthiness. Therefore this task is to attempt using computer vision to differentiate between the two types of images.

The task can be found in [Kaggle](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images) and further information in [the paper](https://arxiv.org/abs/2303.14126).

I have attempted this problem with trying three different models of Convolutional Neural Network (CNN) and compare their result. The models I used are:

1. `resnet18`
1. `squeezenet1_0`
1. `densenet121`

They all sucessfully to differentiate the two types of images, and the result of each is shown in the confusion matrix below.
## resnet18
![Image of resnet18 result](/images/cf1.png)

## squeezenet1_0
![Image of squeezenet1_0 result](/images/cf2.png)

## densenet121
![Image of densenet121 result](/images/cf3.png)
 
 The result shows `densenet121` have the best result, with an accuracy of 97.25%!
