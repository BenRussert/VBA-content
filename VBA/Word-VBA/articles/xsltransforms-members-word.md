---
title: XSLTransforms Members (Word)
keywords: vbawd10.chm1514
f1_keywords:
- vbawd10.chm1514
ms.prod: WORD
ms.assetid: 489a3391-fbd1-a326-9c4d-7fa8d4b64d02
---


# XSLTransforms Members (Word)

A collection of  **XSLTransform** objects that represent all of the Extensible Stylesheet Language Transformations (XSLTs) for a specific XML namespace.


## Remarks

Use the  **Add** method to add an individual **XSLTransform** object to the collection of XSLTs for a schema. The following example adds simplesample.xslt to the XSLTs for the SimpleSample schema.


```vb
Sub AddXSLT() 
 Dim objSchema As XMLNamespace 
 Dim objTransform As XSLTransform 
 
 Set objSchema = Application.XMLNamespaces("SimpleSample") 
 Set objTransform = objSchema.XSLTransforms _ 
 .Add("c:\schemas\simplesample.xslt") 
 
End Sub
```

Use the  **Item** method to return a single **XSLTransform** object. The following example deletes the first XSLT in the collection of XSLTs for the SimpleSample schema.




```vb
Sub DeleteTransform() 
 Dim objXSLT As XSLTransform 
 Dim intResponse As Integer 
 
 Set objXSLT = Application.XMLNamespaces("SimpleSample") _ 
 .XSLTransforms.Item(1) 
 
 intResponse = MsgBox("Are you sure you want to delete the " _ 
 &; objXSLT.Alias &; " XSL transform?", vbYesNo) 
 
 If intResponse = vbYes Then objXSLT.Delete 
 
End Sub
```


 **Note**  The SimpleSample schema is included in the Smart Document Software Development Kit (SDK). For more information, refer to the Smart Document SDK on the Microsoft Developer Network (MSDN) Web site.


## See also


#### Other resources



[Word Object Model Reference](http://msdn.microsoft.com/library/object-model-word-vba-reference%28Office.15%29.aspx)

