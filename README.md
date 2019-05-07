# ![LOGO](logo.png) Management Groups **flow**ground Connector

## Description

A generated **flow**ground connector for the Management Groups API (version 2017-08-31-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/resources-management/2017-08-31-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:46+03:00

## API Description

The Azure Management Groups API enables consolidation of multiple 
subscriptions/resources into an organizational hierarchy and centrally 
manage access control, policies, alerting and reporting for those resources.


## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List management groups for the authenticated user.

*Tags:* `ManagementGroups`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2017-08-31-preview.
* `$skiptoken` - _optional_ - Page continuation token is only used if a previous operation returned a partial result. 
If a previous response contains a nextLink element, the value of the nextLink element will include a token parameter that specifies a starting point to use for subsequent calls.


### Get the details of the management group.

*Tags:* `ManagementGroups`

#### Input Parameters
* `groupId` - _required_ - Management Group ID.
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2017-08-31-preview.
* `$expand` - _optional_ - The $expand=children query string parameter allows clients to request inclusion of children in the response payload.
    Possible values: children.
* `$recurse` - _optional_ - The $recurse=true query string parameter allows clients to request inclusion of entire hierarchy in the response payload.

### Lists all of the available management REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request. The current version is 2017-08-31-preview.

## License

**flow**ground :- Telekom iPaaS / azure-com-resources-management-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
