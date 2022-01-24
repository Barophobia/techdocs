+++
title = "Terraform"
weight = 5
chapter = true
pre = "<b> - </b>"
+++

# Terraform

```
terraform plan          # dry run
terraform apply         # apply configuration changes
terraform refresh       # synchronise state with the resource
terraform destroy       # destroy current configuration
```

### State management

```
terraform state list # this will show the resources in the state file
terraform state rm <RESOURCE> # remove a resource from the state list
```
### Correcting formatting

```
terraform fmt #reformats .tf files for better readability
```

### Remote Exec

This is used for remotely executing a command.

```
provisioner "remote-exec" {
    inline = [
         "apt install neofetch"
    ]
}
```

