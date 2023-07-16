# Canary deployment process on Kubernetes

## Prerequisites

#### Step1
Clone this repo
#### Step 2
Setup minikube locally and mount the github folder as local storage class
#### Step 3
Create two images for Blue and Red from base image of nginx using [Kaniko](https://github.com/GoogleContainerTools/kaniko)

## Setup 

#### Step 1
Setup blue pod
#### Step 2
Setup blue service
#### Step 3
Setup ingress and expose blue service via ingress endpoint
#### Step 4
Setup red pod and service
#### Step 5
Setup canary deployment via ingress