Chest X-rays gives images of our heart, lungs, blood vessels, airways, and bones of our chest and spine. It’s common way to diagnose disease. Generally, people have a series of chest X-rays done over time, to track whether a health problem is getting better or worse. So, in-order to solve the problem of manually classifying X-rays, we are building a model where the images are classified to Normal or Pneumonia, COVID or not.
All the jupyter notebooks are independent of each other. However, we prefer a systematic approach where we start with traditional method followed by Sift Image making techniques and then Inception neural network. So, the order is “DataMining_ImageToArray” for the basic model and its PCA analysis for both Pneumonia and COVID analysis,  “Data Mining_siftmodel1” for SIFT analysis on Pneumonia and “Data Mining_siftmodel2” for SIFT on COVID and finally “DataMining_trainedmodel1” for inception on Pneumonia and “DataMining_trainedmodel2” for COVID.

▪	The data source for Pneumonia CXRs is Kaggle.
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 
▪	The dataset consists of 3875 of pneumonia and non-pneumonia CXR images.
▪	The data source for COVID CXRs seeded from GitHub COVID-Chest X-ray-dataset. https://github.com/ieee8023/covid-chestxray-dataset 
▪	The dataset is still under development stage and it has a total of 150 images for now. We have added some of the images from Pneumonia and Normal to this dataset in order to balance the classes.
