---
title: "getDiskSpaceUsageDataByDate"
description: "This method returns disk space usage data for your CDN FTP."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_ContentDelivery_Account"
aliases:
    - "/reference/services/softlayer_network_contentdelivery_account/getDiskSpaceUsageDataByDate"
---
# [SoftLayer_Network_ContentDelivery_Account](/reference/services/SoftLayer_Network_ContentDelivery_Account)::getDiskSpaceUsageDataByDate

Returns a CDN FTP disk space usage


## Overview 
This method returns disk space usage data for your CDN FTP. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|beginDateTime| dateTime| The beginning time|
|endDateTime| dateTime| ending time|


### Required Headers
* authenticate
* SoftLayer_Network_ContentDelivery_AccountInitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Metric_Tracking_Object_Data'>SoftLayer_Metric_Tracking_Object_Data[] </a>

