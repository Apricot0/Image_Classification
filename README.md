# Birds Classification
## Description
This project is an introduction to deep learning tools for computer vision. [PyTorch](http://pytorch.org).

In step 1 of the project I trained a deep convolutional network (*CNN*) from scratch to recognize scenes. I designed a simple network architecture with jittering, normalization, and regularization.

For step 2 Fine-tuning a pre-trained deep network is involved. We used the pretrained *AlexNet* & *ResNet* network which was not trained to recognize scenes at all.

These two approaches represent the most common approaches to recognition problems in computer vision today -- train a deep network from scratch if you have enough data (it's not always obvious whether or not you do), and if you cannot then instead fine-tune a pre-trained network.

For Step 3 I trained a small *Vision Transformer (ViT)* from scratch. ViT is pre-trained on large amounts of
data and transferred to multiple mid-sized or small image recognition benchmarks(ImageNet, CIFAR-100, VTAB, etc.), ViT attains excellent results compared to state-of-the-art convolutional networks.


## Dataset
Under the root folder, there should be a folder named "data" containing the images.

## Some Tutorials (PyTorch)
- PyTorch for deep learning toolbox (follow the [link](http://pytorch.org) for installation).
- For PyTorch beginners, please read this [tutorial](http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html).
- Feel free to study more tutorials at http://pytorch.org/tutorials/.
- Find cool visualization here at http://playground.tensorflow.org.
