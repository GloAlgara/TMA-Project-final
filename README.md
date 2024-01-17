# TMA-Project-final
Project for the subject TMA

First, we started with one dataset (called Data) that only has IoT devices. Then, we decided to switch to another, provided by Ben-Gurion - University of The Negev (check the end of the readme for references).


## Requirements for the first dataset

oldDataset: The dataset we used to use, a csv file.
IoT predictor: The code with Extratree and Random Forest Classifier. We manually extracted the columns that we couldn't have outside the network


## Requirements for the second dataset
### In this repository we have the following final codes

Device_classifier: 3 classifiers (Bagging, Random Forest and KNN) from inside and outside the network that classifies our devices 
Device_classifier_withSampling: Same as before but we tried to see if sampling would change the results
IoT_classifier: 3 classifiers (Bagging, Random Forest and KNN) from inside and outside the network that classifies the flow to be IoT or Non-IoT
IoT_classifier_with_Sampling: Same as before but we tried to see if having sampling would change the results
deep_learning: Use of multi-class neuronal networks to classify the devices
deep_learning_iot: Use of binary neuronal networks to classify between IoT and Non-IoT
Dataset2: The dataset we used to do this project


## To run the codes:

First make sure the data is in the same folder as the codes. To run them you will need to have any visualizator (online or offline) that supports ipynb files and then execute all the cells in the code. Beware that the neuronal network ones takes about an hour each model, so a total of around 2h for each of the files (4h for all).

Group A2:
Carolina Aldana, Glòria Algara, Sebastian Andrade, Aleix Martín and Amanda Palomo

Providers of the dataset:
Meidan, Y. (Creator), Sachidananda, V. (Creator), Peng, H. (Creator), Sagron, R. (Creator), Elovici, Y. (Creator), Shabtai, A. (Creator), Meidan, Y. (Contributor), Shabtai, A. (Contributor), Elovici, Y. (Contributor) (2020). IoT-deNAT: Outbound flow-based network traffic data of IoT and non-IoT devices behind a home NAT. ZENODO. 10.5281/zenodo.3924770
