# cloud-devops-capstone
The Capstone Project of my Cloud DevOps Nanodegree with Udacity

## CircleCI Status
[![ConorMcElvogue](https://circleci.com/gh/ConorMcElvogue/udacity-devops-capstone.svg?style=svg)](https://app.circleci.com/pipelines/github/ConorMcElvogue/udacity-devops-capstone)

## Project summary and guidelines

Project Outline:
- Demonstrate several CI/CD techniques using a combination of CircleCI,Docker,Amazon EKS and Flask

Project Solution:
- Create a flask application printing "Hello, Udacity! Welcome to my Capstone project"

Project Steps (Continuous Integration):
- Linting to ensuring the code is formatted correctly for use
- Security Scanning
- Create and publish a Docker Image

Project Steps (Continuous Deployment):
- The newly created docker image is deployed to an EKS Cluster
- A service Manifest (loadbalancer) will be created as a single endpoint to access any one of the created cluster pods
- If the image already exists, a rolling update to use the new image

## Libraries / Dependencies / Requirements
- aws cli
- minikube
- docker
- kubectl
- eksctl
- hadolint
- python 3.7
- flask
- pylint
- pytest
- safety
- Amazon AWS Account
