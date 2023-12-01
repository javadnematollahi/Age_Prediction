# Age prediction

In this project I want to predict your age!

## Description

Dataset Address:

https://susanqq.github.io/UTKFace/

OR

https://www.kaggle.com/datasets/jangedoo/utkface-new

Pretrained model that I use for this model:

MobileNet

There are a lot of model in tensorflow library that you can find them in below link:

https://www.tensorflow.org/api_docs/python/tf/keras/applications


## How to install

```
pip install -r requirements.txt
```

##  How to run

Run below command in terminal to create model and train data and finally print loss of validation data:

```
python load_train_age_model.py
```

Run below command in terminal to predict the age of an input picture:

```
python Age_prediction.py
```

## Results:

### loss of train and test with MAE:

 |           |       Loss     |   
 |---------: | :----------------: |
 |    Train     |        4.2915          |     
 |    Validation    |        6.0586          |    


### you can see different diagrams of model in below wandb site link:

https://wandb.ai/javad7189/Age_detection

### Result of model on two picture:
# INPUT:


![javad](https://github.com/javadnematollahi/Age_Prediction/assets/86910174/99da03df-8aa9-4a21-9bf1-6256d4f28c2d)



# OUTPUT:


![khodam](https://github.com/javadnematollahi/Age_Prediction/assets/86910174/83174945-5b2f-43c9-9cde-932970ef3d8e)



# INPUT:


![faces](https://github.com/javadnematollahi/Age_Prediction/assets/86910174/9454ab93-f5db-40c7-ba17-986a31f848dc)


# OUTPUT:


![faces](https://github.com/javadnematollahi/Age_Prediction/assets/86910174/f219df06-fe15-4844-8588-19c91e0c2f78)


