---
title: "getAllFiles"
description: "{{CloudLayerOnlyMethod}} Retrieve details such as id, name, size, create date for all files in a Storage account's root... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Storage_Backup_Evault"
---
# SoftLayer_Network_Storage_Backup_Evault::getAllFiles
## Overview 
{{CloudLayerOnlyMethod}} Retrieve details such as id, name, size, create date for all files in a Storage account's root directory. This does not download file content. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Network_Storage_Backup_EvaultInitParameters

### Optional Headers
* resultLimit

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_Utility_File_Entity'>SoftLayer_Container_Utility_File_Entity[] </a>