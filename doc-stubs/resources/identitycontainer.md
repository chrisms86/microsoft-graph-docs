---
title: "identityContainer resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# identityContainer resource type

Namespace: microsoft.graph



**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List identityContainers](../api/identitycontainer-list.md)|[identityContainer](../resources/identitycontainer.md) collection|Get a list of the [identityContainer](../resources/identitycontainer.md) objects and their properties.|
|[Create identityContainer](../api/identitycontainer-create.md)|[identityContainer](../resources/identitycontainer.md)|Create a new [identityContainer](../resources/identitycontainer.md) object.|
|[Get identityContainer](../api/identitycontainer-get.md)|[identityContainer](../resources/identitycontainer.md)|Read the properties and relationships of an [identityContainer](../resources/identitycontainer.md) object.|
|[Update identityContainer](../api/identitycontainer-update.md)|[identityContainer](../resources/identitycontainer.md)|Update the properties of an [identityContainer](../resources/identitycontainer.md) object.|
|[Delete identityContainer](../api/identitycontainer-delete.md)|None|Deletes an [identityContainer](../resources/identitycontainer.md) object.|
|[List continuousAccessEvaluationPolicy](../api/identitycontainer-list-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md) collection|Get the continuousAccessEvaluationPolicy resources from the continuousAccessEvaluationPolicy navigation property.|
|[Create continuousAccessEvaluationPolicy](../api/identitycontainer-post-continuousaccessevaluationpolicy.md)|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|Create a new continuousAccessEvaluationPolicy object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|conditionalAccess|[conditionalAccessRoot](../resources/conditionalaccessroot.md)|**TODO: Add Description**|
|continuousAccessEvaluationPolicy|[continuousAccessEvaluationPolicy](../resources/continuousaccessevaluationpolicy.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.identityContainer",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.identityContainer"
}
```
