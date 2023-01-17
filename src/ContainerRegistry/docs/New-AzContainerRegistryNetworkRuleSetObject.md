---
external help file:
Module Name: Az.ContainerRegistry
online version: https://learn.microsoft.com/powershell/module/az.ContainerRegistry/new-AzContainerRegistryNetworkRuleSetObject
schema: 2.0.0
---

# New-AzContainerRegistryNetworkRuleSetObject

## SYNOPSIS
Create an in-memory object for NetworkRuleSet.

## SYNTAX

```
New-AzContainerRegistryNetworkRuleSetObject -DefaultAction <DefaultAction> [-IPRule <IIPRule[]>]
 [<CommonParameters>]
```

## DESCRIPTION
Create an in-memory object for NetworkRuleSet.

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
{{ Add code here }}
```

```output
{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
{{ Add code here }}
```

```output
{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -DefaultAction
The default action of allow or deny when no other rules match.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.ContainerRegistry.Support.DefaultAction
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IPRule
The IP ACL rules.
To construct, see NOTES section for IPRULE properties and create a hash table.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.ContainerRegistry.Models.Api20220201Preview.IIPRule[]
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.ContainerRegistry.Models.Api20220201Preview.NetworkRuleSet

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


`IPRULE <IIPRule[]>`: The IP ACL rules.
  - `IPAddressOrRange <String>`: Specifies the IP or IP range in CIDR format. Only IPV4 address is allowed.
  - `[Action <Action?>]`: The action of IP ACL rule.

## RELATED LINKS

