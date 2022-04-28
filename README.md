# Datascience888
This repository is for Data Science work and assignments. 


Prediction on used car has gain a lot of attention in recent year. With the growing standard of living of people many relays on second hand cars. But that’s where the used cars prices cost varies a lot. Sometimes dealers take advantage and increase the prices of second-hand cars. It makes difficult for people to make a better decision while buying used cars.
To make a better prediction using the current market prices of used cars, we must understand our dataset well. Different factors, like mileage, make, model, year, etc can influence the real worth of a car. For this project the aim is to used machine learning technique to make a better prediction for used car prices.

With the growing techniques of Data mining, big data and machine learning everyday, we have seen datasets keep increasing in sizes too. This brings the challenge of imbalanced data which effects the accuracy of prediction. In this project we worked on three imbalanced datasets of used cars. These real-life problems motivate us to study the insight of bigdata, challenges to deal with imbalanced datasets, selecting best model for our project and improving the prediction values. 

The three datasets of used cars are picked from Kaggle and datahub, which are one of the great websites to download free datasets. The dataset contains the records of used car which are created in year 1990-2022. The cars are of different models and have different mileage covered. Another thing observed in these datasets is that humans have make a lot of mistakes while entering their car records online, sometime adding high prices or sometimes leaving the price column empty. In other words, ambiguity is sometimes high. Currently the imbalance rate of these datasets is low but after making them imbalanced, we can work on the real-life problem of car sales dataset more well.

The problem like imbalanced subclass can’t always be solved with removal of some data or adding extra data. In many cases each record and its quantity is important for making better prediction. Classifying imbalanced data is a problem that rises while dealing with different types of imbalanced data in machine learning. [01] has used data mining and pattern classification methods to overcome imbalance. In [02] the author has worked on class imbalanced dataset of in-hospital mortality prediction. The used an algorithm called Balanced Random Forest (BRF) and tune his hyper parameters for better performance. Meng Xu from Beijing University of Technology proposes a novel data augmentation method known as BWGAN-GP [03], Balanced Wasserstein generative adversarial network. It generates RSVP minority class data. 



To train a model on our dataset we came across three different techniques, which are Lightgbm, XGBoost and Random Forest Table 1. Lightgbm is one of the highly efficient gradient boosting algorithms. XGBoost is selected for this project because it handles missing values efficiently and contains verity of parameters to tune. Random forest is a easy to use and flexible algorithm. It is selected for this project because it can handle big datasets efficiently and gives good prediction results. It also provides higher level of accuracy. Some advantages of three selected models are given below:



Decision tree	XGBoost	Random Forest
•	Fast training speed
•	Simple to understand
•	Better accuracy
•	Cost depends of number of data points used to train the tree.
•	Support GPU
•	Easy parameter tuning	•	Handle missing data
•	Provide intuitive features
•	Easy hyper-parameter tuning
•	Regularization: which prevent overfitting
•	Parallel processing
•	Cross validation	•	High accuracy
•	Handle missing values
•	Handle big data with numerous variables. 
•	Automatically balance datasets when classes are more infrequent than other classes.
Table 1: Advantages of selected models for this project
![image](https://user-images.githubusercontent.com/98464484/165731013-f1467b0f-2bfd-436f-b3ff-a1f46b36943c.png)


## Datasets

The three selected dataset contains information about used car on sale. 

1) UsedCarData.csv:

Columns:	 
Rows:
 
 
2) Car details from car dekho.csv:

Columns:	 09
Rows	 301
Year	 1992 - 2020
Memory usage	 21.3+ KB
	

3) Car sales csv:

Columns:	16
Rows	157

	
