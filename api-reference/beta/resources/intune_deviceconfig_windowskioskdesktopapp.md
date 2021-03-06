﻿# windowsKioskDesktopApp resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

The base class for a type of apps

Inherits from [windowsKioskAppBase](../resources/intune_deviceconfig_windowskioskappbase.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|name|String|Represents the friendly name of an app|
|path|String|Define the path of a desktop app|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsKioskDesktopApp"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsKioskDesktopApp",
  "name": "String",
  "path": "String"
}
```






