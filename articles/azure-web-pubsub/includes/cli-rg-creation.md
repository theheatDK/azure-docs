---
author: vicancy
ms.service: azure-web-pubsub
ms.topic: include
ms.date: 08/06/2021
ms.author: lianwei
---

A resource group is a logical container into which Azure resources are deployed and managed. Use the [az group create](/cli/azure/group#az_group_create) command to create a resource group named *myResourceGroup* in the *eastus* location.

```azurecli-interactive
az group create --name "myResourceGroup" -l "EastUS"
```
