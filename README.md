# Image_generation_GAN_AAR
Please see [research paper]("Research paper.pdf") for more information.
# Abstract
This paper discusses ways to improve currently existing image-generation programs with the help of conventional image processing tools. By utilizing a Generative Adversarial Network (or GAN), computers can be trained to generate images. In particular, the SBIS (Sketch-based Image Synthesis) program generates a fully colored image from a pseudo-sketch. However, there exists a large gap between computer-generated images and natural images. To bridge the gap, a combination of Gaussian blurring and binary thresholding was applied to the pseudo-sketches used for training. The resulting pseudo-sketches were used to retrain the GAN. As a result, the output of the Sketch-Based Synthesis program was substantially naturalized. One major discrepancy that was fixed was the amount of color on the sketches: many parts of the original GAN had white spots on the colored images, but every part of the image was colored in our improved version. However, our method only focused on handbags. Thus, a way forward is to apply our smoothing method to other objects such as tables and chairs and to observe if anything happens.
