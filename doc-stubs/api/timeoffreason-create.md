---
title: "Create timeOffReason"
description: "Create a new timeOffReason object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create timeOffReason
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [timeOffReason](../resources/timeoffreason.md) object.

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
POST /team/schedule/timeOffReasons
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [timeOffReason](../resources/timeoffreason.md) object.

The following table shows the properties that are required when you create the [timeOffReason](../resources/timeoffreason.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md)|
|createdBy|[Microsoft.Teams.Shifts.identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md)|
|lastModifiedBy|[Microsoft.Teams.Shifts.identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md)|
|displayName|String|**TODO: Add Description**|
|iconType|timeOffReasonIconType|**TODO: Add Description**. The possible values are: `none`, `car`, `calendar`, `running`, `plane`, `firstAid`, `doctor`, `notWorking`, `clock`, `juryDuty`, `globe`, `cup`, `phone`, `weather`, `umbrella`, `piggyBank`, `dog`, `cake`, `trafficCone`, `pin`, `sunny`, `unknownFutureValue`.|
|isActive|Boolean|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [timeOffReason](../resources/timeoffreason.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_timeoffreason_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/team/schedule/timeOffReasons
Content-Type: application/json
Content-length: 215

{
  "@odata.type": "#Microsoft.Teams.Shifts.timeOffReason",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "displayName": "String",
  "iconType": "String",
  "isActive": "Boolean"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.Teams.Shifts.timeOffReason"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.Teams.Shifts.timeOffReason",
  "id": "8cd8a0c5-a0c5-8cd8-c5a0-d88cc5a0d88c",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "createdDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "displayName": "String",
  "iconType": "String",
  "isActive": "Boolean"
}
```
