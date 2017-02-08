---
title: Application.EPostageInsert Event (Word)
keywords: vbawd10.chm4000015
f1_keywords:
- vbawd10.chm4000015
ms.prod: WORD
api_name:
- Word.Application.EPostageInsert
ms.assetid: 33dfd513-7782-0877-7bf9-1b23cf995d4b
---


# Application.EPostageInsert Event (Word)

Occurs when a user inserts electronic postage into a document.


## Syntax

 _expression_ . **Private Sub object_EPostageInsert**( **_ByVal Doc As Document_** )

 _expression_ A variable that represents an **[Application](application-object-word.md)** object that has been declared with events in a class module. For information about using events with the **Application** object, see[Using Events with the Application Object](http://msdn.microsoft.com/library/using-events-with-the-application-object-word%28Office.15%29.aspx).


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Doc_|Required| **Document**|The name of the document to which to add electronic postage.|

## Example

This example displays a message when electronic postage is inserted into a document.


```vb
Private Sub AppWord_EPostageInsert(ByVal Doc As Document) 
 MsgBox "You just inserted electronic postage into your document." 
End Sub
```


## See also


#### Concepts


[Application Object](application-object-word.md)

