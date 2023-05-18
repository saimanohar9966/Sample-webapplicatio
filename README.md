# web application
steps:

  1. terraform init - initializes a working directory containing Terraform configuration files. (terraform state file soored in s3 bucket)
  2. terraform validate - validates the terraform configuration files
  3. terraform fmt - your configuration files into a canonical format and style
  4. terraform plan - Terraform analyzes the configuration and determines what actions need to be taken to achieve the desired state. It identifies any changes, additions, or deletions of resources that are necessary.
  5. terraform apply -  performs a plan just like terraform plan does, but then actually carries out the planned changes to each resource using the relevant infrastructure provider's API.
