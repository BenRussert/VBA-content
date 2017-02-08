---
title: SortFields Object (Excel)
keywords: vbaxl10.chm844072
f1_keywords:
- vbaxl10.chm844072
ms.prod: EXCEL
api_name:
- Excel.SortFields
ms.assetid: a9c83ea1-1cd9-1552-1f03-71bd92a2cc72
---


# SortFields Object (Excel)

The  **SortFields** collection is a collection of **SortField** objects. It allows developers to store a sort state on workbooks, lists, and autofilters.


## Remarks

The object contains properties to add, count, sort, and remove  **SortField** objects.


## Example


```
ActiveWorksheet.SortFields.Add Key:=Range("A1"), Order:=xlDescending 
ActiveWorksheet.SortFields.Add Key:=Range("B1"), Order:=xlDescending 
ActiveWorksheet.SortFields.Sort Header:=xlGuess 

```


## Methods



|**Name**|
|:-----|
|[Add](sortfields-add-method-excel.md)|
|[Clear](sortfields-clear-method-excel.md)|

## Properties



|**Name**|
|:-----|
|[Application](sortfields-application-property-excel.md)|
|[Count](sortfields-count-property-excel.md)|
|[Creator](sortfields-creator-property-excel.md)|
|[Item](sortfields-item-property-excel.md)|
|[Parent](sortfields-parent-property-excel.md)|

## See also


#### Other resources


[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)
