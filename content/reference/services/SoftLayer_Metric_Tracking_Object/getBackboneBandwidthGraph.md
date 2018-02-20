---
title: "getBackboneBandwidthGraph"
description: "Retrieve a PNG image of the last 24 hours of bandwidth usage of one of SoftLayer's network backbones."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Metric"
classes:
    - "SoftLayer_Metric_Tracking_Object"
---
# SoftLayer_Metric_Tracking_Object::getBackboneBandwidthGraph
## Overview 
Retrieve a PNG image of the last 24 hours of bandwidth usage of one of SoftLayer's network backbones. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|graphTitle| string| An optional name to override a backbone graph image's title|


### Required Headers
* authenticate
* SoftLayer_Metric_Tracking_ObjectInitParameters

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_Bandwidth_GraphOutputs'>SoftLayer_Container_Bandwidth_GraphOutputs </a>