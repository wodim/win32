---
Description: Provides additional information to be used with the CreateReferencePoint method of the Msvm\_VirtualSystemReferencePointService class.
ms.assetid: 6b997ba5-871c-4c33-9ed5-b9a13cbfaacd
title: Msvm\_VirtualSystemReferencePointSettingData class
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Msvm\_VirtualSystemReferencePointSettingData class

Provides additional information to be used with the [**CreateReferencePoint**](msvm-virtualsystemreferencepointservice-createreferencepoint.md) method of the [**Msvm\_VirtualSystemReferencePointService**](msvm-virtualsystemreferencepointservice.md) class.

The following syntax is simplified from Managed Object Format (MOF) code and includes all of the inherited properties.

## Syntax

``` syntax
[AMENDMENT]
class Msvm_VirtualSystemReferencePointSettingData : CIM_SettingData
{
  uint8 ConsistencyLevel;
};
```

## Members

The **Msvm\_VirtualSystemReferencePointSettingData** class has these types of members:

-   [Properties](#properties)

### Properties

The **Msvm\_VirtualSystemReferencePointSettingData** class has these properties.

<dl> <dt>

**ConsistencyLevel**
</dt> <dd> <dl> <dt>

Data type: **uint8**
</dt> <dt>

Access type: Read-only
</dt> </dl>

The consistency level of the reference point.

</dd> </dl>

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                             |
| Minimum supported server<br/> | Windows Server 2016<br/>                                                                          |
| Namespace<br/>                | Root\\virtualization\\v2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



## See also

<dl> <dt>

[**CIM\_SettingData**](cim-settingdata.md)
</dt> </dl>

 

 



