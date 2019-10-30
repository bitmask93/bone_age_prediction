# Objective:
  To predict the age of people based on the X-ray images of their palms.

## Dataset : 

Dataset is part of RSNA(The Radiological Society of North America) challenge to predict the age from X-ray images. This dataset is also 
available on [Kaggle](https://www.kaggle.com/kmader/rsna-bone-age)

## Models Used :

Used Transfer Learning by using models such as Inception Networks and Densenet.

## Model Evaluation :

For predicting the gender, Accuracy was used and for predicting the Age MAE(Mean Absolute Error) is used as a metric.

## Conclusions :

Some of the conclusions of the experiment are :
  1) It is difficult to predict the gender from X-ray images, the models performed very poorly for this task.
  
  2) Using some preprocessing on the images to enhance the joints in the bones helped to reduce the Mean Absolute Error,
  So it's clear that joints play an important role in predicting the age of a person.
  

