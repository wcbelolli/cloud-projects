# cloud-projects

PS C:\Users\wbelolli\cloud-projects\ARM Template> New-AzResourceGroupDeployment `
>> -Name $deploymentName `
>> -TemplateFile $templateFile
New-AzResourceGroupDeployment : 05:31:37 - Error: Code=InvalidTemplateDeployment; Message=The template deployment 'blanketemplate-18-25-2023' is not valid 
according to the validation procedure. The tracking id is '5f2886b0-9eb0-4b7a-b6bb-0a80a7f66213'. See inner errors for details.
At line:1 char:1
+ New-AzResourceGroupDeployment `
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : NotSpecified: (:) [New-AzResourceGroupDeployment], Exception
    + FullyQualifiedErrorId : Microsoft.Azure.Commands.ResourceManager.Cmdlets.Implementation.NewAzureResourceGroupDeploymentCmdlet

New-AzResourceGroupDeployment : 05:31:37 - Error: Code=PreflightValidationCheckFailed; Message=Preflight validation failed. Please refer to the details for the   
specific errors.
At line:1 char:1
+ New-AzResourceGroupDeployment `
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : NotSpecified: (:) [New-AzResourceGroupDeployment], Exception
    + FullyQualifiedErrorId : Microsoft.Azure.Commands.ResourceManager.Cmdlets.Implementation.NewAzureResourceGroupDeploymentCmdlet

New-AzResourceGroupDeployment : 05:31:37 - Error: Code=StorageAccountAlreadyTaken; Message=The storage account named learntemplatestorage123 is already taken.    
At line:1 char:1
+ New-AzResourceGroupDeployment `
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : NotSpecified: (:) [New-AzResourceGroupDeployment], Exception
    + FullyQualifiedErrorId : Microsoft.Azure.Commands.ResourceManager.Cmdlets.Implementation.NewAzureResourceGroupDeploymentCmdlet

New-AzResourceGroupDeployment : The deployment validation failed
At line:1 char:1
+ New-AzResourceGroupDeployment `
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : CloseError: (:) [New-AzResourceGroupDeployment], InvalidOperationException
    + FullyQualifiedErrorId : Microsoft.Azure.Commands.ResourceManager.Cmdlets.Implementation.NewAzureResourceGroupDeploymentCmdlet
