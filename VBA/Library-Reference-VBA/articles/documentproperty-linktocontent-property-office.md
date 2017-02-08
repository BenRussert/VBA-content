---
title: DocumentProperty.LinkToContent Property (Office)
keywords: vbaof11.chm250008
f1_keywords:
- vbaof11.chm250008
ms.prod: MULTIPLEPRODUCTS
api_name:
- Office.DocumentProperty.LinkToContent
ms.assetid: 062df6df-cdee-81fc-3244-e229dacaa64e
---


# DocumentProperty.LinkToContent Property (Office)

Is  **True** if the value of the custom document property is linked to the content of the container document. **False** if the value is static. Read/write.


## Syntax

 _expression_. **LinkToContent**( ** _pfLinkRetVal_** )

 _expression_ A variable that represents a **DocumentProperty** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _pfLinkRetVal_|Required|**Boolean**|Indicates whether the document property is linked to the container document.|

## Remarks

This property applies only to custom document properties. For built-in document properties, the value of this property is  **False**.

Use the  **LinkSource** property to set the source for the specified linked property. Setting the **LinkSource** property sets the **LinkToContent** property to **True**.

For Excel, If LinkToContent is set to  **True**, you must supply an address or range name for the[LinkSource](http://msdn.microsoft.com/library/documentproperty-linksource-property-office.md %28Office.15%29.aspx) from the workbook. If the address or range name covers more than one cell, the custom document property takes the value from the top left cell of the range.


## Example

This example displays the linked status of the custom document property. For the example to work,  **dp** must be a valid **DocumentProperty** object.


```vb
Sub DisplayLinkStatus(dp As DocumentProperty) 
 Dim stat As String, tf As String 
 If dp.LinkToContent Then 
 tf = "" 
 Else 
 tf = "not " 
 End If 
 stat = "This property is " &; tf &; "linked" 
 If dp.LinkToContent Then 
 stat = stat + Chr(13) &; "The link source is " &; dp.LinkSource 
 End If 
 MsgBox stat 
End Sub
```


## See also


#### Concepts


[DocumentProperty Object](documentproperty-object-office.md)
[Sync Object](sync-object-office.md)

