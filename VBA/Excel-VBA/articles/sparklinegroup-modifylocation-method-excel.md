---
title: SparklineGroup.ModifyLocation Method (Excel)
keywords: vbaxl10.chm871079
f1_keywords:
- vbaxl10.chm871079
ms.prod: EXCEL
api_name:
- Excel.SparklineGroup.ModifyLocation
ms.assetid: 8f6ca2cb-b0cc-a0bf-efc0-ee30ca3888e6
---


# SparklineGroup.ModifyLocation Method (Excel)

Sets the associated  **[Range](http://msdn.microsoft.com/library/range-object%28Office.15%29.aspx)** object to modify the location of the sparkline group.


## Syntax

 _expression_ . **ModifyLocation**( **_Location_** )

 _expression_ A variable that represents a **[SparklineGroup](sparklinegroup-object-excel.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Location_|Required| **Range**|The  **Range** that represents the location of the sparkline group.|

### Return Value

Nothing


## Example

This example selects a sparkline group in the location A1:A4 and changes the location to equal A10:A14.


```vb
Range("A1:A4").Select 
ActiveCell.SparklineGroups.Item(1).ModifyLocation Range("$A$10:$A$14")
```


## See also


#### Concepts


[SparklineGroup Object](sparklinegroup-object-excel.md)

