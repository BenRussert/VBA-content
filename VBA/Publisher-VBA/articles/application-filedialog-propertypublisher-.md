---
title: Application.FileDialog Property (Publisher)
keywords: vbapb10.chm131089
f1_keywords:
- vbapb10.chm131089
ms.prod: PUBLISHER
api_name:
- Publisher.Application.FileDialog
ms.assetid: 65d73a9d-be4c-d809-d10d-468181ef9eb0

---


# Application.FileDialog Property (Publisher)

Returns a  **FileDialog** object that represents a single instance of a file dialog box.


## Syntax

 _expression_. **FileDialog**( **_Type_**)

 _expression_A variable that represents a  **Application** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
|Type|Required| **MsoFileDialogType**| The type of dialog box.|

### Return Value

FileDialog


## Remarks

The Type parmater can be one of the  ** [MsoFileDialogType](http://msdn.microsoft.com/library/msofiledialogtype-enumeration-office%28Office.15%29.aspx)** constants declared in the Microsoft Office type library.


## Example

This example displays the  **Save As** dialog box and stores the file name specified by the user.


```vb
Sub ShowSaveAsDialog() 
 Dim dlgSaveAs As FileDialog 
 Dim strFile As String 
 
 Set dlgSaveAs = Application.FileDialog( _ 
 Type:=msoFileDialogSaveAs) 
 dlgSaveAs.Show 
 strFile = dlgSaveAs.SelectedItems(1) 
End Sub
```


## See also


#### Concepts


 [Application Object](application-object-publisher.md)

