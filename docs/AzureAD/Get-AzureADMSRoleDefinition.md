# Get-AzureADMSRoleDefinition

> /roleManagement/directory/roleDefinitions | /roleManagement/directory/roleDefinitions/{unifiedRoleDefinition-id}

## Data

+ AAD Command: [Get-AzureADMSRoleDefinition](https://docs.microsoft.com/en-us/powershell/module/AzureAD/Get-AzureADMSRoleDefinition)
+ AAD Module: AzureAD
+ Graph Command: [Get-MgRoleManagementDirectoryRoleDefinition](https://docs.microsoft.com/en-us/powershell/module/Microsoft.Graph.DeviceManagement.Enrolment/Get-MgRoleManagementDirectoryRoleDefinition) ([Examples](https://github.com/orgs/msgraph/discussions?discussions_q=Get-MgRoleManagementDirectoryRoleDefinition))
+ Graph Module: Microsoft.Graph.DeviceManagement.Enrolment

> Scopes Needed (any one)

|Type|Scopes|
|---|---|
|Application|Directory.Read.All, Directory.ReadWrite.All, EntitlementManagement.Read.All, EntitlementManagement.ReadWrite.All, RoleManagement.Read.Directory, RoleManagement.ReadWrite.Directory|
|Delegate|Directory.Read.All, Directory.ReadWrite.All, EntitlementManagement.Read.All, EntitlementManagement.ReadWrite.All, RoleManagement.Read.Directory, RoleManagement.ReadWrite.Directory|

## Parameters

|AAD Name|Graph Name|AAD Type|Graph Type|Infos|
|---|---|---|---|---|
|All|All|System.Nullable/System.Boolean|System.Management.Automation.SwitchParameter||
|Id||System.String|||
|SearchString||System.String|||
|Top|Top|System.Nullable/System.Int32|System.Int32||
|Filter|Filter|System.String|System.String||

