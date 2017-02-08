---
title: SectionProperties.Move Method (PowerPoint)
keywords: vbapp10.chm725010
f1_keywords:
- vbapp10.chm725010
ms.prod: POWERPOINT
ms.assetid: f414c836-09ed-3f82-4158-fa4291c0d931
---


# SectionProperties.Move Method (PowerPoint)

Moves the specified section to the specified index position, moving the slides in the section along with the section break.


## Syntax

 _expression_. **Move**( **_sectionIndex_**, **_toPos_** )

 _expression_ A variable that represents a **SectionProperties** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _sectionIndex_|Required|**Integer**|The index of the section to move.|
| _toPos_|Required|**Integer**|The index position to which to move the section.|

## Remarks

The section is moved to the index position immediately before the section whose current index is toPos.


## See also


#### Concepts


[SectionProperties Object](sectionproperties-object-powerpoint.md)

