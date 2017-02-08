---
title: DocumentWindow.Panes Property (PowerPoint)
keywords: vbapp10.chm511023
f1_keywords:
- vbapp10.chm511023
ms.prod: POWERPOINT
ms.assetid: 1f26709d-8414-ee89-29d8-588c6787611a
---


# DocumentWindow.Panes Property (PowerPoint)

Returns a  **[Panes](panes-object-powerpoint.md)** collection that represents the panes in the document window. Read-only.


## Syntax

 _expression_. **Panes**

 _expression_ A variable that represents a **DocumentWindow** object.


### Return Value

Panes


## Example

This example tests for the number of panes in the active window. If the value is one, indicating any view other that normal view, normal view is activated.


```
If ActiveWindow.Panes.Count = 1 Then

    ActiveWindow.ViewType = ppViewNormal

End If
```


## See also


#### Concepts


[DocumentWindow Object](documentwindow-object-powerpoint.md)


