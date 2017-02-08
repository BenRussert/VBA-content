---
title: DocumentWindows.Count Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: d659a980-cc23-c805-6084-4c724c0bc6cd
---


# DocumentWindows.Count Property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

 _expression_. **Count**

 _expression_ A variable that represents a **DocumentWindows** object.


### Return Value

Long


## Remarks

If your Visual Studio solution includes the  **Microsoft.Office.Interop.PowerPoint** reference, this property maps to the following types:


-  **Microsoft.Office.Interop.PowerPoint.DocumentWindows.Count**
    

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



[DocumentWindows Object](documentwindows-object-powerpoint.md)

