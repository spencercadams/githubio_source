---
title: "getCreateUser"
description: "Retrieve the customer user who created the shipment."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account_Shipment"
---
# SoftLayer_Account_Shipment::getCreateUser
## Overview 
Retrieve the customer user who created the shipment.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Account_ShipmentInitParameters
* authenticate

### Optional Headers
* SoftLayer_Account_ShipmentObjectMask
* SoftLayer_Account_ShipmentObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer </a>