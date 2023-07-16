#udacity_devops_capstone

#######

Meet all requirement in rubic:
1. Set Up Pipeline
2. Build Docker Container
3. Successful Deployment


In this app I use:
1. To deploy EKS using the AWS CLI, you can find the CloudFormation configuration attached in the 'infra/cluster.yml' file.
2. The deployment will follow the blue-green option, where the Green version (v1) and Blue version (v2) will be used.
3. All images will be stored in Docker Hub for easy access and management.
4. We will provide a sample approval process to demonstrate the deployment flow.
5. For this process, we will utilize a personal account due to some issues related to creating the EKS cluster with other credentials.
