---
title: SlideRange.Count Property (PowerPoint)
keywords: vbapp10.chm532029
f1_keywords:
- vbapp10.chm532029
ms.prod: POWERPOINT
ms.assetid: ff280d05-41f1-fbdc-16c3-ae30a1102340
---


# SlideRange.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **SlideRange** object.


### Return Value

Long


## Example

This example closes all windows except the active window.


```vb
With Application.Windows

    For i = 2 To .Count

        .Item(2).Close

    Next

End With
```


## See also


#### Concepts


[SlideRange Object](sliderange-object-powerpoint.md)

