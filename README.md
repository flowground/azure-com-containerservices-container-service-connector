# ![LOGO](logo.png) ContainerServiceClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerServiceClient API (version 2017-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerservices-containerService/2017-07-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:50+03:00

## API Description

The Container Service Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list of container services in the specified subscription.

> Gets a list of container services in the specified subscription. The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.

*Tags:* `ContainerServices`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a list of container services in the specified resource group.

> Gets a list of container services in the specified subscription and resource group. The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.

*Tags:* `ContainerServices`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified container service.

> Deletes the specified container service in the specified subscription and resource group. The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets. All the other resources created with the container service are part of the same resource group and can be deleted individually.

*Tags:* `ContainerService`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerServiceName` - _required_ - The name of the container service in the specified subscription and resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the properties of the specified container service.

> Gets the properties of the specified container service in the specified subscription and resource group. The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.

*Tags:* `ContainerService`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerServiceName` - _required_ - The name of the container service in the specified subscription and resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a container service.

> Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.

*Tags:* `ContainerService`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerServiceName` - _required_ - The name of the container service in the specified subscription and resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerservices-container-service-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
