# Set-AzureADServicePrincipal

> /servicePrincipals/{servicePrincipal-id}

## Data

+ AAD Command: [Set-AzureADServicePrincipal](https://docs.microsoft.com/en-us/powershell/module/AzureADPreview/Set-AzureADServicePrincipal)
+ AAD Module: AzureADPreview
+ Graph Command: [Update-MgServicePrincipal](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/Update-MgServicePrincipal) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Update-MgServicePrincipal))
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Application.ReadWrite.All|
|Delegate|Application.ReadWrite.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|ErrorUrl||System.String|||
|Tags|Tags|System.Collections.Generic.List/System.String|System.String[]||
|PasswordCredentials|PasswordCredentials|System.Collections.Generic.List/Microsoft.Open.AzureAD.Model.PasswordCredential|Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPasswordCredential[]||
|KeyCredentials|KeyCredentials|System.Collections.Generic.List/Microsoft.Open.AzureAD.Model.KeyCredential|Microsoft.Graph.PowerShell.Models.IMicrosoftGraphKeyCredential[]||
|Homepage|Homepage|System.String|System.String||
|ObjectId||System.String|||
|ServicePrincipalType|ServicePrincipalType|System.String|System.String||
|DisplayName|DisplayName|System.String|System.String||
|AppRoleAssignmentRequired|AppRoleAssignmentRequired|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|AccountEnabled|AccountEnabled|System.String|System.Management.Automation.SwitchParameter||
|ReplyUrls|ReplyUrls|System.Collections.Generic.List/System.String|System.String[]||
|AppId|AppId|System.String|System.String||
|PublisherName||System.String|||
|AlternativeNames|AlternativeNames|System.Collections.Generic.List/System.String|System.String[]||
|LogoutUrl|LogoutUrl|System.String|System.String||
|ServicePrincipalNames|ServicePrincipalNames|System.Collections.Generic.List/System.String|System.String[]||
|SamlMetadataUrl||System.String|||

