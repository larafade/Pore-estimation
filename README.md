# Pore Estimation

This code was developed to estimate porosity levels in light microscopy images using machine learning. 


Input Image | Predicted Mask
:--: | :--: 
<img src="pic5.png" alt="pic1"  width="200%"> | <img src= "pic6.png" alt="pic1" width="200%">


## Getting Started
To run this code, please follow the instructions below:


### Installation
1. Download the files in the repository

2. Run using Google Colab


### Explanation of the code
1. The first step is to crop the images to 512 x 512 px.
2. The mask of the pores was generated as .jpg usign the annotation file.
3. Afterwards the training and testing datasets are defined
4. The U-Net architecture is defines.
5. Finally, the machine learning model named model includes the training / testing datasets and U-Net architecture 


### Explanation of the files
1. Cropping.ipynb
   ```
   This code is used to crop an image of any size into 512 x 512 pixels. This is done to ensure that all the input images of the model all have the size (consequently tensor size). 
   ```
2. Code.ipynb
    ```
   This code is used to crop an image of any size into 512 x 512 pixels. This is done to ensure that all the input images of the model all have the size (consequently tensor size).
    ```
