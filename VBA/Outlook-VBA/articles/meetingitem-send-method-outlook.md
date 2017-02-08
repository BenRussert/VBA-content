---
title: MeetingItem.Send Method (Outlook)
keywords: vbaol11.chm1458
f1_keywords:
- vbaol11.chm1458
ms.prod: OUTLOOK
api_name:
- Outlook.MeetingItem.Send
ms.assetid: d9a6ea8c-2146-06ec-aa8b-6e39fd60a916
---


# MeetingItem.Send Method (Outlook)

Sends the meeting item.


## Syntax

 _expression_ . **Send**

 _expression_ A variable that represents a **MeetingItem** object.


## Remarks

When you create a meeting request programmatically, you first create an  **[AppointmentItem](appointmentitem-object-outlook.md)** object instead of a **[MeetingItem](meetingitem-object-outlook.md)** object. To indicate the appointment is a meeting, set the **[MeetingStatus](appointmentitem-meetingstatus-property-outlook.md)** property of the **AppointmentItem** object to **olMeeting** . To send the meeting request, apply the **[Send](appointmentitem-send-method-outlook.md)** method to that **AppointmentItem** object.


## See also


#### Concepts


[MeetingItem Object](meetingitem-object-outlook.md)
#### Other resources


[How to: Create an Appointment as a Meeting on the Calendar](http://msdn.microsoft.com/library/create-an-appointment-as-a-meeting-on-the-calendar%28Office.15%29.aspx)


