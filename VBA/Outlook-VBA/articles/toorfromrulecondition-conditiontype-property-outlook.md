---
title: ToOrFromRuleCondition.ConditionType Property (Outlook)
keywords: vbaol11.chm2461
f1_keywords:
- vbaol11.chm2461
ms.prod: OUTLOOK
api_name:
- Outlook.ToOrFromRuleCondition.ConditionType
ms.assetid: a5c6e08c-643e-965d-cd3e-b434f20579a0
---


# ToOrFromRuleCondition.ConditionType Property (Outlook)

Returns a constant from the  **[OlRuleConditionType](olruleconditiontype-enumeration-outlook.md)** enumeration that indicates the type of rule condition. Read-only.


## Syntax

 _expression_ . **ConditionType**

 _expression_ A variable that represents a **ToOrFromRuleCondition** object.


## Remarks

 **ConditionType** depends on the type of rule condition, as two types of rule conditions use the **[ToOrFromRuleCondition](toorfromrulecondition-object-outlook.md)** object: **olConditionFrom** and **olConditionSentTo** . **olConditionFrom** is supported only by rules for receiving messages, while **olConditionSentTo** is supported by rules for receiving messages as well as rules for sending messages. For more information, see[Specify Rule Conditions](http://msdn.microsoft.com/library/specifying-rule-conditions%28Office.15%29.aspx).


## See also


#### Concepts


[ToOrFromRuleCondition Object](toorfromrulecondition-object-outlook.md)

