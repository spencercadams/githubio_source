---
title: "getAdditionalEmails"
description: "Retrieve a portal user's additional email addresses. These email addresses are contacted when updates are made to suppor... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer"
---
# SoftLayer_User_Customer::getAdditionalEmails
## Overview 
Retrieve a portal user's additional email addresses. These email addresses are contacted when updates are made to support tickets.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_User_CustomerInitParameters
* authenticate

### Optional Headers
* SoftLayer_User_CustomerObjectMask
* SoftLayer_User_CustomerObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_User_Customer_AdditionalEmail'>SoftLayer_User_Customer_AdditionalEmail[] </a>