# Classifier-task-

## Installation python packages

Use the package manager pip to install Required Packages.
```python
pip install pandas
pip install joblib
pip install flask
```
Machine Learning Library for Accuracy and classification_report.
```python
pip install scikit-learn
```
## Docker Installation, docker hub and Postman

- [Docker Setup](https://afourtech.com/guide-docker-commands-examples)  
- [Docker Hub](https://hub.docker.com/)  
- [postman](https://www.postman.com/) 

## Deployment Explanation 
## Step1:
In Dockerfile you will get the necessry commands to execute model in docker, just create the docker file
dont provide any extension and and follow the commands as given in the Dockerfile. 
## Step2:
Open the postman and used  API for testing the result of the prediction, take the data from request.txt 
file to send request through postmam.

## About project Files 
In Deploy and Notebook folder there is whole code about the project and deployment.
there are two .pkl files, those are model which ceated for the respected model and scalar model as 
mymodel.kl and scale.pkl respectively.

## Docker Image

```shell
docker pull falex55/breast_cancer:latest
```



