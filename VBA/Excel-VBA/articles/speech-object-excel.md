---
title: Speech Object (Excel)
keywords: vbaxl10.chm718072
f1_keywords:
- vbaxl10.chm718072
ms.prod: EXCEL
api_name:
- Excel.Speech
ms.assetid: 1ddd61bc-989e-4766-423e-515ec5d1c23a
---


# Speech Object (Excel)

Contains methods and properties that pertain to speech.


## Remarks

Use the  **[Speech](application-speech-property-excel.md)** property of the **[Application](application-object-excel.md)** object to return a **[Speech](speech-object-excel.md)** object.


## Example

Once a  **Speech** object is returned, you can use the **[Speak](speech-speak-method-excel.md)** method of **Speech** object to play back the contents of a string. In the following example, Microsoft Excel plays back "Hello". This example assumes speech features have been installed on the host system.


 **Note**  There is a speech feature in the setup tree that pertains to Dictation and Command &; Control that does not have to be installed.


```vb
Sub UseSpeech() 
 
 Application.Speech.Speak "Hello" 
 
End Sub()
```


## See also


#### Other resources



[Excel Object Model Reference](http://msdn.microsoft.com/library/object-model-excel-vba-reference%28Office.15%29.aspx)

