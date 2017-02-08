---
title: InvisibleApp.BeforeDataRecordsetDelete Event (Visio)
ms.prod: VISIO
api_name:
- Visio.InvisibleApp.BeforeDataRecordsetDelete
ms.assetid: 0d007a29-b7a9-5355-b3d4-dca8600ddc9f
---


# InvisibleApp.BeforeDataRecordsetDelete Event (Visio)

Occurs before a  **DataRecordset** object is deleted from the **DataRecordsets** collection.


 **Note**  This Visio object or member is available only to licensed users of Visio Professional 2013.


## Syntax

Private Sub  _expression_ _**BeforeDataRecordsetDelete**( **_ByVal DataRecordset As IVDATARECORDSET_** )

 _expression_ An expression that returns a **InvisibleApp** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _DataRecordset_|Required| **[IVDATARECORDSET]**|The data recordset that is going to be deleted.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/event-codes-visio%28Office.15%29.aspx).


