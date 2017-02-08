---
title: PrintRanges.Count Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: 4473e840-e8c7-c3ab-3fe8-d0770a1cd8a4
---


# PrintRanges.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **PrintRanges** object.


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


[PrintRanges Object](printranges-object-powerpoint.md)

