---
mathjax: true
---

# FREQUENCY DOMAIN FILTERING

## DFT and IDFT
The following tasks are implemented:

M X N sinusoidal images are generated using $$sin(2\pi u_0m/M \ + \ 2\pi v_0n/N)$$ for M = N = 500 and their DFT computed. Taken $(u_0,v_0) \ = \ (20,100)$ for
image A and $(u_0,v_0) \ = \ (40,60)$ for image B. The DFT images are visualized.

Both DFTs are added and their inverse image is calculated and it is compared with the pointwise addition of the 2 images in time domain.

## Various Frequency Domain Filtering
Various type of filters are initialized and applied to images and their output noted. The following filters are used:
1) Ideal low pass filter(ILPF)
2) Ideal High pass filter(IHPF)
3) Ideal Band pass filter(IBPF)
4) Gaussian Low pass filter(GLPF)
## How to use:
>Download the ipynb file.

>open it any jupyter notebook

>Run line by line to see how the code works

>You can give any image of your choice(grey scale) by just replacing the image names at appropriate positions

All example images have been included in image file
