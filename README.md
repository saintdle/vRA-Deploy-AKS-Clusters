# Using vRealize Automation Cloud Code Stream to Deploy Azure AKS Clusters, register endpoints with vRA and Clusters with Tanzu Mission Control

This repository contains the configurations for the following;
- Create a Code Stream Pipeline
  - Create a Azure AKS Cluster
    - Saves SSH keys to Docker Host "SharedPath" folder
  - Create AKS cluster as endpoint in both Code Stream and Cloud Assembly
  - Register AKS cluster in Tanzu Mission Control
  
Prerequisites
- vRA Cloud access
  - The pipeline can be changed easily for use with vRA on-prem
- Azure Account that can provision AKS clusters
- Docker host to be used by Code Stream
  - Ability to run the container image: [mcr.microsoft.com/azure-cli](https://mcr.microsoft.com/azure-cli)
- Tanzu Mission Control Account that can register new clusters
