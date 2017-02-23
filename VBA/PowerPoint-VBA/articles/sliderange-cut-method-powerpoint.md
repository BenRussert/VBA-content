---
title: SlideRange.Cut Method (PowerPoint)
keywords: vbapp10.chm532012
f1_keywords:
- vbapp10.chm532012
ms.prod: POWERPOINT
ms.assetid: 91d80a2b-e67a-290b-cb41-6bbeeb467d1b
---


# SlideRange.Cut Method (PowerPoint)

Deletes the specified object and places it on the Clipboard.


## Syntax

 _expression_. **Cut**

 _expression_ A variable that represents a **SlideRange** object.


## Example

This example deletes shapes one and two from slide one in the active presentation, places copies of them on the Clipboard, and then pastes the copies onto slide two.


```vb
With ActivePresentation

    .Slides(1).Shapes.Range(Array(1, 2)).Cut

    .Slides(2).Shapes.Paste

End With
```


## See also


#### Concepts


[SlideRange Object](sliderange-object-powerpoint.md)

