# Waste-Detection-and-segregation
Created By:- Jayant Narayan
Thapar Institute of Engineering and technology

The Purpose of the project is to design an effective way to detect and segregate biodegradable waste from non-biodegradable waste in water bodies. For this, have considered multiple dataset and combined to form a dataset that increases model accuracy for water bodies.

train data consisting of 6720 images and 2058 validation data having images. This helped in randomizing the size of training and testing datasets. Since the dataset contained 7 classes of waste it had to be recategorised into 2 classes (Biodegradable and Non-Biodegradable).

After preprocessing and feature extraction from the images, implemented image classification algorithm in our case Res-net came out with maximum accuracy(93.07%).

For compilation, have used adam optimizer with learning rate of 0.001 and performance metrics as accuracy and cross entropy for minimizing data loss.

