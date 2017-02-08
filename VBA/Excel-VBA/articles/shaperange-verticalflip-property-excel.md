---
title: ShapeRange.VerticalFlip Property (Excel)
keywords: vbaxl10.chm640119
f1_keywords:
- vbaxl10.chm640119
ms.prod: EXCEL
api_name:
- Excel.ShapeRange.VerticalFlip
ms.assetid: 43ecbc06-a16b-821f-b7c9-c66fcfad7a79
---


# ShapeRange.VerticalFlip Property (Excel)

 **True** if the specified shape is flipped around the vertical axis. Read-only **[MsoTriState](http://msdn.microsoft.com/library/msotristate-enumeration-office%28Office.15%29.aspx)** .


## Syntax

 _expression_ . **VerticalFlip**

 _expression_ A variable that represents a **ShapeRange** object.


## Example

This example restores each shape on  `myDocument` to its original state if it's been flipped horizontally or vertically.


```vb
Set myDocument = Worksheets(1) 
For Each s In myDocument.Shapes 
    If s.HorizontalFlip Then s.Flip msoFlipHorizontal 
    If s.VerticalFlip Then s.Flip msoFlipVertical 
Next
```


## See also


#### Concepts


[ShapeRange Object](shaperange-object-excel.md)

