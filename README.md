# Repyute-Assignment

## Terraform module to provision AWS EKS in new VPC

Prerequisites:

1 AWS CLI

2 AWS Access Key ID.

3 AWS Secret Access Key.

4 Default region name.

5 Default output format.

After you've installed the AWS CLI, configure it by running aws configure.

When prompted, enter your AWS Access Key ID, Secret Access Key, region and output format.

creating a new folder, and in that folder create a file named main.tf as provided.

In the same folder, run:
### terraform init
The command will initialise Terraform and create two more folders as well as a state file.

Next:
### terraform plan
Terraform will perform a dry-run and will prompt you a detailed summary of what resources is about to create.

Now finally
### terraform apply
cluster is ready to be used.
