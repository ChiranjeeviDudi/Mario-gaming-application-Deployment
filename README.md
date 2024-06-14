Deploying Mario gaming Application on AWS EKS Cluster.

step 1: Launched an Ec2 instance with ubuntu machine, t2 micro(free tier) with 13 gp2 storage.

step 2: created a role and attached it to the Ec2 instance.

step 3: Installing the Terraform, Kubectl, AWS CLI using the shell commands in script.

step 4: Cloned the GitHub repo

step 5: Provisioned the AWS EKS Cluster using Terraform IaC using Terraform init, Terraform validate, Terraform plan, Terraform apply Terraform destroy

step 6: Used Kubectl commands to apply the Deployment and Service yaml files to get the desired state of running pods

step 7: After sucessful completion of project implementation delete the Deployment and Service in EKS Cluster, use Terraform Destroy to remove / delete the EKS Cluster.
