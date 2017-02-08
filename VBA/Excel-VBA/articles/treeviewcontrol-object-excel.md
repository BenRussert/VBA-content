---
title: TreeviewControl Object (Excel)
keywords: vbaxl10.chm665072
f1_keywords:
- vbaxl10.chm665072
ms.prod: EXCEL
api_name:
- Excel.TreeviewControl
ms.assetid: 32a5e647-14e0-d2a8-05f7-a01db9250a88
---


# TreeviewControl Object (Excel)

Represents the hierarchical member-selection control of a cube field.


## Remarks

You use this object primarily for macro recording; it is not intended for any other use.


## Example

Use the  **[TreeviewControl](cubefield-treeviewcontrol-property-excel.md)** property to return the **TreeviewControl** object. The following example sets the control to its "drilled" (expanded, or visible) status for the states of California and Maryland in the second PivotTable report on the active worksheet.


```vb
ActiveSheet.PivotTables("PivotTable2") _ 
 .CubeFields(1).TreeviewControl.Drilled = _ 
 Array(Array("", ""), _ 
 Array("[state].[states].[CA]", _ 
 "[state].[states].[MD]")) 

```


## See also


#### Other resources



[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)

