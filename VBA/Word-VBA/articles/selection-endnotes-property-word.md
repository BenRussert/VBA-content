---
title: Selection.Endnotes Property (Word)
keywords: vbawd10.chm158662711
f1_keywords:
- vbawd10.chm158662711
ms.prod: WORD
api_name:
- Word.Selection.Endnotes
ms.assetid: fea9ea39-4091-cccd-9025-36be2e4b95ff
---


# Selection.Endnotes Property (Word)

Returns an  **[Endnotes](endnotes-object-word.md)** collection that represents all the endnotes conatined within a selection. Read-only.


## Syntax

 _expression_ . **Endnotes**

 _expression_ A variable that represents a **[Selection](selection-object-word.md)** object.


## Remarks

For information about returning a single member of a collection, see [Returning an Object from a Collection](http://msdn.microsoft.com/library/returning-an-object-from-a-collection-word%28Office.15%29.aspx).


## Example

This example positions the endnotes in the selection at the end of the document and formats the endnote reference marks as lowercase roman numerals.


```vb
With Selection.Endnotes 
 .Location = wdEndOfDocument 
 .NumberStyle = wdNoteNumberStyleLowercaseRoman 
End With
```


## See also


#### Concepts


[Selection Object](selection-object-word.md)

