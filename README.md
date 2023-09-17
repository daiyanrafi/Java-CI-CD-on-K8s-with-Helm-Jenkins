# Kubernetes CI/CD with Helm Jenkins and SonarQube for Java Apps

## Overview

This project demonstrates a complete CI/CD (Continuous Integration/Continuous Deployment) pipeline for Java applications on a Kubernetes cluster. It integrates popular tools such as Helm, Jenkins, and SonarQube to automate the build, test, and deployment processes.

## Features

- Automatic build and deployment of Java applications.
- Kubernetes Helm charts for application packaging.
- Jenkins for CI/CD pipeline orchestration.
- SonarQube for code quality analysis.
- Kubernetes for scalable and containerized application deployments.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Kubernetes cluster up and running.
- Helm installed on your Kubernetes cluster.
- Jenkins server deployed and accessible.
- SonarQube server for code analysis.
- Java development environment.

## Project Structure

This repository is organized with the following directories and key files:

- **.idea**: Directory containing JetBrains IDE settings (e.g., for IntelliJ IDEA).
- **helm**: Directory for Helm charts and Kubernetes manifests.
- **kubernetes**: Directory for Kubernetes-related configuration files.
- **src**: Directory containing the Java source code for the project.
- **target**: Directory where compiled Java classes and JAR files are stored.
- **Dockerfile**: Configuration file for building Docker containers (if applicable).
- **Jenkinsfile**: Configuration file for defining Jenkins pipeline stages.
- **k8s.iml**: IntelliJ IDEA project file (can be ignored if not using IntelliJ IDEA).
- **pom.xml**: Maven build configuration file for the Java project.
- **README.md**: This README file, providing an overview of the project.

You can explore and modify the contents of these directories and files according to your project's requirements.

