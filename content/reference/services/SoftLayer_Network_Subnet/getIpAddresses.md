---
title: "getIpAddresses"
description: "Retrieve all the ip addresses associated with a subnet."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Subnet"
---
# SoftLayer_Network_Subnet::getIpAddresses
## Overview 
Retrieve all the ip addresses associated with a subnet.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_SubnetInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_SubnetObjectMask
* SoftLayer_Network_SubnetObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Subnet_IpAddress'>SoftLayer_Network_Subnet_IpAddress[] </a>