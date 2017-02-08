---
title: SlideRange.Copy Method (PowerPoint)
keywords: vbapp10.chm532013
f1_keywords:
- vbapp10.chm532013
ms.prod: POWERPOINT
ms.assetid: d781370d-8107-efaa-77ea-a7f1aa58737b
---


# SlideRange.Copy Method (PowerPoint)

Copies the specified object to the Clipboard.


## Syntax

 _expression_. **Copy**

 _expression_ A variable that represents a **SlideRange** object.


## Remarks

Use the  **Paste** method to paste the contents of the Clipboard.


## Example

This example copies slide one in the active presentation to the Clipboard.


```vb
ActivePresentation.Slides(1).Copy
```


## See also


#### Concepts


[SlideRange Object](sliderange-object-powerpoint.md)

