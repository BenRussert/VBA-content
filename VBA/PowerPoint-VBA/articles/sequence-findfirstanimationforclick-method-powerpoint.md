---
title: Sequence.FindFirstAnimationForClick Method (PowerPoint)
keywords: vbapp10.chm651007
f1_keywords:
- vbapp10.chm651007
ms.prod: POWERPOINT
ms.assetid: e1fb9fbe-394e-6765-e4ab-6850e540494b
---


# Sequence.FindFirstAnimationForClick Method (PowerPoint)

Returns an  **[Effect](effect-object-powerpoint.md)** object that represents the first animation started by the specified click number.


## Syntax

 _expression_. **FindFirstAnimationForClick**( **_click_** )

 _expression_ A variable that represents a **Sequence** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _click_|Required|**Long**|The specified click number.|

### Return Value

Effect


## Example

The following example finds the first animation for the first click of the first slide and changes the effect to a bounce.


```vb
Sub FindFirstAnimationClick()

    Dim sldFirst As Slide
    Dim effClick As Effect

    Set sldFirst = ActivePresentation.Slides(1)
    Set effClick = sldFirst.TimeLine.MainSequence _
        .FindFirstAnimationForClick(Click:=1)
    effClick.EffectType = msoAnimEffectBounce

End Sub
```


## See also


#### Concepts


[Sequence Object](sequence-object-powerpoint.md)

