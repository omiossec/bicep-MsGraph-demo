# bicep and Microsoft Graph demo

Repos to demonstrate how to use Microsoft Graph with Bicep for a Dev.to post

Note, currently Microsoft Graph Bicep is a preview feature.

## deploying resources 

```powershell
New-AzResourceGroupDeployment -ResourceGroupName bicep-azgraph -TemplateFile ./Bicep/main.bicep
```

