---
title: DriveExists Method
keywords: vblr6.chm2182038
f1_keywords:
- vblr6.chm2182038
ms.prod: MULTIPLEPRODUCTS
ms.assetid: ddba70e5-8b60-4ce6-631f-fb10f81a6d93
---


# DriveExists Method



 **Description**
Returns  **True** if the specified drive exists; **False** if it does not.
 **Syntax**
 _object_. **DriveExists(**_drivespec_**)**
The  **DriveExists** method syntax has these parts:


|**Part**|**Description**|
|:-----|:-----|
| _object_|Required. Always the name of a  **FileSystemObject**.|
| _drivespec_|Required. A drive letter or a complete path specification.|
 **Remarks**
For drives with removable media, the  **DriveExists** method returns **True** even if there are no media present. Use the **IsReady** property of the **Drive** object to determine if a drive is ready.

