---
title: Presentation.NoLineBreakBefore Property (PowerPoint)
keywords: vbapp10.chm583044
f1_keywords:
- vbapp10.chm583044
ms.prod: POWERPOINT
ms.assetid: d7f7f559-cf20-ef3f-60aa-122dc28da203
---


# Presentation.NoLineBreakBefore Property (PowerPoint)

Returns or sets the characters that cannot begin a line. Read/write.


## Syntax

 _expression_. **NoLineBreakBefore**

 _expression_ A variable that represents a **Presentation** object.


### Return Value

String


## Example

This example sets "!", ")", and "]" as characters that cannot begin a line.


```vb
With ActivePresentation

    .FarEastLineBreakLevel = ppFarEastLineBreakLevelCustom

    .NoLineBreakBefore =  "!)]"

End With
```


## See also


#### Concepts


[Presentation Object](presentation-object-powerpoint.md)

