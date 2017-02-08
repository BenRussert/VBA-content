---
title: FromRssFeedRuleCondition Object (Outlook)
keywords: vbaol11.chm3260
f1_keywords:
- vbaol11.chm3260
ms.prod: OUTLOOK
api_name:
- Outlook.FromRssFeedRuleCondition
ms.assetid: 8de6e629-7e3d-b4df-d758-a5bff3abd6a1
---


# FromRssFeedRuleCondition Object (Outlook)

Represents a rule condition that evaluates whether an item is from a specified RSS subscription.


## Remarks

 **FromRssFeedRuleCondition** is derived from the **[RuleCondition](rulecondition-object-outlook.md)** object. Each rule is associated with a **[RuleConditions](ruleconditions-object-outlook.md)** object, which has a **[RuleConditions.FromRssFeed](ruleconditions-fromrssfeed-property-outlook.md)** property. The **FromRssFeed** property always returns a **FromRssFeedRuleCondition** object. If the rule has any of these rule conditions enabled, then **[FromRssFeedRuleCondition.Enabled](fromrssfeedrulecondition-enabled-property-outlook.md)** is **True**.

For more information about specifying rule actions, see [Specify Rule Conditions](http://msdn.microsoft.com/library/specifying-rule-conditions%28Office.15%29.aspx).


## Properties



|**Name**|
|:-----|
|[Application](fromrssfeedrulecondition-application-property-outlook.md)|
|[Class](fromrssfeedrulecondition-class-property-outlook.md)|
|[ConditionType](fromrssfeedrulecondition-conditiontype-property-outlook.md)|
|[Enabled](fromrssfeedrulecondition-enabled-property-outlook.md)|
|[FromRssFeed](fromrssfeedrulecondition-fromrssfeed-property-outlook.md)|
|[Parent](fromrssfeedrulecondition-parent-property-outlook.md)|
|[Session](fromrssfeedrulecondition-session-property-outlook.md)|

## See also


#### Other resources


[Outlook Object Model Reference](http://msdn.microsoft.com/library/object-model-outlook-vba-reference%28Office.15%29.aspx)
