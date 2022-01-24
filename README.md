# PLANT LEAF DISEASE DETECTION USING DEEP LEARNING 
**Deep learning using tensorflow on image dataset containing different healthy and unhealthy Pepper bell.** 

## Dataset
The dataset for this project can be downloaded from: https://drive.google.com/drive/folders/14GveDqfn8xRGfKuw2h4QuKFOHOaLDJu2?usp=sharing


This dataset consists of 55,00 images of leaves 2 classes. All images target size are 200*200 in resolution.

The dataset is divided into three parts as follows:

- **Training** - 2475 images divided into two classes with 997 to 1,478 images per class.
- **Validing** - 2475 images divided into two classes with 997 to 1,478 images per class.
- **Testing** - 550 images (These images are not divided into their respective classes but the class can be inferred from the image filename)

## Project Requirements
The external libraries required for running _**Train.ipynb**_ are:
1. numpy
2. pandas
3. matplotlib
4. sklearn/scikit-learn
5. tensorflow (Version 2.3.0 or higher preferred)

## Model
The model used is a deep Convolutional Neural Network and was created using tensorflow.keras Functional API.

The different layers used in this model are as follows:
- Input 
- Depthwise Convolution 2D
- Convolution 2D
- Max Pooling 2D
- Dense
