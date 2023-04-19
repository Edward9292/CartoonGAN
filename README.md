# CartoonGAN
In recent years, the field of computer vision and image processing has seen significant advancements, particularly in generative models. One such development is CartoonGAN, a generative adversarial network (GAN) that transforms real-world images into cartoon-like representations.   
    
![test3.png](https://raw.githubusercontent.com/Edward9292/CartoonGAN/main/Images/test/transformed_test3.jpg)
![result_test3.png](https://raw.githubusercontent.com/Edward9292/CartoonGAN/main/Images/test/result_test3.png)   
![test1.png](https://raw.githubusercontent.com/Edward9292/CartoonGAN/main/Images/test/transformed_test1.png)
![result_test1.png](https://raw.githubusercontent.com/Edward9292/CartoonGAN/main/Images/test/result_test1.png)   


# Data Set
All the training images for training the model is located under directory `Images`
   
- *Cartoon Images (around 1,800):* This set consists of cartoon images that conclude human, animal, environmental images, and so on.   
- Edges Smoothed Cartoon Images (around 1,800): This set contains the same images as the first category but has been processed using a Gaussian filter to smooth the edges to let the CartoonGAN model's edge-aware smoothing technique work better.   
- Real-world Photographs (around 2,000): This set mainly uses as input for the generator, after passing through the return result to the discriminator to decide if this result follows the expectation.   


# References
