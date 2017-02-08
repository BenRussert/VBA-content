---
title: MarkAsTaskRuleAction Object (Outlook)
keywords: vbaol11.chm3170
f1_keywords:
- vbaol11.chm3170
ms.prod: OUTLOOK
api_name:
- Outlook.MarkAsTaskRuleAction
ms.assetid: 639d9242-7387-2b25-9d0f-f7a14cf16790
---


# MarkAsTaskRuleAction Object (Outlook)

Represents an action that marks a message as a task.


## Remarks

 **MarkAsTaskRuleAction** is derived from the **[RuleAction](ruleaction-object-outlook.md)** object. Each rule is associated with a **[RuleActions](ruleactions-object-outlook.md)** object which has a **[MarkAsTask](ruleactions-markastask-property-outlook.md)** property. The **MarkAsTask** property always returns a **MarkAsTaskRuleAction** object. If the rule has an enabled rule action that marks a message as a task, then **[MarkAsTaskRuleAction.Enabled](markastaskruleaction-enabled-property-outlook.md)** would be **True**.

For more information on specifying rule actions, see [Specify Rule Actions](http://msdn.microsoft.com/library/specifying-rule-actions%28Office.15%29.aspx).


## Properties



|**Name**|
|:-----|
|[ActionType](markastaskruleaction-actiontype-property-outlook.md)|
|[Application](markastaskruleaction-application-property-outlook.md)|
|[Class](markastaskruleaction-class-property-outlook.md)|
|[Enabled](markastaskruleaction-enabled-property-outlook.md)|
|[FlagTo](markastaskruleaction-flagto-property-outlook.md)|
|[MarkInterval](markastaskruleaction-markinterval-property-outlook.md)|
|[Parent](markastaskruleaction-parent-property-outlook.md)|
|[Session](markastaskruleaction-session-property-outlook.md)|

## See also


#### Other resources


[Outlook Object Model Reference](http://msdn.microsoft.com/library/object-model-outlook-vba-reference%28Office.15%29.aspx)
