---
title: AutoCorrect Object (Excel)
keywords: vbaxl10.chm544072
f1_keywords:
- vbaxl10.chm544072
ms.prod: EXCEL
api_name:
- Excel.AutoCorrect
ms.assetid: 2594722a-2ff9-7175-4d35-0da0ad413b0d
---


# AutoCorrect Object (Excel)

Contains Microsoft Excel AutoCorrect attributes (capitalization of names of days, correction of two initial capital letters, automatic correction list, and so on).


## Example

Use the  **[AutoCorrect](application-autocorrect-property-excel.md)** property to return the **AutoCorrect** object. The following example sets Microsoft Excel to correct words that begin with two initial capital letters.


```vb
With Application.AutoCorrect 
 .TwoInitialCapitals = True 
 .ReplaceText = True 
End With
```


## See also


#### Other resources



[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)

