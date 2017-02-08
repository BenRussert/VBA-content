---
title: Selection.Comments Property (Word)
keywords: vbawd10.chm158662712
f1_keywords:
- vbawd10.chm158662712
ms.prod: WORD
api_name:
- Word.Selection.Comments
ms.assetid: 8f6fda0e-7070-eb42-3e1b-3a2a0654b330
---


# Selection.Comments Property (Word)

Returns a  **[Comments](comments-object-word.md)** collection that represents all the comments in the specified. Read-only.


## Syntax

 _expression_ . **Comments**

 _expression_ A variable that represents a **[Selection](selection-object-word.md)** object.


## Remarks

For information about returning a single member of a collection, see [Returning an Object from a Collection](http://msdn.microsoft.com/library/returning-an-object-from-a-collection-word%28Office.15%29.aspx).


## Example

This example adds a comment to the selected text.


```vb
ActiveDocument.ActiveWindow.View.ShowHiddenText = True 
Selection.Comments.Add Range:=Selection.Range, Text:="Approved"
```


## See also


#### Concepts


[Selection Object](selection-object-word.md)

