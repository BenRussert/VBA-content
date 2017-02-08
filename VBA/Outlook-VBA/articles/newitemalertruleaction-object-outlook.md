---
title: NewItemAlertRuleAction Object (Outlook)
keywords: vbaol11.chm3171
f1_keywords:
- vbaol11.chm3171
ms.prod: OUTLOOK
api_name:
- Outlook.NewItemAlertRuleAction
ms.assetid: 01d30816-50aa-ff23-69a0-4aa627b3d7e4
---


# NewItemAlertRuleAction Object (Outlook)

Represents an action that displays a new item alert to the user.


## Remarks

 **NewItemAlertRuleAction** is derived from the **[RuleAction](ruleaction-object-outlook.md)** object. Each rule is associated with a **[RuleActions](ruleactions-object-outlook.md)** object which has a **[NewItemAlert](ruleactions-newitemalert-property-outlook.md)** property. The **NewItemAlert** property always returns a **NewItemAlertRuleAction** object. If the rule has an enabled rule action that displays the specified alert in the **New item Alert** dialog box, then **[NewItemAlertRuleAction.Enabled](newitemalertruleaction-enabled-property-outlook.md)** would be **True**.

For more information on specifying rule actions, see [Specify Rule Actions](http://msdn.microsoft.com/library/specifying-rule-actions%28Office.15%29.aspx).


## Properties



|**Name**|
|:-----|
|[ActionType](newitemalertruleaction-actiontype-property-outlook.md)|
|[Application](newitemalertruleaction-application-property-outlook.md)|
|[Class](newitemalertruleaction-class-property-outlook.md)|
|[Enabled](newitemalertruleaction-enabled-property-outlook.md)|
|[Parent](newitemalertruleaction-parent-property-outlook.md)|
|[Session](newitemalertruleaction-session-property-outlook.md)|
|[Text](newitemalertruleaction-text-property-outlook.md)|

## See also


#### Other resources


[Outlook Object Model Reference](http://msdn.microsoft.com/library/object-model-outlook-vba-reference%28Office.15%29.aspx)
