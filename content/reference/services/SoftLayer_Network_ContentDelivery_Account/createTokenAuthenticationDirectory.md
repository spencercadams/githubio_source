---
title: "createTokenAuthenticationDirectory"
description: "You need to specify a directory on your CDN FTP or on your origin host in which your secure content resides to enable th... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_ContentDelivery_Account"
---
# SoftLayer_Network_ContentDelivery_Account::createTokenAuthenticationDirectory
## Overview 
You need to specify a directory on your CDN FTP or on your origin host in which your secure content resides to enable the token authentication . It will take about about 30 minutes for a newly configured token authentication directory to take effect. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|directory| string| A directory name on your CDN FTP|
|mediaType| string| Valid content types are: HTTP, FLASH or WM|


### Required Headers
* authenticate
* SoftLayer_Network_ContentDelivery_AccountInitParameters

### Optional Headers

### Return Values
boolean