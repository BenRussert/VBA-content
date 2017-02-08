---
title: Range.Sentences Property (Word)
keywords: vbawd10.chm157155380
f1_keywords:
- vbawd10.chm157155380
ms.prod: WORD
api_name:
- Word.Range.Sentences
ms.assetid: fe870f13-d09f-efbf-1d2f-745f2c318c28
---


# Range.Sentences Property (Word)

Returns a  **Sentences** collection that represents all the sentences in the range. Read-only.


## Syntax

 _expression_ . **Sentences**

 _expression_ A variable that represents a **[Range](range-object-word.md)** object.


## Remarks

For information about returning a single member of a collection, see [Returning a Single Object from a Collection](http://msdn.microsoft.com/library/returning-a-single-object-from-a-collection%28Office.15%29.aspx).


## Example

This example displays the number of sentences in the first paragraph in the active document.


```vb
MsgBox ActiveDocument.Paragraphs(1).Range _ 
 .Sentences.Count &; " sentences"
```


## See also


#### Concepts


[Range Object](range-object-word.md)

