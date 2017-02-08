---
title: DrawingControl.ShapeParentChanged Event (Visio)
ms.prod: VISIO
api_name:
- Visio.DrawingControl.ShapeParentChanged
ms.assetid: f3e0a789-bb27-10b4-f363-effc8f480a54
---


# DrawingControl.ShapeParentChanged Event (Visio)

Occurs after shapes are grouped or a group is ungrouped.


## Syntax

Private Sub  _expression_ _**ShapeParentChanged**( **_ByVal shape As [IVSHAPE]_** )

 _expression_ A variable that represents a **DrawingControl** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Shape_|Required| **[IVSHAPE]**|The shape whose parent changed.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/event-codes-visio%28Office.15%29.aspx).


