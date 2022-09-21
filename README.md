# SA-RoadScenes
Saudi Arabia's road scenes dataset for semantic segmentation.
This dataset is part of my master thesis work.

# Description
A small dataset contains 100 images captured in various cities in Saudi Arabia (SA), including Alahsa, Jeddah, Makkah, Riyadh, and Jubail Industrial city, during different daytime. Each image has a different size. 

The images are annotated into six regions of interest: 

- building
- car
- sign
- street
- sky represented as background
- unlabelled pixels

All images have their corresponding masks (binary masks), as 8bit multipage tiff files.

However, to address the dataset limitations, data augmentation techniques based on image manipulation (Cropping + Resizing + Horizontal flipping) are applied and the size of images is modified to be 128 × 128 pixels. The total number of images after augmentation is 980 images.

# Citation
If you use this dataset in your work, please cite this repository.
