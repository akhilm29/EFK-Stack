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


