---
title: "Create advancedRiskReportingSettings"
description: "Create a new advancedRiskReportingSettings object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create advancedRiskReportingSettings
Namespace: microsoft.graph



Create a new [advancedRiskReportingSettings](../resources/advancedriskreportingsettings.md) object.

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
POST ** Collection URI for Microsoft.IdentityProtectionServices.advancedRiskReportingSettings not found
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [advancedRiskReportingSettings](../resources/advancedriskreportingsettings.md) object.

The following table shows the properties that are required when you create the [advancedRiskReportingSettings](../resources/advancedriskreportingsettings.md).

|Property|Type|Description|
|:---|:---|:---|
|enabledFor|[Microsoft.IdentityProtectionServices.directoryObjectsSelection](../resources/directoryobjectsselection.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and an [advancedRiskReportingSettings](../resources/advancedriskreportingsettings.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_advancedriskreportingsettings_from_"
}
-->
``` http
POST https://graph.microsoft.com/v1.0** Collection URI for Microsoft.IdentityProtectionServices.advancedRiskReportingSettings not found
Content-Type: application/json
Content-length: 181

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.advancedRiskReportingSettings",
  "enabledFor": {
    "@odata.type": "microsoft.graph.directoryObjectsSelection"
  }
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.IdentityProtectionServices.advancedRiskReportingSettings"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.IdentityProtectionServices.advancedRiskReportingSettings",
  "enabledFor": {
    "@odata.type": "microsoft.graph.directoryObjectsSelection"
  }
}
```
