---
title: "getModifyUser"
description: "Retrieve the customer user who last modified the request."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_MassDataMigration_Request"
---
# SoftLayer_Network_Storage_MassDataMigration_Request::getModifyUser
## Overview 
Retrieve the customer user who last modified the request.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_Storage_MassDataMigration_RequestInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_Storage_MassDataMigration_RequestObjectMask
* SoftLayer_Network_Storage_MassDataMigration_RequestObjectFilter
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Customer'>SoftLayer_User_Customer </a>