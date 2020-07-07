# Udacity-DevOps-Capstone
Steps in Completing Your Project
## Step 1: Scope of the Project
### Pipeline 1:
* Start
* Create kubernetes cluster
* Configure services for cluster
* End

### Pipeline 2:
* Start
* Lint HTML
* Build Docker Image
* Push Image To Dockerhub
* Set current kubectl context
* Deploy blue container
* Deploy green container
* Create the service in the blue cluster
* Wait user approve
* Create the service in the green cluster
* End

### Deployment type:
Blue/Green deployment.

For the Docker application used an Nginx "Hello World" application.

## Step 2: Use Jenkins, and implement blue/green or rolling deployment.
Created Jenkins master box with either Jenkins and install the plugins needed.

### Set up the environment to deploy code:
* Jenkins
* Blue Ocean Plugin in Jenkins
* Pipeline-AWS Plugin in Jenkins
* Docker
* Pip
* AWS Cli
* Eksctl
* Kubectl

### Step 3: Build a Kubernetes cluster.
Use EKS to setup the Kubernetes cluster.

### Step 4: Build and test the pipeline
![pipeline](Screenshots/screen%20(15).png?raw=true)