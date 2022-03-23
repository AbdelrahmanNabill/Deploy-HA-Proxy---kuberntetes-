# Deploy-HA-Proxy---kuberntetes-

ITI kubernetes project
Deploying Ha-proxy web application 

## Components and services used for Deploying the project . 

- Create Namespace.
- Create Deployment.
- Create a ServiceAccount.
- Create a ClusterRole and ClusterRoleBinding
- Create a backend deployment using Declartive way .
- Create a service for backend
- Create a deployment for frontend using Declartive way
    - Configure specs like image , args 
    - resources requests , livenessProbe , containerPort , environment variables .
- Create a service for frontend 
    - Configure specs like NodePort and same as backend Deployment .

## Screenshot of the web-application