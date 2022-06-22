### Important Note

Note that every region has a different AMI ID. The AMI ID's keeps on changing so make sure you use the latest AMI ID from the AWS console similar to the way it is shown in the video.

### Documentation Referred:

https://registry.terraform.io/

https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs

### first_ec2.tf

```sh
terraform {
  required_providers {
    azurerm = {
      source = "hashicorp/azurerm"
      version = "3.10.0"
    }
  }
}

provider "azurerm" {
  # Configuration options
}
```
### Commands:

```sh
terraform init
terraform plan
terraform apply
```
