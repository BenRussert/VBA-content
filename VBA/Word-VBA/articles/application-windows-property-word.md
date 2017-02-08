---
title: Application.Windows Property (Word)
keywords: vbawd10.chm158334978
f1_keywords:
- vbawd10.chm158334978
ms.prod: WORD
api_name:
- Word.Application.Windows
ms.assetid: 860d9e12-4c02-be1f-64a7-ef0305881854
---


# Application.Windows Property (Word)

Returns a  **[Windows](windows-object-word.md)** collection that represents all document windows. Read-only.


## Syntax

 _expression_ . **Windows**

 _expression_ A variable that represents an **[Application](application-object-word.md)** object.


## Remarks

The collection corresponds to the window names that appear at the bottom of the Window menu. For information about returning a single member of a collection, see [Returning an Object from a Collection](http://msdn.microsoft.com/library/returning-an-object-from-a-collection-word%28Office.15%29.aspx).


## Example

This example arranges all open windows so that they don't overlap.


```
Windows.Arrange ArrangeStyle:=wdTiled
```


## See also


#### Concepts


[Application Object](application-object-word.md)

