Spring deployment:
1) Built JAR file from the Spring web app and deployed into AWS Cloud using AWS Beanstalk service (on EC2 instance)
2) Built Docker image from the web app with Dockerfile
3) Docker image deployed into Kubernetes (using Kind instead of AWS EKS): created cluster/deployement.yaml/exposed port to run the Docker instance from Kubernetes
4) Created WAR file for server application deployement
