---
title: SlideShowView.CurrentShowPosition Property (PowerPoint)
keywords: vbapp10.chm513027
f1_keywords:
- vbapp10.chm513027
ms.prod: POWERPOINT
ms.assetid: 390eb2c3-059f-f7e9-e91a-0e8cf9a0ddff
---


# SlideShowView.CurrentShowPosition Property (PowerPoint)

Returns the position of the current slide within the slide show that is showing in the specified view. Read-only.


## Syntax

 _expression_. **CurrentShowPosition**

 _expression_ A variable that represents a **SlideShowView** object.


### Return Value

Long


## Remarks

If the specified view contains a custom show, the  **CurrentShowPosition** property returns the position of the current slide within the custom show, not the position of the current slide within the entire presentation.


## Example

This example sets a variable to the position of the current slide in the slide show running in slide show window one.


```
lastSlideSeen = SlideShowWindows(1).View.CurrentShowPosition
```


## See also


#### Concepts


[SlideShowView Object](slideshowview-object-powerpoint.md)

