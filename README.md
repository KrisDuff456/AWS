# AWS
This will be step by step instructions using Amazon Web Services console to create and launch services such as EKS or something simple as a VPC. 

*Note I am still learning the AWS platform and these instructions are based off my experiance using the platform.

# Content 

1. EKS creation
2. Worker Nodes
3. S3 Bucket
4. EFS
5. ECR

# Perrmisions 
If you are using a user, you will need to attach some of these permissions in order to have access to creating the resources. 

  AutoScalingFullAccess
  AmazonEKSClusterPolicy
  AmazonEKSWorkerNodePolicy
  AmazonVPCFullAccess
  AmazonEKSServicePolicy
  AmazonEKS_CNI_Policy
  AmazonEC2FullAccess
