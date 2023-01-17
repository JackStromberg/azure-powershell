### Example 1: Get the login credentials for a container registry
```powershell
Get-AzContainerRegistryCredential -ResourceGroupName "MyResourceGroup" -Name "MyRegistry"
```

```output
Username   Password                         Password2
--------   --------                         ---------
MyRegistry +Y+==B==KdT=YV=ZgH=p/zQ/e1sNQq/d //JRPkgxx+r+z/ztU=R//E==vum=pRKL
```

This command gets the login credentials for the specified container registry. Admin user has to be enabled for the container registry `MyRegistry` to get login credentials.
