Local Kubernetes Cluster using Minikube

This project demonstrates the deployment of an Employee Management System using Kubernetes, Docker, and GitHub Actions for automated CI/CD. This setup is aimed at understanding how Kubernetes can be used in local development environments with Minikube to manage containerized applications effectively.

Features
Local Kubernetes Setup with Minikube
Containerization with Docker
Continuous Integration and Deployment with GitHub Actions
Kubernetes Dashboard for Cluster Management
Scalable and Resilient Application Deployment

Prerequisites
Docker
Minikube
kubectl
GitHub account
Any IDE (e.g., VSCode)

Installation and Setup
Step 1: Install Prerequisites
Ensure Docker, Minikube, and kubectl are installed on your machine. Here are the installation guides:

Docker: Install Docker
Minikube: Install Minikube
kubectl: Install kubectl
Step 2: Clone the Repository
Clone this repository to your local machine:
git clone https://github.com/sanskrutikhedkar9/HomeKube-Local-Kubernetes-Cluster-using-Minikube

Step 3: Start Minikube
Start your Minikube environment:
minikube start

Step 4: Deploy to Kubernetes
Deploy the application using kubectl:
kubectl apply -f kubernetes/

Step 5: Access the Application
Find out the IP address and exposed port of your service:
minikube service list
Access the application in a web browser using the provided IP and port.

CI/CD using GitHub Actions
This project uses GitHub Actions for Continuous Integration and Continuous Deployment. The workflows are defined in the .github/workflows directory. They handle automated testing, building Docker images, and deploying to Kubernetes.

Accessing Kubernetes Dashboard
To access the Kubernetes Dashboard and manage workloads visually:
minikube dashboard

Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
