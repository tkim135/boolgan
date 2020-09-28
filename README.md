This repository involves my design of a Computer Vision / Deep Learning framework,
whereby the computer takes in a dataset of car images and uses artificial 
intelligence to generate new car images.

We improve upon the commonly used DCGAN architecture by implementing 
Wasserstein loss to decrease mode collapse and introducing dropout at the end of 
the discrimiantor to introduce stochasticity. Furthermore, we introduce convolutional 
layers at the end of the generator to improve expressiveness and smooth noise. All 
of these improvements upon the DCGAN architecture comprise our proposal of the novel 
BoolGAN architecture, which is able to decrease the FID from 195.922 (baseline) to 165.966.

- 0607_boolgan.ipynb: An IPython notebook where the Python code and its outputs are in the same place.
- 0607_boolgan.pdf: A PDF version of the 0607_boolgan.ipynb in case the file will not open.
- BoolGAN_paper.pdf: A paper explaining my model; has been posted to arxiv.org
