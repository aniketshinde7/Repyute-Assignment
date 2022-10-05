## Repyute-Assignment

# Terraform module to provision AWS EKS in new VPC

Prerequisites:
AWS CLI
AWS Access Key ID.
AWS Secret Access Key.
Default region name.
Default output format.

After you've installed the AWS CLI, configure it by running aws configure.

When prompted, enter your AWS Access Key ID, Secret Access Key, region and output format.

creating a new folder, and in that folder create a file named main.tf as provided.

In the same folder, run:
terraform init
The command will initialise Terraform and create two more folders as well as a state file.

Next:
terraform plan
Terraform will perform a dry-run and will prompt you a detailed summary of what resources is about to create.

Now finally
terraform apply
cluster is ready to be used.
