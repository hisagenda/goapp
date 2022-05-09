# goapp


# Creating an EKS cluster and a VPC using terraform

# - Summary:

● Automating the build of the container

● Setting up the ingress load balancer

● Defining the whole infrastructure as code

# - Prerequisites and tools:

1. Terraform : https://learn.hashicorp.com/terraform/getting-started/install.html
2. Azure Subscription (Access Key & Secret Key)
3. AZ CLI : https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html
4. Code Editor of choice
5. Helm

# - Installation Steps:

- To install terraform If you do not already have it installed, I will recommend you go through the link here - https://learn.hashicorp.com/terraform/getting-started/install.html

# - Code

- Go application was cloned from https://github.com/olliefr/docker-gs-ping for test 
- created AGW with no routing rule and a virtual network it sits on
- Proceeded to create an AKS cluster using Azure Terraform with code definitions


# - Summary

-  Code has necessary comments in portions where some explanation may be needed on code use
-  Code can be deployed to AKS, however if we wanted to deploy to any other provider we would need to make changes to the providers 
-  State files are stored locally for this project, however for a production deployment I would advise to use a File share on the cloud
-  To persist variable values, create a “terraform.tfvars ” file, and assign variables within this file.


# Tip: if you are looking for deleting the resource, terraform destroy will clean up all the resources created for you.


- Thanks for taking out time to read! if you have anything to add please send a response or add a note!


# -  Author email:  abiola.kayode@gmail.com






