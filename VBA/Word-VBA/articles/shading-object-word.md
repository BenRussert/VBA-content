---
title: Shading Object (Word)
keywords: vbawd10.chm2362
f1_keywords:
- vbawd10.chm2362
ms.prod: WORD
api_name:
- Word.Shading
ms.assetid: e136509a-1be1-29e4-7b37-1faf659e37ba
---


# Shading Object (Word)

Contains shading attributes for an object.


## Remarks

Use the  **Shading** property to return the **Shading** object. The following example applies fine gray shading to the first paragraph in the active document.


```
ActiveDocument.Paragraphs(1).Shading.Texture = wdTexture10Percent
```

The following example applies shading with different foreground and background colors to the selection.




```
With Selection.Shading 
 .Texture = wdTexture20Percent 
 .ForegroundPatternColorIndex = wdBlue 
 .BackgroundPatternColorIndex = wdYellow 
End With
```

The following example applies a vertical line texture to the first row in the first table in the active document.




```
ActiveDocument.Tables(1).Rows(1).Shading.Texture = _ 
 wdTextureVertical
```


## Properties



|**Name**|
|:-----|
|[Application](shading-application-property-word.md)|
|[BackgroundPatternColor](shading-backgroundpatterncolor-property-word.md)|
|[BackgroundPatternColorIndex](shading-backgroundpatterncolorindex-property-word.md)|
|[Creator](shading-creator-property-word.md)|
|[ForegroundPatternColor](shading-foregroundpatterncolor-property-word.md)|
|[ForegroundPatternColorIndex](shading-foregroundpatterncolorindex-property-word.md)|
|[Parent](shading-parent-property-word.md)|
|[Texture](shading-texture-property-word.md)|

## See also


#### Other resources


[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)
