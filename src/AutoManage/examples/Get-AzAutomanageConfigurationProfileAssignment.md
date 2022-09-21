### Example 1: {{ Add title here }}
```powershell
Get-AzAutomanageConfigurationProfileAssignment
```

```output
Name    ResourceGroupName ManagedBy Status  TargetId
----    ----------------- --------- ------  --------
default automangerg                 Unknown /subscriptions/9e223dbe-3399-4e19-88eb-0975f02ac87f/resourceGroups/automangerg/providers/Microsoft.Compute/virtualMachines/aglinuxvm
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
Get-AzAutomanageConfigurationProfileAssignment -ResourceGroupName automangerg -VMName aglinuxvm
```

```output
Name    ResourceGroupName ManagedBy Status  TargetId
----    ----------------- --------- ------  --------
default automangerg                 Unknown /subscriptions/9e223dbe-3399-4e19-88eb-0975f02ac87f/resourceGroups/automangerg/providers/Microsoft.Compute/virtualMachines/aglinuxvm
```

{{ Add description here }}

### Example 3: {{ Add title here }}
```powershell
New-AzAutomanageConfigurationProfileAssignment -ResourceGroupName automangerg -VMName aglinuxvm -ConfigurationProfile "/providers/Microsoft.Automanage/bestPractices/AzureBestPracticesProduction" | Get-AzAutomanageConfigurationProfileAssignment
```

```output
Name    ResourceGroupName ManagedBy Status  TargetId
----    ----------------- --------- ------  --------
default automangerg                 Unknown /subscriptions/9e223dbe-3399-4e19-88eb-0975f02ac87f/resourceGroups/automangerg/providers/Microsoft.Compute/virtualMachines/aglinuxvm
```

{{ Add description here }}