# ![LOGO](logo.png) SubscriptionDefinitionsClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionDefinitionsClient API (version 2017-11-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/subscription-subscriptionDefinitions/2017-11-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:39:19+03:00

## API Description

Subscription definitions client provides an interface to create, modify and retrieve azure subscriptions programmatically.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Microsoft.Subscription API operations.

*Tags:* `SubscriptionDefinitions`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### List an Azure subscription definition by subscriptionId.

*Tags:* `SubscriptionDefinitions`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### Get an Azure subscription definition.

*Tags:* `SubscriptionDefinitions`

#### Input Parameters
* `subscriptionDefinitionName` - _required_ - The name of the Azure subscription definition.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### Create an Azure subscription definition.

*Tags:* `SubscriptionDefinitions`

#### Input Parameters
* `subscriptionDefinitionName` - _required_ - The name of the Azure subscription definition.
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01

### Retrieves the status of the subscription definition PUT operation. The URI of this API is returned in the Location field of the response header.

*Tags:* `SubscriptionDefinitions`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. Current version is 2015-06-01
* `operationId` - _required_ - The operation ID, which can be found from the Location field in the generate recommendation response header.

## License

**flow**ground :- Telekom iPaaS / azure-com-subscription-subscription-definitions-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
