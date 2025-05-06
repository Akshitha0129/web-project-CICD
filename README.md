# Full CI/CD Pipeline with AWS – End-to-End Web App Deployment
This project demonstrates how to build a complete CI/CD pipeline using AWS services to automatically build and deploy a web application.

<img width="1022" alt="Screenshot 2025-04-10 at 5 27 54 PM" src="https://github.com/user-attachments/assets/131e1b1c-b808-4908-99a6-f0e00843006e" />

## Architecture Overview

This solution integrates the following AWS services:

CodeArtifact – Secure storage and management of dependencies

CodeBuild – Builds your app from GitHub source using buildspec.yml

S3 – Stores application artifacts

CodeDeploy – Deploys the built app onto a web server

CloudFormation – Provisions VPC and EC2-based infrastructure

GitHub – Source control for app code and infrastructure files

## Project Structure
settings.xml – Maven settings file (for Java web app projects)

buildspec.yml – Instructions for AWS CodeBuild

appspec.yml – Instructions for AWS CodeDeploy

index.jsp – Sample application file

script/ – Custom deployment or hook scripts

## What You Will Learn
How to securely manage credentials with IAM and key pairs

Creating a CI/CD pipeline in AWS manually, without pre-built templates

Connecting GitHub to CodePipeline via CodeConnection

Automating build, artifact storage, and deployment to EC2 using CodeDeploy

Infrastructure provisioning using CloudFormation

## Full Tutorial
Read the complete step-by-step guide on Medium:
https://medium.com/@akshitha799/building-ci-cd-project-cd63b1dcfb23
