# RieszNetworks

## Code from paper:
Barisin, T., Schladitz, K., & Redenbach, C. (2023). Riesz networks: scale invariant neural networks in a single forward pass. 
https://arxiv.org/pdf/2305.04665.pdf

### PhD thesis: 
Barisin, T. (2023). Methods for scale and orientation invariant analysis of lower dimensional structures in 3d images (Doctoral dissertation, Rheinland-Pfälzische Technische Universität Kaiserslautern-Landau).
https://doi.org/10.26204/KLUEDO/7408


## Notebooks with short descriptions:

- ### RieszNet-MNIST 
  (version: 14.12.2023)
  
  RieszNet applied to classic MNIST dataset: training + testing
  
  Test accuracy (after 20 epochs): 98.78%
  
  Number of parameters: 20,882


- ### RieszNet-MNISTLargeScale
  (version: 16.12.2023)

  RieszNet applied to classic MNIST LargeScale dataset: training (on scale 1) + testing (on scales 0.5-8)

  Example model is trained on 5000 images for 20 epochs.
  Test accuracies on selected scales: 88.31% (scale 0.5), 94.75% (scale 1), 94.47% (scale 2),  92.12% (scale 4), 55.87% (scale 8).
  
  For accuracies on the full dataset check the paper:  96.34% (scale 0.5), 98.58% (scale 1), 98.39% (scale 2),  96.42% (scale 4), 51.82% (scale 8).


- ### RieszNet-crack-segmentation-2d
  (version: 18.12.2023)

  RieszNet for crack segmentation of cracks on 2d slices cropped from CT images of concrete: remake of the model from the paper.

  ###### Testing scale generalization:
  Trained on crack width 3. Tested on variety of simulated and real cracks of various widths. 

- ### RieszNet-crack-segmentation-3d
  (version 20.12.2023)

 RieszNet for crack segmentation of cracks on 3d CT images of concrete: remake of the model from the thesis with some examples.
 Model was trained on crack width 3.  

