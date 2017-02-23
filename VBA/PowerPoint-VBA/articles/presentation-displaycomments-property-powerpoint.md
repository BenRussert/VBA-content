---
title: Presentation.DisplayComments Property (PowerPoint)
keywords: vbapp10.chm583042
f1_keywords:
- vbapp10.chm583042
ms.prod: POWERPOINT
ms.assetid: b241151a-82b5-7188-a8b8-a4a04fc37165
---


# Presentation.DisplayComments Property (PowerPoint)

Determines whether comments are displayed in the specified presentation. Read/write.


## Syntax

 _expression_. **DisplayComments**

 _expression_ A variable that represents a **Presentation** object.


### Return Value

MsoTriState


## Remarks

The value returned by the  **DisplayComments** property can be one of these **MsoTriState** constants.



|**Constant**|**Description**|
|:-----|:-----|
|**msoFalse**|Comments are not displayed in the specified presentation.|
|**msoTrue**| Comments are displayed in the specified presentation.|

## Example

This example hides comments in the active presentation.


```vb
ActivePresentation.DisplayComments = msoFalse
```


## See also


#### Concepts


[Presentation Object](presentation-object-powerpoint.md)

