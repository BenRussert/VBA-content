---
title: DataLabels.ShowSeriesName Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: fa069801-8725-786d-6a45-f38bf5aeb61c
---


# DataLabels.ShowSeriesName Property (PowerPoint)

 **True** to show the series name for the data labels on a chart. **False** to hide the name. Read/write **Boolean**.


## Syntax

 _expression_. **ShowSeriesName**

 _expression_ A variable that represents a **[DataLabels](datalabels-object-powerpoint.md)** object.


## Example




 **Note**  Although the following code applies to Microsoft Word, you can readily modify it to apply to PowerPoint.

The following example enables the series name to be shown for the data labels of the first series on the first chart.




```vb
With ActiveDocument.InlineShapes(1)
    If .HasChart Then
        .Chart.SeriesCollection(1).DataLabels. _
            ShowSeriesName = True
    End If
End With
```


## See also


#### Concepts


[DataLabels Object](datalabels-object-powerpoint.md)

