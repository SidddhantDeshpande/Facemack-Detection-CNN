# Facemask-Detection
A project to build a model to classify masked and unmasked faces
The project aims to design a system to distinguish between masked and unmasked faces and also identify the type of the mask worn.
Here I have taken Two approaches : One using Neural Networks (CNN) and another using SVMs(Support Vector Machines)
#### Scope of this project
* The trained model will be able to easily recognize whether a person has worn a mask or not.
* It will also be able to predict the type of mask worn by the person.
* This model is capable to detect any number of human faces and check if they are wearing a mask.

#### Dataset:
###### For the SVM Approach
* The dataset used for training the model is a custom dataset consisting of 1500 images (1000 masked , 500 unmasked).
* The face is identified by a classifier called haar cascade classifier.

With that out of the way lets get started🥳

## SVM Approach:
###### So what is the SVM algorithm?
* SVM is a supervised ML algorithm.
* The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. 

![image](https://user-images.githubusercontent.com/87174561/168951787-cf719fca-4087-4b66-ba79-e59e4838d132.png)
* This best decision boundary is called a hyperplane.

#### Hyperplane: 
 There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points.


#### Support Vectors:
The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.

##### This amazing image shared by Kirk Bone on Twitter explains the steps beautifully
![image](https://user-images.githubusercontent.com/87174561/168952042-ceead972-704a-4610-9f87-dd9712183bd1.png)

Here the example of a model that classifies between cats and dogs is given

### Flowchart of the processes


![image](https://user-images.githubusercontent.com/87174561/168952179-18002dd3-7e29-42b5-9ba9-31aabf456122.png)

## CNN Approach
