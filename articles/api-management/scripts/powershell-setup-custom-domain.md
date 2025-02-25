---
title: Azure PowerShell Script Sample - Set up custom domain | Microsoft Docs
description: Learn how to set up a custom domain on proxy or portal endpoints of the API management service. See sample scripts and view additional available resources.
services: api-management
documentationcenter: ''
author: dlepow
manager: cfowler
editor: ''

ms.service: api-management
ms.workload: mobile
ms.topic: sample
ms.date: 12/14/2017
ms.author: danlep
ms.custom: mvc, devx-track-azurepowershell
---

# Set up custom domain

This sample script sets up custom domain on proxy and portal endpoint of the API Management service.

[!INCLUDE [updated-for-az](../../../includes/updated-for-az.md)]

[!INCLUDE [cloud-shell-try-it.md](../../../includes/cloud-shell-try-it.md)]

If you choose to install and use the PowerShell locally, this tutorial requires the Azure PowerShell module version 1.0 or later. Run `Get-Module -ListAvailable Az` to find the version. If you need to upgrade, see [Install Azure PowerShell module](/powershell/azure/install-azure-powershell). If you are running PowerShell locally, you also need to run `Connect-AzAccount` to create a connection with Azure.

## Sample script

[!code-powershell[main](../../../powershell_scripts/api-management/setup-custom-domain/setup_custom_domain.ps1 "Set up custom domain")]

## Clean up resources

When no longer needed, you can use the [Remove-AzResourceGroup](/powershell/module/az.resources/remove-azresourcegroup) command to remove the resource group and all related resources.

```azurepowershell-interactive
Remove-AzResourceGroup -Name myResourceGroup
```

[!INCLUDE [api-management-custom-domain](../../../includes/api-management-custom-domain.md)]

## Next steps

For more information on the Azure PowerShell module, see [Azure PowerShell documentation](/powershell/azure/).

Additional Azure PowerShell samples for Azure API Management can be found in the [PowerShell samples](../powershell-samples.md).
