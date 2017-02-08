---
title: PictureFormat.Crop Property (Word)
keywords: vbawd10.chm164298861
f1_keywords:
- vbawd10.chm164298861
ms.prod: WORD
api_name:
- Word.PictureFormat.Crop
ms.assetid: 431cc1a8-dd05-d813-6ba6-a6a78ee2472b
---


# PictureFormat.Crop Property (Word)

Returns or sets a [Crop](http://msdn.microsoft.com/library/crop-object-office%28Office.15%29.aspx) object that represents an image cropping. Read/write.


## Syntax

 _expression_ . **Crop**

 _expression_ An expression that returns a **PictureFormat** object.


## Remarks

Use the  **Crop** property to work with an image cropping.


## Example

The following code example creates a cropping of the first image in the active document and sets the crop height to 100 point.


```vb
Dim myInlineShape As InlineShape 
Dim myCrop As Crop 
 
Set myInlineShape = ActiveDocument.InlineShapes(1) 
Set myCrop = myInlineShape.PictureFormat.Crop 
 
myCrop.ShapeHeight = 100
```


## See also


#### Concepts


[PictureFormat Object](pictureformat-object-word.md)

