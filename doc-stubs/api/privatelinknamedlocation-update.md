---
title: "Update privateLinkNamedLocation"
description: "Update the properties of a privateLinkNamedLocation object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update privateLinkNamedLocation
Namespace: microsoft.graph



Update the properties of a [privateLinkNamedLocation](../resources/privatelinknamedlocation.md) object.

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
PATCH /privateLinkNamedLocations/{privateLinkNamedLocationsId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [privateLinkNamedLocation](../resources/privatelinknamedlocation.md) object.

The following table shows the properties that are required when you update the [privateLinkNamedLocation](../resources/privatelinknamedlocation.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [namedLocation](../resources/namedlocation.md)|
|displayName|String|**TODO: Add Description** Inherited from [namedLocation](../resources/namedlocation.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [namedLocation](../resources/namedlocation.md)|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [namedLocation](../resources/namedlocation.md)|
|privateLinkResourcePolicyIds|String collection|**TODO: Add Description**|
|isTrusted|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [privateLinkNamedLocation](../resources/privatelinknamedlocation.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_privatelinknamedlocation"
}
-->
``` http
PATCH https://graph.microsoft.com/v1.0/privateLinkNamedLocations/{privateLinkNamedLocationsId}
Content-Type: application/json
Content-length: 178

{
  "@odata.type": "#microsoft.graph.privateLinkNamedLocation",
  "displayName": "String",
  "privateLinkResourcePolicyIds": [
    "String"
  ],
  "isTrusted": "Boolean"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.privateLinkNamedLocation",
  "id": "9a43f380-f380-9a43-80f3-439a80f3439a",
  "displayName": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedDateTime": "String (timestamp)",
  "privateLinkResourcePolicyIds": [
    "String"
  ],
  "isTrusted": "Boolean"
}
```
