# New-AzureADApplicationKeyCredential

> /applications/{application-id}/addKey

## Data

+ AAD Command: [New-AzureADApplicationKeyCredential](https://docs.microsoft.com/en-us/powershell/module/AzureAD/New-AzureADApplicationKeyCredential)
+ AAD Module: AzureAD
+ Graph Command: [Add-MgApplicationKey](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Applications/Add-MgApplicationKey) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Add-MgApplicationKey))
+ Graph Module: Microsoft.Graph.Applications

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Application.ReadWrite.All, Directory.ReadWrite.All|
|Delegate|Application.ReadWrite.All, Directory.ReadWrite.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|CustomKeyIdentifier||System.String|||
|Usage||System.Nullable/Microsoft.Open.AzureAD.Graph.PowerShell.Custom.KeyUsage|||
|Type||System.Nullable/Microsoft.Open.AzureAD.Graph.PowerShell.Custom.KeyType|||
|Value||System.String|||
|EndDate||System.Nullable/System.DateTime|||
|ObjectId||System.String|||
|StartDate||System.Nullable/System.DateTime|||

