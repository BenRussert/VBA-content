---
title: Rectangles Object (Word)
ms.prod: WORD
api_name:
- Word.Rectangles
ms.assetid: c1de5e7f-13b1-e35a-d9f1-9a8f1246e2e5
---


# Rectangles Object (Word)

A collection of  **Rectangle** objects in a page that represent portions of text and graphics. Use the **Rectangles** collection and related objects and properties for programmatically defining page layout in a document.


## Remarks

Use the  **Rectangles** property to return a **Rectangles** collection. The following example returns the **Rectangles** collection for the first page in the active document.


```vb
Dim objRectangles As Rectangles 
 
Set objRectangles = ActiveDocument.ActiveWindow _ 
 .Panes(1).Pages(1).Rectangles
```


## See also


#### Other resources



[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)

