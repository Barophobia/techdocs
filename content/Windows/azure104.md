+++
title = "Azure 104 Exam Study Guide"
date = 2021-12-09T16:51:31Z
weight = 5
chapter = true
pre = "<b> - </b>"
+++

## Skills Measured
- Manage Azure identities and governance (15–20%)
- Implement and manage storage (15–20%)
- Deploy and manage Azure compute resources (20–25%)
- Configure and manage virtual networking (20-25%)
- Monitor and maintain Azure resources (10–15%)

## Manage Azure identities and governance (15–20%)
### Manage Azure Active Directory (Azure AD) objects
- Create users and groups
Creating a new user: 
	- Sign into Azure portal
	- Go into 'Azure Active Directory'
	- Select 'Users' in the left hand menu
	- Click the 'New User' button
   Inside the 'New user' form you will be asked for:
	- Name
	- Username
	- Groups
	- Directory Role
	- Job info
   An autogenerated password will be provided inside the password box, then select create.


Creating a new group: 
	- Sign into Azure portal
	- Go into 'Azure Active Directory'
	- Select 'Group' in the left hand menu
	- Click the 'New Group' button
   Inside the 'New Group' form you will be asked for:
	- Group Type
	- Group Name
	- Group Description
	- Membership type
	- Owners
	- Members
   Then select create.

- Manage licenses in Azure AD
Viewing Licenses:
	- Sign into Azure portal
	- Go into 'Azure Active Directory'
	- Select 'Licenses' in the left hand menu
Inside License there will be an 'All Products' option on the left hand menu this will show your current licenses as well as having options to try/buy more and assign licenses to users.

- Create administrative units
	- Sign into Azure portal
	- Go into 'Azure Active Directory'
	- Select 'Administrative Units' in the left hand menu
	- Click the 'Add' button to create an administrative unit
Inside the 'Add administrative unit' you will be asked for:
	- Name
	- Description
Inside this form you can also add roles to the new administrative unit.

- Manage user and group properties

- Manage device settings and device identity
- Perform bulk updates
- Manage guest accounts
- Configure self-service password reset

### Manage access control
- Create custom role-based access control (RBAC) and Azure AD roles
- Provide access to Azure resources by assigning roles at different scopes
- Interpret access assignments

### Manage Azure subscriptions and governance
- Configure and manage Azure Policy
- Configure resource locks
- Apply and manage tags on resources
- Manage resource groups
- Manage subscriptions
- Manage costs by using alerts, budgets, and recommendations
- Configure management groups

## Implement and manage storage (15—20%)
### Configure access to storage
- Configure network access to storage accounts
- Create and configure storage accounts
- Generate shared access signature tokens
- Configure stored access policies
- Manage access keys
- Configure Azure AD authentication for a storage account
- Configure storage encryption

### Manage data in Azure storage accounts
- Create import and export jobs
- Manage data by using Azure Storage Explorer and AzCopy
- Implement Azure Storage redundancy
- Configure object replication

### Configure Azure Files and Azure Blob Storage
- Create an Azure file share
- Configure Azure Blob Storage
- Configure storage tiers
- Configure blob lifecycle management

## Deploy and manage Azure compute resources (20—25%)
### Automate deployment of resources by using templates
- Modify an ARM template
- Deploy a template
- Save a deployment as an ARM template
- Deploy virtual machine (VM) extensions

### Create and configure VMs
- Create a VM
- Manage images by using the Azure Compute Gallery
- Configure Azure Disk Encryption
- Move VMs from one resource group to another
- Manage VM sizes
- Add data disks
- Configure VM network settings
- Configure VM availability options
- Deploy and configure VM scale sets

### Create and configure containers
- Configure sizing and scaling for Azure Container Instances
- Configure container groups for Azure Container Instances
- Configure storage for Azure Kubernetes Service (AKS)
- Configure network connections for AKS
- Upgrade an AKS cluster

### Create and configure an Azure App Service
- Create an App Service plan
- Configure scaling settings in an App Service plan
- Create an App Service
- Secure an App Service
- Configure custom domain names
- Configure backup for an App Service
- Configure networking settings
- Configure deployment settings

## Configure and manage virtual networking (20—25%)
### Configure virtual networks
- Create and configure virtual networks and subnets
- Create and configure virtual network peering
- Configure private and public IP addresses
- Configure user-defined network routes
- Configure Azure DNS

### Configure secure access to virtual networks
- Create and configure network security groups (NSGs) and application security groups (ASGs)
- Evaluate effective security rules
- Implement Azure Bastion
- Configure service endpoints on subnets
- Configure private endpoints

### Configure load balancing
- Configure Azure Application Gateway
- Configure an internal or public load balancer
- Troubleshoot load balancing

### Monitor virtual networking
- Monitor on-premises connectivity
- Configure and use Azure Monitor for networks
- Use Azure Network Watcher
- Troubleshoot external networking
- Troubleshoot virtual network connectivity

## Monitor and maintain Azure resources (10—15%)
### Monitor resources by using Azure Monitor
- Configure and interpret metrics
- Configure Azure Monitor Logs
- Query and analyze logs
- Set up alerts and actions
- Configure monitoring of VMs, storage accounts, and networks by using VM insights

### Implement backup and recovery:
- Create an Azure Recovery Services vault
- Create an Azure Backup vault
- Create and configure backup policy
- Perform backup and restore operations by using Azure Backup
- Configure Azure Site Recovery for Azure resources
- Perform failover to a secondary region by using Azure Site Recovery
- Configure and review backup reports