# Hybrid_Image

A hybrid image is the sum of a low-pass filtered version of  one image and a high-pass filtered version of a second image. There is a free parameter, which can be tuned for each image pair, which controls how much high frequency to remove from the first image and how much low frequency to leave in the second image. This is called the “cutoff-frequency”.

Reading this [paper](https://stanford.edu/class/ee367/reading/OlivaTorralb_Hybrid_Siggraph06.pdf) will help in understanding of hybrid images.

### Input Images:

Image-1:

![Image-1](./hybrid_pyramid_input/data/Afghan_girl_after.jpg)

Image-2:

<img src="./hybrid_pyramid_input/data/Afghan_girl_before.jpg" alt="Image-2" />

# Results: 
### High and Low frequency Images:

Low-pass filtered Image-1:  

![Image-1](./Results/low_frequencies.jpg)

High-pass filtered Image-2:

![Image-2](./Results/high_frequencies.jpg)

### Hybrid Image:

![Hybrid_image](./Results/hybrid_image.jpg)
