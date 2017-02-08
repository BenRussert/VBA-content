---
title: SlicerCacheLevels Object (Excel)
keywords: vbaxl10.chm898072
f1_keywords:
- vbaxl10.chm898072
ms.prod: EXCEL
api_name:
- Excel.SlicerCacheLevels
ms.assetid: 6b1139a5-e81d-e11d-b4f5-f5d0fed24bf7
---


# SlicerCacheLevels Object (Excel)

Represents the collection of hierarchy levels for the OLAP data source that is filtered by a slicer.


## Remarks

When a slicer is used to filter an OLAP data source, its parent slicer cache can contain multiple hierarchy levels from the data source. Use the  **SlicerCacheLevels** collection of the parent **[SlicerCache](slicercache-object-excel.md)** object to access the **[SlicerCacheLevel](slicercachelevel-object-excel.md)** objects that represent these hierarchy levels. This collection is not accessible for non-OLAP data sources.


## Example

The following code example retrieves a  **SlicerCacheLevel** object that represents the Country level of the Customer Geography hierarchy from the **SlicerCacheLevel** collection of the Country slicer.


```vb
ActiveWorkbook.SlicerCaches("Slicer_Customer_Geography"). _ 
 SlicerCacheLevels("[Customer].[Customer Geography].[Country]")
```


## See also


#### Other resources


[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)


