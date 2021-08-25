---
title: "shiftAvailability resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# shiftAvailability resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|recurrence|[patternedRecurrence](../resources/patternedrecurrence.md)|**TODO: Add Description**|
|timeSlots|[timeRange](../resources/timerange.md) collection|**TODO: Add Description**|
|timeZone|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.shiftAvailability"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.shiftAvailability",
  "recurrence": {
    "@odata.type": "microsoft.graph.patternedRecurrence"
  },
  "timeZone": "String",
  "timeSlots": [
    {
      "@odata.type": "microsoft.graph.timeRange"
    }
  ]
}
```
