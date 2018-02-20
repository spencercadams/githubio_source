---
title: "getUpgradeItem"
description: "Retrieve billing items whose product item has an upgrade path defined in our system will return the next product item in... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Billing"
classes:
    - "SoftLayer_Billing_Item_Virtual_DedicatedHost"
---
# SoftLayer_Billing_Item_Virtual_DedicatedHost::getUpgradeItem
## Overview 
Retrieve billing items whose product item has an upgrade path defined in our system will return the next product item in the upgrade path.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Billing_Item_Virtual_DedicatedHostInitParameters
* authenticate

### Optional Headers
* SoftLayer_Billing_Item_Virtual_DedicatedHostObjectMask
* SoftLayer_Billing_Item_Virtual_DedicatedHostObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Product_Item'>SoftLayer_Product_Item </a>