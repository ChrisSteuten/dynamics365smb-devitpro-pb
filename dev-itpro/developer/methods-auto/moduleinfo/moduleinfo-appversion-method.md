---
title: "ModuleInfo.AppVersion() Method"
description: "Gets the version of the specified application's metadata."
ms.author: solsen
ms.date: 05/14/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# ModuleInfo.AppVersion() Method
> **Version**: _Available or changed with runtime version 1.0._

Gets the version of the specified application's metadata.


## Syntax
```AL
AppVersion :=   ModuleInfo.AppVersion()
```
> [!NOTE]
> This method can be invoked using property access syntax.
## Parameters
*ModuleInfo*  
&emsp;Type: [ModuleInfo](moduleinfo-data-type.md)  
An instance of the [ModuleInfo](moduleinfo-data-type.md) data type.  

## Return Value
*AppVersion*  
&emsp;Type: [Version](../version/version-data-type.md)  
The version of the specified application's metadata.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[ModuleInfo Data Type](moduleinfo-data-type.md)  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)