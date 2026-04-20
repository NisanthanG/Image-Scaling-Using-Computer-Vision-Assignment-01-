# Image-Scaling-Using-Computer-Vision-Assignment-01-

This study systematically implemented and evaluated a comprehensive suite of image processing techniques spanning intensity transformations and  neighbourhood filtering. The key findings are summarized below:
•	Gamma correction provides intuitive non-linear brightness control; performing correction in the L*a*b* colour space ensures hue preservation that direct RGB gamma cannot guarantee.
•	Custom histogram equalization accurately reproduces OpenCV's reference implementation and demonstrates how global intensity redistribution reveals hidden image detail.
•	Otsu thresholding combined with selective histogram equalization is a powerful pipeline for foreground enhancement in scenes with extreme lighting contrast.
•	Gaussian filtering provides effective noise suppression with a smooth, artifact-free frequency response, while median filtering is significantly superior for impulsive (salt-and-pepper) noise due to its edge-preserving non-linear nature.
•	Bilateral filtering achieves edge-preserving smoothing by combining spatial and range Gaussian weights; the theoretical framework clearly explains why it outperforms linear Gaussian filtering near boundaries.
•	The Convolution Theorem unifies spatial and frequency domain perspectives, providing a rigorous basis for understanding filter behaviour and predicting artifacts such as ringing.
•	Homomorphic filtering targets the illumination-reflectance model directly, offering illumination correction superior to histogram equalization in scenes with spatially non-uniform lighting.
Together, these results demonstrate that the choice of processing technique must be matched to the specific nature of the image degradation and the enhancement goal. No single technique is universally optimal; instead, a thorough understanding of the theoretical underpinnings and practical trade-offs is essential for effective image processing system design.
