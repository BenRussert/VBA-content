---
title: Effect.DisplayName Property (PowerPoint)
keywords: vbapp10.chm652015
f1_keywords:
- vbapp10.chm652015
ms.prod: POWERPOINT
ms.assetid: 1c8c7a78-5b09-a94e-880e-d82311cc5ee9
---


# Effect.DisplayName Property (PowerPoint)

Returns the name of an animation effect. Read-only.


## Syntax

 _expression_. **DisplayName**

 _expression_ A variable that represents a **Effect** object.


### Return Value

String


## Example

This example displays the name for the first animation sequence of the first slide's main animation sequence timeline.


```vb
Sub DisplayEffectName()

    Dim effMain As Effect

    Set effMain = ActivePresentation.Slides(1).TimeLine.MainSequence(1)

    MsgBox effMain.DisplayName

End Sub
```


## See also


#### Concepts



[Effect Object](effect-object-powerpoint.md)

