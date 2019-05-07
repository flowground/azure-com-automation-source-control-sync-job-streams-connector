# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2017-05-15-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-sourceControlSyncJobStreams/2017-05-15-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:22+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of sync job streams identified by sync job id.

*Tags:* `SourceControlSyncJobStreams`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `sourceControlName` - _required_ - The source control name.
* `sourceControlSyncJobId` - _required_ - The source control sync job id.
* `$filter` - _optional_ - The filter to apply on the operation.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve a sync job stream identified by stream id.

*Tags:* `SourceControlSyncJobStreams`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `sourceControlName` - _required_ - The source control name.
* `sourceControlSyncJobId` - _required_ - The source control sync job id.
* `streamId` - _required_ - The id of the sync job stream.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-source-control-sync-job-streams-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
