# Neural Style Transfer using VGG19 and TensorFlow (2018)

In this project, I've implemented a neural style transfer model using VGG19 and TensorFlow. The model applies the artistic style of one image to the content of another using deep neural networks.

Getting Started:
To get started with this project, you'll need to have the following installed:

    TensorFlow 2.x
    NumPy
    Matplotlib

How it Works:

I started by downloading the pre-trained VGG19 model, which was trained on the ImageNet dataset. However, since VGG19 is a large model, I only chose the layers that were important for neural style transfer. I tweaked the VGG19 model by freezing its layers and only selecting the convolutional layers that were essential for style transfer.

Next, I chose two images: a content image and a style image. The content image is the image that I wanted to apply the style to, and the style image is the image whose style I wanted to transfer.

The model then computes the style and content losses, which are then used to update the pixels of the generated image. The model continues to update the generated image until it matches the content image while also incorporating the style of the style image. The number of epochs can be customized to your choice.

Finally, I tested the model on a photo of a friend, and I was amazed by the results! The generated image had my friend's content, but with the style of the style image.

Conclusion:
In conclusion, this project demonstrates how neural style transfer can be implemented using VGG19 and TensorFlow. By choosing only the essential layers, the model runs more efficiently, and by tweaking the layers, I was able to achieve great results on my friend's photo. 

I hope this project serves as a starting point for anyone interested in implementing their neural style transfer models.
