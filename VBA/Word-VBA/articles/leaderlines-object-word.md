---
title: LeaderLines Object (Word)
keywords: vbawd10.chm3170
f1_keywords:
- vbawd10.chm3170
ms.prod: WORD
api_name:
- Word.LeaderLines
ms.assetid: ea8805d1-eec7-eaf6-1046-967e28d6bc56
---


# LeaderLines Object (Word)

Represents leader lines on a chart. Leader lines connect data labels to data points.


## Remarks

 This object is not a collection; there is no object that represents a single leader line.

This object applies only to pie charts.


## Example

Use the  **[LeaderLines](series-leaderlines-property-word.md)** property to return the **LeaderLines** object. The following example adds data labels and blue leader lines to series one on the first chart in the active document. If no leader lines are visible, this example code will fail. In this situation, you can manually drag one of the data labels away from the pie chart to make a leader line show up.


```vb
With ActiveDocument.InlineShapes(1) 
 If .HasChart Then 
 With .Chart.SeriesCollection(1) 
 .HasDataLabels = True 
 .DataLabels.Position = xlLabelPositionBestFit 
 .HasLeaderLines = True 
 .LeaderLines.Border.ColorIndex = 5 
 End With 
 End If 
End With
```


## See also


#### Other resources



[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)

