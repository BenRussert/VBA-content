---
title: Coauthoring.FavorServerEditsDuringMerge Property (PowerPoint)
keywords: vbapp10.chm731004
f1_keywords:
- vbapp10.chm731004
ms.prod: POWERPOINT
ms.assetid: 82c563c0-b3a0-18ca-5405-6aa786c4946a
---


# Coauthoring.FavorServerEditsDuringMerge Property (PowerPoint)

Gets or sets whether the merged document favors server-side edits when conflicts occur. Read/write.


## Syntax

 _expression_. **FavorServerEditsDuringMerge**

 _expression_ A variable that represents a **Coauthoring** object.


### Return Value

Boolean


## Remarks

 **FavorServerEditsDuringMerge** returns an error if the application is not already in merge mode. **True** to favor server-side edits. The default is **False**, which means that local client-side edits are favored.


## See also


#### Concepts


[Coauthoring Object](coauthoring-object-powerpoint.md)

