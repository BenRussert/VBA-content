---
title: Application.LanguageSettings Property (Excel)
keywords: vbaxl10.chm133251
f1_keywords:
- vbaxl10.chm133251
ms.prod: EXCEL
api_name:
- Excel.Application.LanguageSettings
ms.assetid: 631879d9-f43f-4985-32d0-77bf314956eb
---


# Application.LanguageSettings Property (Excel)

Returns the  **[LanguageSettings](http://msdn.microsoft.com/library/languagesettings-object-office%28Office.15%29.aspx)** object, which contains information about the language settings in Microsoft Excel. Read-only.


## Syntax

 _expression_ . **LanguageSettings**

 _expression_ A variable that represents an **Application** object.


## Example

This example returns the language identifier for the language you selected when you installed Microsoft Excel.


```vb
Set objLangSet = Application.LanguageSettings 
MsgBox objLangSet.LanguageID(msoLanguageIDInstall)
```


## See also


#### Concepts


[Application Object](application-object-excel.md)

