---
title: Slide.Design Property (PowerPoint)
keywords: vbapp10.chm531029
f1_keywords:
- vbapp10.chm531029
ms.prod: POWERPOINT
ms.assetid: bac64534-92f7-5611-db7e-501504e577e1
---


# Slide.Design Property (PowerPoint)

Returns a  **Design** object representing a design.


## Syntax

 _expression_. **Design**

 _expression_ A variable that represents a **Slide** object.


### Return Value

Design


## Example

The following example adds a title master.


```vb
Sub AddDesignMaster

    ActivePresentation.Slides(1).Design.AddTitleMaster

End Sub
```


## See also


#### Concepts


[Slide Object](slide-object-powerpoint.md)

