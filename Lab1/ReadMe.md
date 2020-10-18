#Arm Template Deployment

⋅⋅* Download and authenticate Azure CLI

⋅⋅* Create azuredeploy.json and azuredeploy.parameters.json

..* execute powershell command: 
  New-AzResourceGroupDeployment -Name ExampleDeployment -ResourceGroupName ExampleResourceGroup `
  -TemplateFile c:\MyTemplates\azuredeploy.json `
  -TemplateParameterFile c:\MyTemplates\storage.parameters.json