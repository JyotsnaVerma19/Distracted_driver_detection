# Machine Learning

## Introduction
From a report by the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver.
This has just become like drunken driving. Almost 425,000 people injured and 3,000 people killed by distracted driving every year.
This project is about building a model for a multi class classification, so that drivers can be categorised and predicted on the basis of their behaviour.
The 10 classes to be predicted are:
c0: safe driving
c1: texting - right
c2: talking on the phone - right
c3: texting - left
c4: talking on the phone - left
c5: operating the radio
c6: drinking
c7: reaching behind
c8: hair and makeup
c9: talking to passenger

## Objective

We are aiming to improve the alarming statistics caused by the distracted driving, by testing whether dashboard cameras can automatically detect drivers engaging in distracted behaviors.
State Farm insurance company has given us a dataset of 2D dashboard camera images, and we need to develop an algorithm to detect and classify driver's behaviour and check if they are driving attentively or not.
We will be implementing deep learning arhitecture to create models and predict and classify them by training them on the given datset.

## Loading the data
1. Downloading the data from kaggle into colab using curlwget web extension for faster downloads and uploads
2. First we will go to kaggle state farm competition page. The link : https://www.kaggle.com/c/state-farm-distracted-driver-detection/data
3. Then in the data section of the problem statement we will click the 'download all' tab to download all the data. After that when it asks for a place to download, we will cancel it and will go curlwget extension
and will copy the link that will be geneated in wget dialog box.
4. We will paste this link with a exclamation mark sign ! at the start and will run this.


## Step of Execution
1. Download the project by clicking [this link](https://github.com/JyotsnaVerma19/Distracted_driver_detection) and place all the data files in ./data/ directory or  unzip the project folder attached.
2. Open jupyter notebook in project directory or open the ipython notebook in google colab and load the data by the steps mentioned in section "Loading the data".
3. And click run all under Runtime section on the navigation bar (the run time might be long as the training of the model takes time). 

## Loading data for predicting test images
1. We will create a folder in the ./imgs directory and we will create one more sub directory in that folder and we will place all the test images in that folder and give that path to image data generator.
For ex- ./imgs/test_imgs/pred_imgs, image data generator will take directory as ./imgs/test_imgs and glob command will look something like this : imgs_path = glob.iglob('/content/imgs/test_imgs/pred_imgs/*.jpg')

## Reports
1. STRUCTURED_ABSTRACT_CSC8635.pdf : This is the structured abstract file containing context, objective, method, results, novelty and key images.

## Note : 
This project runs fine on Windows operating system. (Haven't checked on other OS)