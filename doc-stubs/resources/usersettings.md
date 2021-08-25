---
title: "userSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# userSettings resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List userSettings](../api/usersettings-list.md)|[userSettings](../resources/usersettings.md) collection|Get a list of the [userSettings](../resources/usersettings.md) objects and their properties.|
|[Create userSettings](../api/usersettings-create.md)|[userSettings](../resources/usersettings.md)|Create a new [userSettings](../resources/usersettings.md) object.|
|[Get userSettings](../api/usersettings-get.md)|[userSettings](../resources/usersettings.md)|Read the properties and relationships of a [userSettings](../resources/usersettings.md) object.|
|[Update userSettings](../api/usersettings-update.md)|[userSettings](../resources/usersettings.md)|Update the properties of a [userSettings](../resources/usersettings.md) object.|
|[Delete userSettings](../api/usersettings-delete.md)|None|Deletes a [userSettings](../resources/usersettings.md) object.|
|[List shiftPreferences](../api/usersettings-list-shiftpreferences.md)|[shiftPreferences](../resources/shiftpreferences.md) collection|Get the shiftPreferences resources from the shiftPreferences navigation property.|
|[Create shiftPreferences](../api/usersettings-post-shiftpreferences.md)|[shiftPreferences](../resources/shiftpreferences.md)|Create a new shiftPreferences object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|shiftPreferences|[shiftPreferences](../resources/shiftpreferences.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.userSettings",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.userSettings"
}
```
