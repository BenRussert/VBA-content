---
title: Template.CustomDocumentProperties Property (Word)
keywords: vbawd10.chm157941769
f1_keywords:
- vbawd10.chm157941769
ms.prod: WORD
api_name:
- Word.Template.CustomDocumentProperties
ms.assetid: b11e705f-7042-014c-4efc-2d2fba135ab2
---


# Template.CustomDocumentProperties Property (Word)

Returns a  **DocumentProperties** collection that represents all the custom document properties for the specified document.


## Syntax

 _expression_ . **CustomDocumentProperties**

 _expression_ Required. A variable that represents a **[Template](template-object-word.md)** object.


## Remarks

Use the  **BuiltInDocumentProperties** property to return the collection of built-in document properties. Properties of type **msoPropertyTypeString** cannot exceed 255 characters in length.

For information about returning a single member of a collection, see [Returning an Object from a Collection](http://msdn.microsoft.com/library/returning-an-object-from-a-collection-word%28Office.15%29.aspx).


## See also


#### Concepts


[Template Object](template-object-word.md)

