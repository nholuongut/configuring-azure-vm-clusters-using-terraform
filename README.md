# Configuring-Azure-VM-Clusters-Using-Terraform

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

# Public repository for my A Cloud on Github

## Deploying the Prerequisites

We are using the Azure CLI for authentication and deployment. You can find the Azure CLI [here](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest).

```bash
az login
az account set -s "SUBSCRIPTION_NAME"
```

Once you are logged in, you can deploy the prerequisites. First make a copy of the `terraform.tfvars.example` file and rename it to `terraform.tfvars`. Then edit the file and fill in the values for the variables.

Once your `terraform.tfvars` file is ready, you can deploy the resources:

```bash
terraform init
terraform apply -auto-approve
```

🚀 # I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](bitfield.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟

