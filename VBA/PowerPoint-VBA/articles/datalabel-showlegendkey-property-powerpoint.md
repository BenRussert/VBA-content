---
title: DataLabel.ShowLegendKey Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: 1cd5f3a4-056d-ccb6-140f-08ec1e416eda
---


# DataLabel.ShowLegendKey Property (PowerPoint)

 **True** if the data label legend key is visible. Read/write **Boolean**.


## Syntax

 _expression_. **ShowLegendKey**

 _expression_ A variable that represents a **[DataLabel](datalabel-object-powerpoint.md)** object.


## Example




 **Note**  Although the following code applies to Microsoft Word, you can readily modify it to apply to PowerPoint.

The following example sets the data labels for series one of the first chart in the active document to show values and the legend key.




```vb
With ActiveDocument.InlineShapes(1)
    If .HasChart Then
        .Chart.SeriesCollection(1).DataLabels. _
            ShowLegendKey = True
        .Chart.SeriesCollection(1).DataLabels.Type = xlShowValue
    End If
End With
```


## See also


#### Concepts


[DataLabel Object](datalabel-object-powerpoint.md)

