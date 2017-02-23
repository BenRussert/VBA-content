---
title: Application.ProtectedViewWindowBeforeEdit Event (PowerPoint)
keywords: vbapp10.chm621027
f1_keywords:
- vbapp10.chm621027
ms.prod: POWERPOINT
ms.assetid: 8cfd38bf-8336-0106-a170-1319bcea0eb8
---


# Application.ProtectedViewWindowBeforeEdit Event (PowerPoint)

Occurs immediately before editing is enabled on the document in the specified protected view window.


## Syntax

 _expression_. **ProtectedViewWindowBeforeEdit**( **_ProtViewWindow_**, **_Cancel_** )

 _expression_ A variable that represents an **Application** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _ProtViewWindow_|Required|**ProtectedViewWindow**|The protected view window that contains the document that is enabled for editing.|
| _Cancel_|Required|**Boolean**|**False** when the event occurs. If the event procedure sets this argument to **True**, editing is not enabled on the document.|

### Return Value

Nothing


## See also


#### Concepts


[Application Object](application-object-powerpoint.md)

