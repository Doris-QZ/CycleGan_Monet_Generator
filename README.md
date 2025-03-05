# Introduction
In this [Kaggle Competition](https://www.kaggle.com/competitions/gan-getting-started), my goal is to build a Generative Adversarial Network (GAN), specifically a CycleGAN model, capable of generating images in the style of Monet. 

A GAN consists of at least two neural networks: a generator and a discriminator. These two models work against each other--the generator tries to produce realistic images to fool the discriminator, while the discriminator attempts to distinguish between real and generated images.

### Data
The dataset contains two TFRecord files, with all images having three color channels (RGB): 
* **monet_tfrec** - 300 Monet paintings, each sized 256x256 pixels, in TFRecord format
* **photo_tfrec** - 7028 photos, each sized 256x256 pixels, in TFRecord format

**Data Source:** Amy Jang, Ana Sofia Uzsoy, and Phil Culliton. I’m Something of a Painter Myself. https://kaggle.com/competitions/gan-getting-started, 2020. Kaggle.
