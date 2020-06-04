# Neural-Style-Transfer

This project is based on Transfer Learning. In this I have used the VGG19 model present in keras pretrained on the imagenet dataset
and it is basically designed to output a new image having the same content as an input content image but styled as per the style image.
This project is a very nice way for someone who has the theoretical knowledge of deep learning and is looking for a way to start with practical implementations using python and tensorflow.

To try it on your own, you just need to clone the repo and install the dependencies and get started with this jupyter notebook.

## Side note

This code was trained for a very few epochs and quite a high learning rate because it was all that was required for the sample images.
However, if you want the model to learn a bit more complex or a lot simpler features you should just try to play around with the 
layers and the filters selected for loss computation. You can visualise the output of each layer in the notebook and then decide which layer to use for the loss computation and you will definitely get a lot better results. Just try it out :)
