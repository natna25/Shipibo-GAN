# Shipibo-GAN
Project using Generative Adversarial Networks to generate images of Shipibo tribe patterns and also 
make some animations.

The Shipibo is a tribe indigenous to South America. They are located somewhere deep in the Amazon 
forest and are threatened today by all of the trouble that this forest is having today.

The goal of this project was to leverage the Deep Learning architecture of Generative Adversarial 
Networks as presented by Ian Goodfellow in 2014. This sort of architecture has been greatly improved 
uppon in the past few years. Nvidia researches were able to generate super realistic images with 
architectures such as ProGAN and StyleGAN.


# 1) Collecting the Dataset

All of the data here was collected from an image scrapper that goes onto google images and retrieves a 
few hundred images per keyword. This yieled a dataset of aroun 900 images which I went onto clean by 
hand to reach around 400 good quality images. 

The problem is that this dataset was nowhere near enough to be able to train a proper GAN on it. In 
order to greatly increase the amount of data I relied on some aggressive data augmentation techniques
in order to squeeze out as much data as possible. I had to sacrifice the high level details and symetry
of the original images in order to take a lot of random slices from the original picture which I would
then 
