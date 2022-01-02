# Coronary vessel segmentation using multiresolution and multiscale deep learning

# REVIEW

* WRITING 2/5 poor english
* METHOD 4/5 simple and intuitive
* VALIDATION 4/5 extensive validation with 20 sota methods, scarsity of test data compensed by cross validation.
* STRENGHTS: Impressive results for such a simple method.
* WEAKNESSES: Bad graphs, bad english and unprecise/unspecific technical considerations.

# Links
* https://github.com/marioviti/Literature/blob/main/1-s2.0-S2352914821000927-main.pdf
* https://www.sciencedirect.com/science/article/pii/S2352914821000927#fig5

## Abstract

XRA 2D coronary vessel segmentation. 
Outperforms 20 state-of-the-art methods including recent attention U-Net.

## Method and Materials

* XRA 2D Angiography
* CLAHE preprocessing 
* Multi resolution Multi (4) 0.75 1 1.25 1.5 scalar factors
* MRCF (Multi Resolution Convolution Filter) block
* Unet with MRCF blocks in the decoder

### MCRF block

input features are resampled using 4 scales
each resampled feature is processed by a 1x1 3x3 5x5 7x7 convolution kernel
all outputs are resampled to the original resolution and concatenated.

https://ars.els-cdn.com/content/image/1-s2.0-S2352914821000927-gr2.jpg

