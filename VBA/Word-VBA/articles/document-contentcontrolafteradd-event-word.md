---
title: Document.ContentControlAfterAdd Event (Word)
keywords: vbawd10.chm4001010
f1_keywords:
- vbawd10.chm4001010
ms.prod: WORD
api_name:
- Word.Document.ContentControlAfterAdd
ms.assetid: 9a19d147-76bd-eb92-5844-c56b2d6eae7c
---


# Document.ContentControlAfterAdd Event (Word)

Occurs after adding a content control to a document.


## Syntax

Private Sub  _expression_ _**ContentControlAfterAdd**( **_NewContentControl_** , **_InUndoRedo_** )

 _expression_ An expression that returns a **[Document](document-object-word.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _NewContentControl_|Required| **ContentControl**|The content control being added.|
| _InUndoRedo_|Required| **Boolean**|Specifies whether the addition is taking place as part an undo or redo action.|

## Remarks

For information about using events with the  **Document** object, see[Using Events with the Document Object](http://msdn.microsoft.com/library/using-events-with-the-document-object%28Office.15%29.aspx).


## See also


#### Concepts


[Document Object](document-object-word.md)

