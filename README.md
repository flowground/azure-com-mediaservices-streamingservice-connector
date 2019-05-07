# ![LOGO](logo.png) Azure Media Services **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Media Services API (version 2018-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/mediaservices-streamingservice/2018-07-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:23+03:00

## API Description

Streaming resource management client for Azure Media Services

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Live Events

> Lists the Live Events in the account.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Delete Live Event

> Deletes a Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get Live Event

> Gets a Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Updates a existing Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create Live Event

> Creates a Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.
* `autoStart` - _optional_ - The flag indicates if the resource should be automatically started on creation.

### List Live Outputs

> Lists the Live Outputs in the Live Event.

*Tags:* `LiveOutputs`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Delete Live Output

> Deletes a Live Output.

*Tags:* `LiveOutputs`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `liveOutputName` - _required_ - The name of the Live Output.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get Live Output

> Gets a Live Output.

*Tags:* `LiveOutputs`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `liveOutputName` - _required_ - The name of the Live Output.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create Live Output

> Creates a Live Output.

*Tags:* `LiveOutputs`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `liveOutputName` - _required_ - The name of the Live Output.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Reset Live Event

> Resets an existing Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Start Live Event

> Starts an existing Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Stop Live Event

> Stops an existing Live Event.

*Tags:* `LiveEvents`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `liveEventName` - _required_ - The name of the Live Event.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### List StreamingEndpoints

> Lists the StreamingEndpoints in the account.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Delete StreamingEndpoint

> Deletes a StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get StreamingEndpoint

> Gets a StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Update StreamingEndpoint

> Updates a existing StreamingEndpoint.

*Tags:* `StreamingEndpoint`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create StreamingEndpoint

> Creates a StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.
* `autoStart` - _optional_ - The flag indicates if the resource should be automatically started on creation.

### Scale StreamingEndpoint

> Scales an existing StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Start StreamingEndpoint

> Starts an existing StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Stop StreamingEndpoint

> Stops an existing StreamingEndpoint.

*Tags:* `StreamingEndpoints`

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `streamingEndpointName` - _required_ - The name of the StreamingEndpoint.
* `api-version` - _required_ - The Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-mediaservices-streamingservice-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
