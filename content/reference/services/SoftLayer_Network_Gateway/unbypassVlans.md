---
title: "unbypassVlans"
description: "Start the asynchronous process to unbypass the provided VLANs. The VLANs must already be attached. Any VLANs that are al... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Gateway"
---
# SoftLayer_Network_Gateway::unbypassVlans
## Overview 
Start the asynchronous process to unbypass the provided VLANs. The VLANs must already be attached. Any VLANs that are already unbypassed will be ignored. The status field can be checked for progress. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|vlans| <a href='/reference/datatypes/SoftLayer_Network_Gateway_Vlan'>SoftLayer_Network_Gateway_Vlan[] </a>| |


### Required Headers
* authenticate
* SoftLayer_Network_GatewayInitParameters

### Optional Headers

### Return Values
void