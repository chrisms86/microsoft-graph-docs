---
title: "workforceIntegrationEncryption resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workforceIntegrationEncryption resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|protocol|workforceIntegrationEncryptionProtocol|**TODO: Add Description**. The possible values are: `sharedSecret`, `unknownFutureValue`.|
|secret|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.workforceIntegrationEncryption"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workforceIntegrationEncryption",
  "protocol": "String",
  "secret": "String"
}
```
