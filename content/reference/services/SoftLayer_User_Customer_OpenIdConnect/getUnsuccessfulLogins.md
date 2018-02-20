---
title: "getUnsuccessfulLogins"
description: "Retrieve a user's unsuccessful attempts to log into the SoftLayer customer portal."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
---
# SoftLayer_User_Customer_OpenIdConnect::getUnsuccessfulLogins
## Overview 
Retrieve a user's unsuccessful attempts to log into the SoftLayer customer portal.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_User_Customer_OpenIdConnectInitParameters
* authenticate

### Optional Headers
* SoftLayer_User_Customer_OpenIdConnectObjectMask
* SoftLayer_User_Customer_OpenIdConnectObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Customer_Access_Authentication'>SoftLayer_User_Customer_Access_Authentication[] </a>