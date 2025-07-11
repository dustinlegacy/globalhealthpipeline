
https://app.terraform.io

After logging into Terraform Cloud and making an account/profiile, we need to download Hashicorp and Terraform on our local machine. We are using MacOS.

```
brew tap hashicorp/tap
brew install terraform
```
Once the installastion is complete, you can run the following command to make sure it downloaded correctly

```
terraform -help
```

In the main github repo, make a sub-directory for you terraform project. For our project, this can be found here: [terraform](terraform)

Next you have to connect GCP with Terrafrom. We followed the quick start guide here: https://registry.terraform.io/providers/hashicorp/google/latest/docs/guides/getting_started
