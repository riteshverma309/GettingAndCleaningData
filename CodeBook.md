---
title: "CodeBook.md"
author: "Ritesh Kumar Verma"
date: "Saturday, March 21, 2015"
output: html_document
---
##Variable Descriptions:

trainingData variable created for data in /train/X_train.txt
trainingLabel variable created for data in  /train/y_train.txt
trainingSubject  variable created for data in /train/subject_train.txt
testingData variable created for data in /test/X_test.txt
testLabel variable created for data in /test/y_test.txt 
testSubject  variable created for data in /test/subject_test.txt
joinLabel  variable created for combining  trainingLabel and testLabel
joinSubject variable created for combining  trainingSubject and testSubject
features variable created for data in /myData/features.txt
mean_Std_Indices variable created for mean and std data indexes list in features
joinData variable created to collect combined data for training and test data
activity variable created for data in /activity_labels.txt
cleanedData variable created for final clean combined dataset
result variable created for final collection of means


##Some Sample data from cleanData

subject  activity	tBodyAccMeanX	tBodyAccMeanY	tBodyAccMeanZ	tBodyAccStdX	tBodyAccStdY   ......
1        standing	0.28858451	-2.029417e-02	-1.329051e-01	-9.952786e-01	-0.983110610      ....
1         sitting	0.27843225	-1.965430e-02	-1.079703e-01	-9.943903e-01	-0.984562780    ....
1         walking	0.20356167	-3.050523e-02	-1.370951e-01	-2.469644e-01	0.298557830     .....


##some samle data from result 

subject  activity	tBodyAccMeanX	tBodyAccMeanY	tBodyAccMeanZ	tBodyAccStdX	....
1        walking	0.2773308	    -0.017383819	-0.11114810	  -0.283740259	 ......
1  walkingUpstairs	0.2554617	  -0.023953149	-0.09730200	  -0.354708025  .......
1  walkingDownstairs	0.2891883	-0.009918505	-0.10756619	0.030035338	    .......

