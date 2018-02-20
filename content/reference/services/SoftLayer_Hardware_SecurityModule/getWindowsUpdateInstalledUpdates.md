---
title: "getWindowsUpdateInstalledUpdates"
description: "Retrieve a list of Windows updates installed on a server as reported by the local SoftLayer Windows Server Update Servic... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Hardware"
classes:
    - "SoftLayer_Hardware_SecurityModule"
---
# SoftLayer_Hardware_SecurityModule::getWindowsUpdateInstalledUpdates
## Overview 
Retrieve a list of Windows updates installed on a server as reported by the local SoftLayer Windows Server Update Services (WSUS) server. Windows servers provisioned by SoftLayer are configured to use the local WSUS server via the private network by default. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Hardware_SecurityModuleInitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_Utility_Microsoft_Windows_UpdateServices_UpdateItem'>SoftLayer_Container_Utility_Microsoft_Windows_UpdateServices_UpdateItem[] </a>