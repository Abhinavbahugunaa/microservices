
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
- `jenkin_shared_lib/`: Includes automation scripts for various tasks.
- `deploymentservice.yml/`: Holds Kubernetes deployment configurations.
- `jenkinsfile`: Defines the Jenkins pipeline stages.
- `README.md`: You're reading it!

## Getting Started

1. Clone this repository :

   ```bash
   git clone https://github.com/abhinavbahugunaa/demo-devops-microservice.git
   cd demo-devops-microservice
   
 2. Build the Microservice : Navigate to the project directory and build the microservice using Maven.

    ```bash
    cd microservice
    mvn clean install

3. Run Unit Tests: Execute unit tests to ensure the microservice's functionality.

   ```bash
   mvn test
   
4. Integration: Integrate the microservice with other components as needed.

5. Code Quality Analysis: Analyze the code quality using SonarQube.

6. Containerization: Build a Docker image of the microservice.

   ```bash
   docker build -t my-microservice:latest
   
7. Image Scanning: Scan the Docker image using Trivy for vulnerabilities.

8. Kubernetes Deployment: Deploy the microservice on a Kubernetes cluster using Helm charts.

9. Monitoring Setup: Set up monitoring using Grafana and Prometheus.

10. Jenkins Pipeline: The entire process can be automated using the Jenkins pipeline provided in the repository. Configure the pipeline in your Jenkins environment and trigger it.

## Pipeline Steps

The CI/CD pipeline for this project orchestrates the end-to-end process of building, testing, deploying, and monitoring the microservices application. Below are the main steps of the pipeline:

1. **Build Microservice**: Use Maven to build the microservice and create a deployable artifact.

2. **Run Unit Tests**: Validate microservice functionality with unit tests.

3. **Integration**: Integrate the microservice with other components of the application.

4. **Code Quality**: Analyze code quality using SonarQube for bugs, vulnerabilities, and maintainability.

5. **Build Docker Image**: Package the microservice as a Docker image.

6. **Security Scan**: Scan the Docker image for vulnerabilities using Trivy.

7. **Deploy to Kubernetes**: Deploy the microservice to Kubernetes using Helm charts.

8. **Monitoring Setup**: Set up monitoring with Grafana and Prometheus.

Each step ensures a seamless build, testing, security, deployment, and monitoring process.


## Monitoring

The monitoring setup involves using Grafana and Prometheus. You can access the Grafana dashboard to monitor the health and performance of the deployed microservice. Prometheus collects and stores metrics that Grafana uses to create visualizations.





