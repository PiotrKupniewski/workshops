# DevOps: Deploying Microservices to OKE with Jenkins Pipelines (CI/CD) #

## Introduction

In this workshop, we will focus on a popular CI/CD tool called Jenkins and how it can be used for continuous delivery on OKE. Jenkins is an extensible automation server that can be used as a simple CI server or turned into the continuous delivery hub for any project. 

This labs are design for people with or with no experience on cloud native technologies like Jenkins, Docker and Kubernetes. In this workshops you will work with thess tools plus frameworks like ReatJS and Springboot.

In this workshop, you will deploy four microservices on to OKE: 

+ **Jenkins Server**
+ **Frontend app** running on ReactJS
+ **Backend app (API)** running on Springboot (Java)
+ **Mysql Server** 

## Prerequisites ##

For this workshop you require and oracle cloud Account. You may request a trial account [here](https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=_ref_coc-asset-opcHome) or if you are in an event an account maybe provided.

You will also need a **Github** account.

For software on your laptop you will require:

+ Github client - you can download [here](https://git-scm.com/downloads).
+ Visual Code (or IDE of your choice) - you can download [here](https://code.visualstudio.com/)


## Steps to follow ##

1. Creating a Kubernetes Cluster on Oracle Cloud Infrastructure
    - Please note that if are using a instructor provided environment you might already have a cluster and you need to skip this step
    - If you want to create your own cluster you can create using the Quick create option. [Here](https://www.oracle.com/webfolder/technetwork/tutorials/obe/oci/oke-full/index.html) are the instructions

2. Create Jenkin Instance in your kubernetes instances
3. Create Mysql Server in you kubernetes instances
4. Create your Jenkins pipelines