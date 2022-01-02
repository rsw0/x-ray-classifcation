# x-ray-classifcation

This project seeks to classify a given X-Ray image into one of the following four categories: normal, COVID-19, Pneumonia-Bacterial, and Pneumonia-Viral.

Transfer learning was used to construct the models. Two base models (VGG16 and ResNet) were compared and tuned. The lowest testing loss (0.48077499866485596) was achieved by ResNet, and the testing accuracy for ResNet was 0.7777777910232544. The T-SNE plot for ResNet shows a clear separation among the classes.

The folder "all" contains training and testing data. All codes are included in the Jupyter notebook file. Class project for CS440 at Boston University

