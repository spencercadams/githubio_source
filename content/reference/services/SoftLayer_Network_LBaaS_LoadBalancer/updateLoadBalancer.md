---
title: "updateLoadBalancer"
description: "Update load balancer's description, and return the load balancer object containing all listeners, pools, members and dat... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_LBaaS_LoadBalancer"
---
# SoftLayer_Network_LBaaS_LoadBalancer::updateLoadBalancer
## Overview 
Update load balancer's description, and return the load balancer object containing all listeners, pools, members and datacenter. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|uuid| string| |
|newDescription| string| |


### Required Headers
* authenticate

### Optional Headers
* SoftLayer_Network_LBaaS_LoadBalancerObjectMask
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_LBaaS_LoadBalancer'>SoftLayer_Network_LBaaS_LoadBalancer </a>