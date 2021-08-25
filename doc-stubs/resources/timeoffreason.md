---
title: "timeOffReason resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# timeOffReason resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [changeTrackedEntity](../resources/changetrackedentity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List timeOffReasons](../api/timeoffreason-list.md)|[timeOffReason](../resources/timeoffreason.md) collection|Get a list of the [timeOffReason](../resources/timeoffreason.md) objects and their properties.|
|[Create timeOffReason](../api/timeoffreason-create.md)|[timeOffReason](../resources/timeoffreason.md)|Create a new [timeOffReason](../resources/timeoffreason.md) object.|
|[Get timeOffReason](../api/timeoffreason-get.md)|[timeOffReason](../resources/timeoffreason.md)|Read the properties and relationships of a [timeOffReason](../resources/timeoffreason.md) object.|
|[Update timeOffReason](../api/timeoffreason-update.md)|[timeOffReason](../resources/timeoffreason.md)|Update the properties of a [timeOffReason](../resources/timeoffreason.md) object.|
|[Delete timeOffReason](../api/timeoffreason-delete.md)|None|Deletes a [timeOffReason](../resources/timeoffreason.md) object.|
|[stageForDeletion](../api/timeoffreason-stagefordeletion.md)|None|**TODO: Add Description**|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md).|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md).|
|displayName|String|**TODO: Add Description**|
|iconType|timeOffReasonIconType|**TODO: Add Description**. The possible values are: `none`, `car`, `calendar`, `running`, `plane`, `firstAid`, `doctor`, `notWorking`, `clock`, `juryDuty`, `globe`, `cup`, `phone`, `weather`, `umbrella`, `piggyBank`, `dog`, `cake`, `trafficCone`, `pin`, `sunny`, `unknownFutureValue`.|
|id|String|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md).|
|isActive|Boolean|**TODO: Add Description**|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md).|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [changeTrackedEntity](../resources/changetrackedentity.md).|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.timeOffReason",
  "baseType": "Microsoft.Teams.Shifts.changeTrackedEntity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.timeOffReason",
  "id": "String (identifier)",
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
