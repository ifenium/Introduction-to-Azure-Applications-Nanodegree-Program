# Create a Resource Group 
name: resource-group-west

location: West US region

## Step 1:
Install the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) for your Operating System if you haven't already.

---
## Step 2:
Please note that I'll be using Windows hence Powershell will be my default terminal.

* Login in using: `az login`

---
### Step 3:
* Check out the list of all locations in a tabular format available using: `az account list-locations -o table` 

* Create the resource group in West US regions `az group create --name resource-group-west --location westus`
