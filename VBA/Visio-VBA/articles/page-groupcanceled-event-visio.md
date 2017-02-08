---
title: Page.GroupCanceled Event (Visio)
keywords: vis_sdr.chm10962005
f1_keywords:
- vis_sdr.chm10962005
ms.prod: VISIO
api_name:
- Visio.Page.GroupCanceled
ms.assetid: ae7bd6b5-8975-26a2-86af-ff12eaef5ebb
---


# Page.GroupCanceled Event (Visio)

Occurs after an event handler has returned  **True** (cancel) to a **QueryCancelGroup** event.


## Syntax

Private Sub  _expression_ _**GroupCanceled**( **_ByVal Selection As [IVSELECTION]_** )

 _expression_ A variable that represents a **Page** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Selection_|Required| **[IVSELECTION]**|The selection of shapes that was going to be grouped.|

## Remarks

If you're using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own  **Event** objects, use the **Add** or **AddAdvise** method. To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. To create an **Event** object that receives notification, use the **AddAdvise** method. To find an event code for the event you want to create, see[Event codes](http://msdn.microsoft.com/library/event-codes-visio%28Office.15%29.aspx).


