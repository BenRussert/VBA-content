---
title: Application.FileValidation Property (PowerPoint)
keywords: vbapp10.chm502069
f1_keywords:
- vbapp10.chm502069
ms.prod: POWERPOINT
ms.assetid: 90cc8bff-df3b-7a57-adcc-bbfb9c677468
---


# Application.FileValidation Property (PowerPoint)

Returns or sets a value that indicates how PowerPoint will validate files before opening them. Read/write


## Syntax

 _expression_. **FileValidation**

 _expression_ A variable that represents an **Application** object.


### Return Value

 **[MsoFileValidationMode](http://msdn.microsoft.com/library/msofilevalidationmode-enumeration-office%28Office.15%29.aspx)**


## Remarks

Files that do not pass validation will be opened in a  **Protected View** window. If you set the **FileValidation** property, that setting will remain in effect for the entire session during which the application is open.


## See also


#### Concepts


[Application Object](application-object-powerpoint.md)

