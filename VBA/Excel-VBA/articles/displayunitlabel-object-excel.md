---
title: DisplayUnitLabel Object (Excel)
keywords: vbaxl10.chm672072
f1_keywords:
- vbaxl10.chm672072
ms.prod: EXCEL
api_name:
- Excel.DisplayUnitLabel
ms.assetid: 522dea6a-114f-3e0f-f8ae-6c2667c733dd
---


# DisplayUnitLabel Object (Excel)

Represents a unit label on an axis in the specified chart.


## Remarks

 Unit labels are useful for charting large values—for example, in the millions or billions. You can make the chart more readable by using a single unit label instead of large numbers at each tick mark.


## Example

Use the  **[DisplayUnitLabel](axis-displayunitlabel-property-excel.md)** property to return the **DisplayUnitLabel** object. The following example sets the display label caption to "Millions" on the value axis in Chart1, and then it turns off automatic font scaling.


```vb
With Charts("Chart1").Axes(xlValue) 
 .DisplayUnit = xlMillions 
 .HasDisplayUnitLabel = True 
 With .DisplayUnitLabel 
 .Caption = "Millions" 
 .AutoScaleFont = False 
 End With 
End With
```


## See also


#### Other resources


[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)


