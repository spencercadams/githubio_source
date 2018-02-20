---
title: "getPreferenceTypes"
description: "Use any of the preference types to fetch or modify user preferences using [[SoftLayer_User_Customer::getPreference|getPr... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
---
# SoftLayer_User_Customer_OpenIdConnect::getPreferenceTypes
## Overview 
Use any of the preference types to fetch or modify user preferences using [[SoftLayer_User_Customer::getPreference|getPreference]] or [[SoftLayer_User_Customer::changePreference|changePreference]], respectively. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_User_Customer_OpenIdConnectInitParameters

### Optional Headers
* SoftLayer_User_Customer_OpenIdConnectObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Preference_Type'>SoftLayer_User_Preference_Type[] </a>