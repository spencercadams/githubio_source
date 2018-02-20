---
title: "getFirewallRules"
description: "Retrieve the currently running rule set of a firewalled VLAN."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Network"
classes:
    - "SoftLayer_Network_Vlan"
---
# SoftLayer_Network_Vlan::getFirewallRules
## Overview 
Retrieve the currently running rule set of a firewalled VLAN.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Network_VlanInitParameters
* authenticate

### Optional Headers
* SoftLayer_Network_VlanObjectMask
* SoftLayer_Network_VlanObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Network_Vlan_Firewall_Rule'>SoftLayer_Network_Vlan_Firewall_Rule[] </a>