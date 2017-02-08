---
title: Categories Object (Word)
ms.prod: WORD
api_name:
- Word.Categories
ms.assetid: f5f5081d-4309-6617-28da-c369c1fe690c
---


# Categories Object (Word)

Represents a collection of building block categories.


## Remarks

Use the  **Item** method to access an exising category. You can then use the **[BuildingBlocks](category-buildingblocks-property-word.md)** property to access a collection of **[BuildingBlock](buildingblock-object-word.md)** objects for the category. The following example prints the type and category names of all the building blocks in the first template to the **Immediate Window** . (This example assumes that the **Immediate Window** is visible.)


```vb
Dim objTemplate As Template 
Dim objBBT As BuildingBlockType 
Dim objCat As Category 
Dim intCount As Integer 
Dim intCountCat As Integer 
 
Set objTemplate = Templates(1) 
 
For intCount = 1 To objTemplate.BuildingBlockTypes.Count 
 Set objBBT = objTemplate.BuildingBlockTypes(intCount) 
 If objBBT.Categories.Count > 0 Then 
 Debug.Print objBBT.Name 
 For intCountCat = 1 To objBBT.Categories.Count 
 Set objCat = objBBT.Categories(intCountCat) 
 Debug.Print vbTab &; objCat.Name 
 Next 
 End If 
Next
```

Use the  **Item** method to access an exising category; to create a new category, use the **Add** method of the **BuildingBlockEntries** collection. Set the value of the Category parameter.

For more information about building blocks, see [Working with Building Blocks](http://msdn.microsoft.com/library/working-with-building-blocks%28Office.15%29.aspx).


## See also


#### Other resources



[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)

