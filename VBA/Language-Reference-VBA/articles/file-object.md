---
title: File Object
keywords: vblr6.chm2181925
f1_keywords:
- vblr6.chm2181925
ms.prod: MULTIPLEPRODUCTS
ms.assetid: 0c8ff620-e1fe-e588-c2a6-d76adf372bbe
---


# File Object



 **Description**
Provides access to all the properties of a file.
 **Remarks**
The following code illustrates how to obtain a  **File** object and how to view one of its properties.



```vb
Sub ShowFileInfo(filespec)
    Dim fs, f, s
    Set fs = CreateObject("Scripting.FileSystemObject")
    Set f = fs.GetFile(filespec)
    s = f.DateCreated
    MsgBox s
End Sub
```


