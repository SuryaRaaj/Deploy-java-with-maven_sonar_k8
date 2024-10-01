# Deploy-java-with-maven_sonar_k8

This repository contains a GitHub Actions workflow that automates the CI/CD process for a Java application using Maven, SonarQube, and Kubernetes.

## Overview

- **Build Job**: Compiles the Java application and performs code analysis.
- **Deploy Job**: Deploys the application to a Kubernetes cluster.

## Technologies Used

- **Java**
- **Maven**
- **SonarQube**
- **Kubernetes**
- **GitHub Actions**

## Prerequisites

1. GitHub repository
2. SonarQube account and project
3. Access to a Kubernetes cluster

## Setup Instructions

1. **Add Secrets**:
   - `KUBECONFIG`: Your Kubernetes config.
   - `SONAR_TKN`: Your SonarQube token.

2. **Kubernetes Manifests**:
   - Place your YAML files in the `kubernetes/` directory.

3. **Update Workflow**:
   - Set your SonarQube organization, key, and name in the workflow file.

