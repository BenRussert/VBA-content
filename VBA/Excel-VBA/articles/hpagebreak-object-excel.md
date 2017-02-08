---
title: HPageBreak Object (Excel)
keywords: vbaxl10.chm158072
f1_keywords:
- vbaxl10.chm158072
ms.prod: EXCEL
api_name:
- Excel.HPageBreak
ms.assetid: 8fc96958-33ab-8251-f627-4769b5eab97f
---


# HPageBreak Object (Excel)

Represents a horizontal page break. 


## Remarks

The  **HPageBreak** object is a member of the **[HPageBreaks](hpagebreaks-object-excel.md)** collection.


 **Note**  There is a limit of 1026 horizontal page breaks per sheet.


## Example

Use  **[HPageBreaks](worksheets-hpagebreaks-property-excel.md)** ( _index_ ), where _index_ is the index number of the page break, to return an **HPageBreak** object. The following example changes the location of horizontal page break one.


```vb
Worksheets(1).HPageBreaks(1).Location = Worksheets(1).Range("e5")
```


## See also


#### Other resources


[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)


