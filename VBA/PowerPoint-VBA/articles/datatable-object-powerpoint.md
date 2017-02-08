---
title: DataTable Object (PowerPoint)
keywords: vbapp10.chm698000
f1_keywords:
- vbapp10.chm698000
ms.prod: POWERPOINT
ms.assetid: eaa7cdda-e374-7d19-47a6-87e4458fc244
---


# DataTable Object (PowerPoint)

Represents a chart data table.


## Example




 **Note**  Although the following code applies to Microsoft Word, you can readily modify it to apply to PowerPoint.

Use the  **[DataTable](chart-datatable-property-powerpoint.md)** property to return a **DataTable** object. The following example adds a data table with an outline border to embedded chart one.




```vb
With ActiveDocument.InlineShapes(1)

    If .HasChart Then

        .Chart.HasDataTable = True

        .Chart.DataTable.HasBorderOutline = True

    End If

End With
```


## See also


#### Concepts


[PowerPoint Object Model Reference](object-model-powerpoint-vba-reference.md)

