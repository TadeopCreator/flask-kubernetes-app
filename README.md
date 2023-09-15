# Flask Kubernetes App

This is a simple Flask application that serves a message on the root page. This project is part of a larger GitOps setup, and it demonstrates a basic web service that can be deployed using Jenkins and ArgoCD.

Check the [medium article](https://medium.com/@tadeop/continuous-deployment-with-jenkins-gitops-and-minikube-deploying-a-flask-app-to-kubernetes-664beeaa82b0) that provides an overview of the project, its structure, and how to set it up.

## Table of Contents

- [Project Overview](#project-overview)
- [License](#license)

## Project Overview

This project hosts a minimal Flask application that demonstrates a basic web service. It's designed to be a starting point for those interested in deploying a Flask application on Kubernetes using Jenkins for continuous integration and GitOps with ArgoCD for continuous deployment.

The deployment settings, including the container image, are defined in the [kubernetesmanifest-flask-app repository](https://github.com/TadeopCreator/kubernetesmanifest-flask-app), where you can find the `deployment.yaml` file.

For a detailed step-by-step guide on setting up and configuring this project, please refer to the [comprehensive Medium article](https://medium.com/p/664beeaa82b0/edit).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
