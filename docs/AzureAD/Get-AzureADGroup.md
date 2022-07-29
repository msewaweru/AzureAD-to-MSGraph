# Get-AzureADGroup

> /groups | /groups/{group-id}

## Data

+ AAD Command: [Get-AzureADGroup](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Get-AzureADGroup)
+ AAD Module: AzureAD
+ Graph Command: [Get-MgGroup](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.Groups/Get-MgGroup)
+ Graph Module: Microsoft.Graph.Groups

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Directory.Read.All, Directory.ReadWrite.All, Group.Read.All, Group.ReadWrite.All, GroupMember.Read.All|
|Delegate|Directory.AccessAsUser.All, Directory.Read.All, Directory.ReadWrite.All, Group.Read.All, Group.ReadWrite.All, GroupMember.Read.All|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|ObjectId||System.String|||
|Filter|Filter|System.String|System.String||
|Top|Top|System.Nullable/System.Int32|System.Int32||
|SearchString||System.String|||
|All|All|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
