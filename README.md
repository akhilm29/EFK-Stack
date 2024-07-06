## Overview

This repository contains the setup and configuration files for deploying the Elasticsearch, Fluentd, and Kibana (EFK) stack on Azure Kubernetes Service (AKS). The EFK stack is used for centralized log management, real-time log analysis, and monitoring of applications running on AKS.

## Prerequisites

Before deploying the EFK stack, ensure you have the following:
- Azure account
- AKS cluster
- Azure CLI installed
- Kubectl CLI installed
- Helm CLI installed

## Architecture

The EFK stack consists of the following components:

- **Elasticsearch**: Stores and indexes log data.
- **Fluentd**: Collects and forwards logs from AKS pods to Elasticsearch.
- **Kibana**: Visualizes log data stored in Elasticsearch.


![image](https://github.com/darksaber8888/efkstack/assets/165632097/8b0c155f-3dcd-4f48-a1ee-b655ee4ecd3e)


![image](https://github.com/darksaber8888/efkstack/assets/165632097/7b4f5f86-a152-4ef3-b49e-b7a78ed33a81)



