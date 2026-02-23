# AWS-Resource-Cleanup-Guide

* Delete deployment - ```kubectl delete deployment flask-app```
* Delete service - ```kubectl delete service flask-app-service```
* Delete ```.env``` var - ```kubectl delete secret capstone-secret```
* Delete EKS Cluster - ```eksctl delete cluster --name flask-app-cluster --region us-east-1```
* Verify Cluster Deletion - ```eksctl get cluster --region us-east-1```
* Delete artifacts of ECR and S3 (optional - delete ECR and S3)
* Validate if ```CloudFormation``` stacks are deleted.
* Confirm service termination on AWS support chat.
