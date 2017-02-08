---
title: Floor Object (Word)
keywords: vbawd10.chm702
f1_keywords:
- vbawd10.chm702
ms.prod: WORD
api_name:
- Word.Floor
ms.assetid: 01d277eb-501b-09e5-65b8-83506c76ac05
---


# Floor Object (Word)

Represents the floor of a 3-D chart.


## Example

Use the  **[Floor](chart-floor-property-word.md)** property to return the **Floor** object. The following example sets the floor color for embedded chart one to cyan. The example will fail if the chart is not a 3-D chart.


```vb
With ActiveDocument.InlineShapes(1) 
 If .HasChart Then 
 .Chart.Floor.Interior.Color = RGB(0, 255, 255) 
 End If 
End With 

```


## See also


#### Other resources


[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)


