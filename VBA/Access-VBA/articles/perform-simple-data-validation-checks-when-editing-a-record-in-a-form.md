---
title: Perform Simple Data Validation Checks When Editing a Record in a Form
ms.prod: ACCESS
ms.assetid: 7bb5bf02-30ef-960a-051e-a22592dd80f9
---


# Perform Simple Data Validation Checks When Editing a Record in a Form

You can use the [BeforeUpdate](B783FCAB-F697-A464-820C-712EAC46CB4B.md) event of a form or a control to perform validation checks on data entered into a form or control. If the data in the form or control fails the validation check, you can set the **BeforeUpdate** event's _Cancel_ argument to **True** to cancel the update.

The following example prevents the user from saving changes to the current record if the Unit Cost field does not contain a value.



```vb
Private Sub Form_BeforeUpdate(Cancel As Integer) 
 
   ' Check for a blank value in the Unit Cost field. 
    If IsNull(Me![Unit Cost]) Then 
 
       ' Alert the user. 
       MsgBox "You must supply a Unit Cost."   
 
      ' Cancel the update. 
      Cancel = True 
    End If 
End Sub
```


