---
title: SenderInAddressListRuleCondition Object (Outlook)
keywords: vbaol11.chm3182
f1_keywords:
- vbaol11.chm3182
ms.prod: OUTLOOK
api_name:
- Outlook.SenderInAddressListRuleCondition
ms.assetid: c43aa055-8d4f-e264-07dd-4c5519faf1c7
---


# SenderInAddressListRuleCondition Object (Outlook)

Represents a rule condition that the sender's address is in the address list specified in  **[AddressRuleCondition.Address](addressrulecondition-address-property-outlook.md)**.


## Remarks

 **SenderInAddressListRuleCondition** is derived from the **[RuleCondition](rulecondition-object-outlook.md)** object. Each rule is associated with a **[RuleConditions](ruleconditions-object-outlook.md)** object which has a **[SenderInAddressList](ruleconditions-senderinaddresslist-property-outlook.md)** property. The **SenderInAddressList** property always returns a **SenderInAddressListRuleCondition** object. If the rule has any of these rule conditions enabled, then **[SenderInAddressListRuleCondition.Enabled](senderinaddresslistrulecondition-enabled-property-outlook.md)** would be **True**.

For more information on specifying rule conditions, see [Specify Rule Conditions](http://msdn.microsoft.com/library/specifying-rule-conditions%28Office.15%29.aspx).


## Properties



|**Name**|
|:-----|
|[AddressList](senderinaddresslistrulecondition-addresslist-property-outlook.md)|
|[Application](senderinaddresslistrulecondition-application-property-outlook.md)|
|[Class](senderinaddresslistrulecondition-class-property-outlook.md)|
|[ConditionType](senderinaddresslistrulecondition-conditiontype-property-outlook.md)|
|[Enabled](senderinaddresslistrulecondition-enabled-property-outlook.md)|
|[Parent](senderinaddresslistrulecondition-parent-property-outlook.md)|
|[Session](senderinaddresslistrulecondition-session-property-outlook.md)|

## See also


#### Other resources


[Outlook Object Model Reference](http://msdn.microsoft.com/library/object-model-outlook-vba-reference%28Office.15%29.aspx)
