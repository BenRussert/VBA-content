---
title: Range.SpellingErrors Property (Word)
keywords: vbawd10.chm157155644
f1_keywords:
- vbawd10.chm157155644
ms.prod: WORD
api_name:
- Word.Range.SpellingErrors
ms.assetid: 4b35a13d-2a5f-e9cd-0667-58aae00a48f1
---


# Range.SpellingErrors Property (Word)

Returns a  **ProofreadingErrors** collection that represents the words identified as spelling errors in the specified range. Read-only.


## Syntax

 _expression_ . **SpellingErrors**

 _expression_ A variable that represents a **[Range](range-object-word.md)** object.


## Remarks

For information about returning a single member of a collection, see [Returning a Single Object from a Collection](http://msdn.microsoft.com/library/returning-a-single-object-from-a-collection%28Office.15%29.aspx).


## Example

This example checks the specified range for spelling errors and displays each error found.


```vb
Set myErrors = ActiveDocument.Paragraphs(3).Range.SpellingErrors 
If myErrors.Count = 0 Then 
 Msgbox "No spelling errors found." 
Else 
 For Each myErr in myErrors 
 Msgbox myErr.Text 
 Next 
End If
```


## See also


#### Concepts


[Range Object](range-object-word.md)

