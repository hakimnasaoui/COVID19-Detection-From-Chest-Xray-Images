# Covid-19-Detection-From-Chest-Xray-Images

## Dataset 
Kaggle Dataset Link : https://www.kaggle.com/nabeelsajid917/covid-19-x-ray-10000-images


## Model

* Simple Convolutional Neural Network model.
* Trained the whole network for 15 epochs
* Batch size set to 8
* Optimizer : RMSPROP
* Data Augmentation : The goal is to get rid of the class imbalance issues. Oversampling with data augmentation


*Through this model is almost 95% accurate but still there is a lot of work need to be done as the dataset lack of other useful information like geo-location, travel history etc to detect COVID-19. Using only X Rays images is not enough.*
