# Machine Learning

## Introduction
From a report from the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver.
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
3. Then in the data section of the question, we will click the 'download all' tab to download all the data. After that when it asks for a place to download, we will cancel it and will go curlwget extension
and will copy the link that will be geneated in wget dialog box.
4. We will paste this link with a exclamation mark sign ! at the start and will run this.


## Step of Execution
1. Download the project by clicking [this link](https://github.com/JyotsnaVerma19/CSC8631_EDA_DM) and place all the data files in ./data/ directory or  unzip the project folder attached.
* If downloading from Git, make data and cache directory in the project folder.
2. Open RStudio
3. Set working directory by using the command setwd("path/where/you/downloaded/the/project/file") or you can simply click on sessions tab present in the top menu bar then go to set working directory then choose directory (Session > Set Working Directory > Choose directory).
Open ./reports/Reports.rmd and run all the chunks by clicking on Run > Run All button in Rstudio.
To generate the pdf report click on knit or knit to pdf.

## Accessing Structured Abstract Report
Go to ./reports/ folder and find the Critical_Reflection_Report.pdf

## Note : 
This project runs fine on Windows operating system. (Haven't checked on other OS)