---
title: Series.Smooth Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: fff72f72-25f3-801c-67eb-b801102c8aed
---


# Series.Smooth Property (PowerPoint)

 **True** if curve smoothing is enabled for the line chart or scatter chart. Read/write **Boolean**.


## Syntax

 _expression_. **Smooth**

 _expression_ A variable that represents a **[Series](series-object-powerpoint.md)** object.


## Remarks

This property applies only to line and scatter charts. 


## Example




 **Note**  Although the following code applies to Microsoft Word, you can readily modify it to apply to PowerPoint.

The following example enables curve smoothing for series one for the first chart in the active document. You should run the example on a 2-D line chart.




```vb
With ActiveDocument.InlineShapes(1)

    If .HasChart Then

        .Chart.SeriesCollection(1).Smooth = True

    End If

End With
```


