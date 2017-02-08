---
title: SoundEffect.ImportFromFile Method (PowerPoint)
keywords: vbapp10.chm540005
f1_keywords:
- vbapp10.chm540005
ms.prod: POWERPOINT
ms.assetid: 78a56002-a854-cadb-c86f-806bfbd41f2b
---


# SoundEffect.ImportFromFile Method (PowerPoint)

Specifies the sound that will be played whenever the specified shape is clicked or animated or whenever the specified slide transition occurs.


## Syntax

 _expression_. **ImportFromFile**( **_FullName_** )

 _expression_ A variable that represents an **SoundEffect** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _FullName_|Required|**String**|The name of the specified sound file.|

## Example

This example specifies that the file Dudududu.wav will start to play at the transition to slide two in the active presentation and will continue to play until the next sound starts.


```vb
With ActivePresentation.Slides(2).SlideShowTransition

    .SoundEffect.ImportFromFile "c:\sndsys\dudududu.wav"

    .LoopSoundUntilNext = True

End With
```


## See also


#### Concepts


[SoundEffect Object](soundeffect-object-powerpoint.md)

