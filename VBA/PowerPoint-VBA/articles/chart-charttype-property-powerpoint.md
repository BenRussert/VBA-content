---
title: Chart.ChartType Property (PowerPoint)
ms.prod: POWERPOINT
ms.assetid: 5a806b77-1efd-fd3a-132f-f6e3afd7315d
---


# Chart.ChartType Property (PowerPoint)

Returns or sets the chart type. Read/write  **[XlChartType](http://msdn.microsoft.com/library/xlcharttype-enumeration-excel%28Office.15%29.aspx)**.


## Syntax

 _expression_. **ChartType**

 _expression_ A variable that represents a **[Chart](chart-object-powerpoint.md)** object.


## Remarks

Some chart types are not available for PivotChart reports.


## Example




 **Note**  Although the following code applies to Microsoft Word, you can readily modify it to apply to PowerPoint.

The following example sets the bubble size in chart group one to 200% of the default size if the chart is a 2-D bubble chart.




```vb
With ActiveDocument.InlineShapes(1).Chart 
    If .ChartType = xlBubble Then 
        .ChartGroups(1).BubbleScale = 200 
    End If 
End With
```


## See also


#### Concepts


[Chart Object](chart-object-powerpoint.md)

