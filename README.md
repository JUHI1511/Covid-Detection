# Covid-19-detection-with-chest-scan
In this project, we have applied deep learning for COVID-19 detection. We have applied four different deep learning models: CNN model, CNN model with regularization, CNN model with Image augmentation and Transfer learning model(VGG16) with image augmentation.Out of which I got best accuracy with vgg16 as 97%

* Dataset of chest X-ray is downloaded from Kaggle.com and it is visualised for the proper understanding of the data before processing. Data augmentation is applied on the images so that it can effectively classify the covid-19 cases.
* CNN is proposed for the detection of covid-19 and hence controls the fast spreading covid-19 cases.
* Pre trained deep learning model that is transfer learning algorithm VGG-16 is used to increase the accuracy of the proposed mode

COVID-19 Chest X-ray radiography images databases from the Kaggle repository (https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) are taken. The dataset consists of Chest X-ray images for COVID-19 positive cases patients 2295 patients with 1583 normal images and 712 covid images. Out of these, 1811 chest x-ray images are used for training (1266 Normal/545 COVID) and 484 images are used for testing (317 Normal/167 COVID).

Our results showed that the basic CNN model has overfitting based on training/validation accuracy/losses. We also noticed overfitting had been slightly reduced in the CNN model with regularization. For image augmentation with our CNN model, we observed that overfitting had been dramatically reduced. We noticed that their results are pretty similar to our CNN model with the image augmentation method for transfer learning.!
### Dataset Images
![Dataset Images](https://user-images.githubusercontent.com/71288590/133456389-d87e0d47-a654-445a-a75e-8575936df507.png)


# CNN MODEL
### CNN ACCURACY CURVE
![download (1)](https://user-images.githubusercontent.com/71288590/133457935-bcfa1532-d046-4fff-841c-083281c70174.png)
![download](https://user-images.githubusercontent.com/71288590/133458012-e5c4357d-a255-4530-a843-5948da165165.png)

### CNN Confusion Matrics

## Future Works

Transfer learning will be used for feature extraction, and the output of corresponding transfer learning will be feed to our CNN model
Freezing only some of the network layers of transfer learning and fine-tuning the remaining network layers of transfer learning along with our CNN model.
The aim is to help medical practitioners helping us in battle against COVID-19 by easing the task of manual testing using Deep Learing.

Problem type :- Supervised
Algorithms used :- CNN and Transfer Learning(VGG16)
Dataset:https://github.com/dakshtrehan/Covid-19-Detection
Libraries used :- Keras, Numpy, Seaborn, Matplotlib, os
Inspired by :- https://www.youtube.com/watch?v=nHQDDAAzIsI
