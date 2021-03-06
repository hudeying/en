# rebootInstance


## Description
Reboot a single VM, only the virtual machine in the status of <b>running</b> can be rebooted, and the reboot is only available when there is no task in progress for virtual machine.


## Request method
POST

## Request address
https://vm.jdcloud-api.com/v1/regions/{regionId}/instances/{instanceId}:rebootInstance

|Name|Type|Required or not|Default value|Description|
|---|---|---|---|---|
|**instanceId**|String|True| |VM ID|
|**regionId**|String|True| |Region ID|

## Request parameter
None


## Response parameter
None


## Response code
|Return code|Description|
|---|---|
|**400**|Invalid parameter|
|**401**|Authentication failed|
|**404**|Not found|
|**503**|Service unavailable|
|**200**|OK|
|**500**|Internal server error|
