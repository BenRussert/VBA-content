---
title: Presentations.Count Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: e9f4d85f-4ba3-6c07-353d-79bbf39f91da
---


# Presentations.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **Presentations** object.


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


[Presentations Object](presentations-object-powerpoint.md)

