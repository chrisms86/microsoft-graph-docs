---
title: "Create user"
description: "Create a new user object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create user
Namespace: microsoft.graph



Create a new [user](../resources/user.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /users
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [user](../resources/user.md) object.

The following table shows the properties that are required when you create the [user](../resources/user.md).

|Property|Type|Description|
|:---|:---|:---|
|identityUserRisk|[Microsoft.IdentityProtectionServices.identityUserRisk](../resources/identityuserrisk.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [user](../resources/user.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_user_from_users"
}
-->
``` http
POST https://graph.microsoft.com/v1.0/users
Content-Type: application/json
Content-length: 153

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.user",
  "identityUserRisk": {
    "@odata.type": "microsoft.graph.identityUserRisk"
  }
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IdentityProtectionServices.user"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.user",
  "identityUserRisk": {
    "@odata.type": "microsoft.graph.identityUserRisk"
  }
}
```
