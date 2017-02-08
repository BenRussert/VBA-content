---
title: Walls Object (Word)
keywords: vbawd10.chm384
f1_keywords:
- vbawd10.chm384
ms.prod: WORD
api_name:
- Word.Walls
ms.assetid: e98c7218-b944-12bb-caf9-daecee4b6c0c
---


# Walls Object (Word)

Represents the walls of a 3-D chart. 


## Remarks

This object is not a collection. There is no object that represents a single wall; you must return all the walls as a unit.


## Example

Use the  **[Walls](chart-walls-property-word.md)** property to return the **Walls** object. The following example sets the pattern on the walls for the first chart in the active document. If the chart is not a 3-D chart, this example will fail.


```vb
With ActiveDocument.InlineShapes(1) 
 If .HasChart Then 
 .Chart.Walls.Interior.Pattern = xlGray75 
 End If 
End With
```


## See also


#### Other resources



[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)

