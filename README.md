# Image-segmentation

This notebook performs image segmentation on the Berkely Segmentation Dataset, using K-means algorithm and assigns each cluster produced from K-means to a color and outputs a colored image.

This colored image is then evaluated using Conditional Entorpy and F-measure against multiple ground truth segmentaions from the dataset to measure how good the algorithm did.

We used pixel encoding according to RGB color only, and pixel encoding according to spatial features of the pixels.
