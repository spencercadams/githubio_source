---
title: "getResourceRecords"
description: "Retrieve the individual records contained within a domain record. These include but are not limited to A, AAAA, MX, CTYP... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Dns"
classes:
    - "SoftLayer_Dns_Domain"
---
# SoftLayer_Dns_Domain::getResourceRecords
## Overview 
Retrieve the individual records contained within a domain record. These include but are not limited to A, AAAA, MX, CTYPE, SPF and TXT records.

### Parameters 
|Name | Type | Description |
| --- | --- | --- |


### Required Headers
* SoftLayer_Dns_DomainInitParameters
* authenticate

### Optional Headers
* SoftLayer_Dns_DomainObjectMask
* SoftLayer_Dns_DomainObjectFilter
* resultLimit
* SoftLayer_ObjectMask

### Return Values
<a href='/reference/datatypes/SoftLayer_Dns_Domain_ResourceRecord'>SoftLayer_Dns_Domain_ResourceRecord[] </a>