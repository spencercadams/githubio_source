---
title: "getActiveAlarmSubscribers"
description: "This method retrieves an array of SoftLayer_Notification_User_Subscriber objects belonging to the SoftLayer_Monitoring_A... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Monitoring"
classes:
    - "SoftLayer_Monitoring_Agent"
---
# SoftLayer_Monitoring_Agent::getActiveAlarmSubscribers
## Overview 
This method retrieves an array of SoftLayer_Notification_User_Subscriber objects belonging to the SoftLayer_Monitoring_Agent which are able to receive alarm notifications. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* authenticate
* SoftLayer_Monitoring_AgentInitParameters

### Optional Headers
* SoftLayer_Monitoring_AgentObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Notification_User_Subscriber'>SoftLayer_Notification_User_Subscriber[] </a>