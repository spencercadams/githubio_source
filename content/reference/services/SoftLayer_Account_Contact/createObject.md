---
title: "createObject"
description: "This method creates an account contact. The accountId is fixed, other properties can be set during creation. The typeId... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account_Contact"
---
# SoftLayer_Account_Contact::createObject
## Overview 
This method creates an account contact. The accountId is fixed, other properties can be set during creation. The typeId indicates the SoftLayer_Account_Contact_Type for the contact. This method returns the SoftLayer_Account_Contact object that is created. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|templateObject| <a href='/reference/datatypes/SoftLayer_Account_Contact'>SoftLayer_Account_Contact </a>| The SoftLayer_Account_Contact object that you wish to create.|


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_Account_ContactObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Account_Contact'>SoftLayer_Account_Contact </a>