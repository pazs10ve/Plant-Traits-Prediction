# Plant-Traits-Prediction

This notebook focuses on analyzing plant traits data and building a machine learning model to predict plant-related outcomes. The workflow involves loading the dataset, preprocessing, and training a model using PyTorch to capture relevant features of the dataset. The primary goal is to utilize plant trait features to build a model that can generalize well on unseen data and provide valuable insights into plant traits through a machine learning approach.

The model architecture leverages a simple Convolutional Neural Network (CNN) backbone with a MLP head trained on plant traits data to predict specific target outcomes. The dataset includes features such as temperature, precipitation, soil properties, and other environmental factors.

#Dataset Used
The iNaturalist dataset has been used in this project contains information about plant traits. These features represent various environmental and biological measurements, such as:

WORLDCLIM_BIO1: Annual mean temperature
WORLDCLIM_BIO12: Annual precipitation
SOIL_bdod: Soil bulk density at different depths
Other features include measures of temperature and precipitation seasonality, soil properties, and climate-related variables.
The dataset is divided into training and testing sets, with the training set used to build the model, and the test set reserved for evaluating performance.

#Training Process
The model has been trained for 100 epochs for the criterion of Mean Squared Error (MSE) with a batch size of 32, learning rate of 0.001.
