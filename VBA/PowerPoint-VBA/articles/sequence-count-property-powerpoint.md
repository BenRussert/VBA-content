---
title: Sequence.Count Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: b3f02a35-309d-768c-dc76-bd0ef84261cc
---


# Sequence.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **Sequence** object.


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


[Sequence Object](sequence-object-powerpoint.md)

