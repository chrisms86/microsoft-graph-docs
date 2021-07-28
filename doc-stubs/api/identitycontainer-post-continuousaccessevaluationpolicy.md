---
title: "Create continuousAccessEvaluationPolicy"
description: "Create a new continuousAccessEvaluationPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create continuousAccessEvaluationPolicy
Namespace: microsoft.graph



Create a new continuousAccessEvaluationPolicy object.

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
POST /identityContainer/continuousAccessEvaluationPolicy
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object.

The following table shows the properties that are required when you create the [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|isEnabled|Boolean|**TODO: Add Description**|
|users|String collection|**TODO: Add Description**|
|groups|String collection|**TODO: Add Description**|
|isContinuousAccessEvaluationConfiguredByConditionalAccess|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_continuousaccessevaluationpolicy_from_"
}
-->
``` http
POST https://graph.microsoft.com/v1.0/identityContainer/continuousAccessEvaluationPolicy
Content-Type: application/json
Content-length: 322

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.continuousAccessEvaluationPolicy",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "users": [
    "String"
  ],
  "groups": [
    "String"
  ],
  "isContinuousAccessEvaluationConfiguredByConditionalAccess": "Boolean"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IdentityProtectionServices.continuousAccessEvaluationPolicy"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.continuousAccessEvaluationPolicy",
  "id": "68d6189a-189a-68d6-9a18-d6689a18d668",
  "description": "String",
  "displayName": "String",
  "isEnabled": "Boolean",
  "users": [
    "String"
  ],
  "groups": [
    "String"
  ],
  "isContinuousAccessEvaluationConfiguredByConditionalAccess": "Boolean"
}
```
