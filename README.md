
# Project Title:- Face Recognition and Drowsiness Detection
![image](https://user-images.githubusercontent.com/93859458/165930218-bd539816-332a-41e2-840b-d8f4bd3f59b3.png)
## Description
 when we started working on a drowsiness detection system. Our first step in project was to gather the information about drowsiness detection and ways to detect drowsiness. Deep learning helped us tackle the problem by using the CNN model. As we started working we started gathering eye images from the MRL data set. These images are in low and high resolution, all captured in various lighting conditions and by different devices.After importing dataset we Splitted the whole dataset in two folders as closed_eyes and open_eyes further we we changed the shape of all the images we had 86-86pixels to 224-224pixels.then further we assigned all the features in X variable and all the labels in Y variable. then we normalized the X-variable by dividing it 255 so we can scale down it to 0-1 values further we moved to model training where we used mobile net as our algorithm with adam optimiser and sigmoid function which us lowest as accuracy 57% and highest accuracy as 88% we used model with high accuracy for prediction. By feeding external images we predicted the eye's condition whether it is opened and closed. Our model gave us a positive value that means our image was an open eye image. In last step by using open cv we started capturing image and with the use of haar cascade file detected the shape of face and eyes and after preprocessing image our model predicted us the values positive and negative for opend_eyes and Closed_eyes


## Table of Content
* Description
* Dataset Information
* Tools and Libraries Used
* Files
* Results
* Feedback


## Dataset Informatio
the large-scale dataset of human eye images. This dataset contains infrared images in low and high resolution, all captured in various lightning conditions and by different devices. The dataset is suitable for testing several features or trainable classifiers.
Dataset :
Every Emage in dateset is numbered as S0012_03054_0_1_0_2_1_01 where as

* in the dataset, we collected the data of 37 different persons (33 men and 4 women)

* image ID; the dataset consists of 84,898 images

* gender [0 - man, 1 - woman]; the dataset contains the information about gender for each image (man, woman)

* glasses [0 - no, 1 - yes]; the information if the eye image contains glasses is also provided for each image (with and without the glasses)

* eye state [0 - closed, 1 - open]; this property contains the information about two eye states (open, close)

* eflections [0 - none, 1 - small, 2 - big]; we annotated three reflection

* states based on the size of reflections (none, small, and big reflections)

* lighting conditions [0 - bad, 1 - good]; each image has two states (bad, good) based on the amount of light during capturing the videos

![image](https://user-images.githubusercontent.com/93859458/165928503-b58bb074-d80e-40db-8f49-482fd11bb4db.png)



## Tools and Libraries Used
* Pandas
* numpy
* Matplotlib
* tensorflow 
* openCV
* OS
* Keras



## Files
* This repository contains files as mentioned below
* Face Recognition and Drowsiness Detection.ipynb: Google colab contains all the python code, documentation and visualization
* MRL Dataset.csv: dataset 
* Summary-Face-Recognition-and-Drowsiness-Detection



## Results
### MObile Net Accuracy
![image](https://user-images.githubusercontent.com/93859458/165929007-1f732111-a153-453f-bb21-d47469693d3f.png))



## Feedback

If you have any feedback, please reach out to us at samarthgangurde01.com

