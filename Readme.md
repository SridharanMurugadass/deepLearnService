# Machine Learning Image Recognition 


 for the impatient ones wanting to have a web service for image recognition by using Tensorflow prerequisites: run ```./gradlew fetchInceptionFrozenModel bootrun```, navigate to http://localhost:8080 and upload an image. The backend will categorize the image and output the result along with the probability.


## Why
Tensorflow is hard enough to wrap one's head around. It has several parts that deal with preparing data, defining and training a model and finally, outputting a model that can then be used to categorize (infer) other data. There's math involved, new vocabulary to learn and on top, a toolchain which revolves around Python.
This project only addresses serving a Tensorflow pre-trained image categorization model, otherwise called the Inception model.  

## Prerequisites
- JDK 8

## Run
```./gradlew fetchInceptionFrozenModel bootrun```

Navigate to http://localhost:8080 and upload an image. The backend will categorize the image and output the result along with the probability.


## Developed By
Sridharan Murugadass
Chennai
sridharanbe.ece@hotmail.com