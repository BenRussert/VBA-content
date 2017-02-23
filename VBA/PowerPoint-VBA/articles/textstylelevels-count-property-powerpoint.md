---
title: TextStyleLevels.Count Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: ec2c4c53-482d-725a-5d86-3869d55dda38
---


# TextStyleLevels.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **TextStyleLevels** object.


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


[TextStyleLevels Object](textstylelevels-object-powerpoint.md)

