# Automating Big Data Processing with Docker, GKE, and Cloud Functions on Google Cloud Platform

## Objective
The objective of this project is to automate and deploy a dataflow service as a microservice template using Docker, Google Kubernetes Engine (GKE), and Google Cloud Functions. This involves creating a scalable architecture for running data processing tasks, deploying microservices using Docker containers, and automating processes with Cloud Functions.

## Tools
- Language: Python3
- Libraries: FastAPI
- Services: Cloud Storage, Dataflow, Apache Beam, BigQuery, G-Cloud SDK, Google Kubernetes Engine, Google Container Registry, Google Cloud Functions, kubectl, Docker

## Implementation

- **Ran Dataflow Template and Created Microservice:**
  - Executed a Dataflow template for data processing tasks.
  - Developed a microservice to execute the Dataflow job using the template, ensuring seamless integration into the existing architecture.

- **Understood and Installed Docker, Created Docker Image:**
  - Gained understanding of Docker containerization technology.
  - Installed Docker on the local machine or server environment.
  - Created a Dockerfile to define the specifications for building the Docker image.
  - Built the Docker image for the microservice, including all necessary dependencies and configurations.

- **Overviewed Kubernetes and Configured GKE for Container Orchestration:**
  - Studied Kubernetes for container orchestration and management.
  - Configured Google Kubernetes Engine (GKE) for deploying and managing containers at scale.
  - Explored Kubernetes concepts such as pods, deployments, services, and namespaces.

- **Pushed Docker Image to Google Container Registry:**
  - Pushed the Docker image of the microservice to Google Container Registry (GCR).
  - Ensured proper authentication and permissions for accessing the GCR repository.

- **Created a GKE Cluster, Defined Deployment, and Service Configurations:**
  - Created a GKE cluster to host the microservice and other containerized applications.
  - Defined deployment configurations such as container specifications, replicas, and environment variables.
  - Configured service configurations for accessing the microservice externally, including load balancing and networking settings.

- **Deployed the Microservice in GKE Cluster and Ensured Its Functionality:**
  - Deployed the Docker image of the microservice to the GKE cluster using Kubernetes deployment manifests.
  - Monitored the deployment process and ensured successful deployment without errors.
  - Tested the functionality of the microservice in the GKE environment to verify proper execution and integration with other components.


## Key Learnings and Outcomes
- Understanding of containerization with Docker and container orchestration with Kubernetes.
- Hands-on experience in deploying microservices using Docker and GKE.
- Familiarity with automating processes using Google Cloud Functions.
- Ability to create scalable architectures for running data processing tasks in a cloud environment.
