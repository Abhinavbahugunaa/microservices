
# Demo DevOps Microservice Project

Welcome to the Demo DevOps Microservice Project! This project showcases the complete implementation of a basic microservices application using a variety of DevOps practices and tools. The pipeline is orchestrated using Jenkins.

## Tools and Technologies Used

This project utilizes the following tools and technologies:

- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/) ([kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/), [kubectl](https://kubernetes.io/docs/reference/kubectl/overview/), [kubelet setup](https://kubernetes.io/docs/setup/production-environment/tools/kubelet/))
- [Helm](https://helm.sh/)
- [Jenkins](https://www.jenkins.io/)
- [SonarQube](https://www.sonarqube.org/)
- [Trivy](https://github.com/aquasecurity/trivy)
- [Grafana](https://grafana.com/)

## Project Structure

The repository is organized as follows:

- `microservices/`: Contains the source code for the microservices.
- `scripts/`: Includes automation scripts for various tasks.
- `deployment/`: Holds Kubernetes deployment configurations.
- `Jenkinsfile`: Defines the Jenkins pipeline stages.
- `README.md`: You're reading it!

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/abhinavbahugunaa/demo-devops-microservice.git
   cd demo-devops-microservice
   
 2. Build the Microservice: Navigate to the project directory and build the microservice using Maven.

