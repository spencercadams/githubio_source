---
title: "getAssignedVolumes"
description: "Retrieve the SoftLayer_Network_Storage volumes to which this SoftLayer_Network_Storage_Allowed_Host is allowed access."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Allowed_Host_Subnet"
---
# SoftLayer_Network_Storage_Allowed_Host_Subnet::getAssignedVolumes
## Overview 
Retrieve the SoftLayer_Network_Storage volumes to which this SoftLayer_Network_Storage_Allowed_Host is allowed access.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_Storage_Allowed_Host_SubnetInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_Storage_Allowed_Host_SubnetObjectMask
* SoftLayer_Network_Storage_Allowed_Host_SubnetObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Storage'>SoftLayer_Network_Storage[] </a>