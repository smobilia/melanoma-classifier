# Melanoma Project README file

## Project Summary
This project is for the development of Melanoma Classifier for the Kaggle SIIM-ISIC Melanoma Classification Contest

## Project Goals
The primary project goal is to develop a classifier that can detect instances of Melanoma from input images.

The secondary project goal is to get more experience working with PyTorch.

## Requirements
These files were built with a Python environment using version 3.6.10.

These files require the following python packages:
tensorflow 1.9
pandas 1.0.5
numpy 1.19.1
pillow 7.2.0
pytorch 0.4.1
scikit-learn 0.23.1
matplotlib 3.2.2

The Google Chrome CurlWget extension was also used to download the into Colab.

## How to Use These Files
These files were run in Google Colab using a GPU.  The data was imported into Colab with the help of the Chrome CurlWget extension. The files were broken up into eight sections: 
1) Import Necessary Python Packages 
2) Download and Examine Data 
3) Split and Transform Data 
4) Format Data
5) Create CNN
6) Helper Functions
7) Fit the Training Data to the Network
8) Generate Test Data

Running these sections in order should reproduce the results for a particular run.

## Data and Preprocessing

## CNN Implementation

## Conclusion

### Future Work
- Incorporate early stopping into the models.
- Incorporate metadata into the models.
- Incorporate more image processing and data augmentation on the images.

## References
Thank you to Kaggle user Chris Deotte for providing the scaled jpg images that were used in these models.
[PyTorch JPEGs - 768, 512, 384, 256 - TensorFlow JPEGs](https://www.kaggle.com/c/siim-isic-melanoma-classification/discussion/164092 "Resized JPGs")

I also liked the way that Kaggle user Vishnu organized his code [here](https://www.kaggle.com/vishnus/a-simple-pytorch-starter-code-single-fold-93 "Simple PyTorch Starter"), and I based some of my pipeline layout on this code.

These PyTorch tutorials were also helpful:
- [Data Loading and Processing Tutorial](http://seba1511.net/tutorials/beginner/data_loading_tutorial.html "Data Loading and Processing Tutorial")
- [Neural Networks](http://seba1511.net/tutorials/beginner/blitz/neural_networks_tutorial.html#sphx-glr-beginner-blitz-neural-networks-tutorial-py "Neural Networks")
