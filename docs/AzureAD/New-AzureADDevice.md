# New-AzureADDevice

> /devices

## Data

+ AAD Command: [New-AzureADDevice](https://docs.microsoft.com/en-us/powershell/module/AzureAD/New-AzureADDevice)
+ AAD Module: AzureAD
+ Graph Command: [New-MgDevice](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Identity.DirectoryManagement/New-MgDevice) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=New-MgDevice))
+ Graph Module: Microsoft.Graph.Identity.DirectoryManagement

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application||
|Delegate|Directory.AccessAsUser.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|DeviceObjectVersion||System.Nullable/System.Int32|||
|DeviceId|DeviceId|System.String|System.String||
|DisplayName|DisplayName|System.String|System.String||
|DeviceOSType||System.String|||
|AlternativeSecurityIds|AlternativeSecurityIds|System.Collections.Generic.List/Microsoft.Open.AzureAD.Model.AlternativeSecurityId|Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAlternativeSecurityId[]||
|AccountEnabled|AccountEnabled|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|ApproximateLastLogonTimeStamp||System.Nullable/System.DateTime|||
|DeviceTrustType||System.String|||
|DevicePhysicalIds||System.Collections.Generic.List/System.String|||
|DeviceOSVersion||System.String|||
|IsManaged|IsManaged|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|ProfileType|ProfileType|System.String|System.String||
|SystemLabels|SystemLabels|System.Collections.Generic.List/System.String|System.String[]||
|DeviceMetadata|DeviceMetadata|System.String|System.String||
|IsCompliant|IsCompliant|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||

