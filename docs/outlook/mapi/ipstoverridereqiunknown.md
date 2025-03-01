---
title: "IPSTOVERRIDEREQ  IUnknown"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IPSTOVERRIDEREQ
api_type:
- COM
ms.assetid: 22f497de-4afe-4433-965d-c3b5a66b05da
description: "Accesses resources of a Personal Folders file (PST) store provider."
---

# IPSTOVERRIDEREQ : IUnknown

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Accesses resources of a Personal Folders file (PST) store provider.
  
|Property |Value |
|:-----|:-----|
|Inherits from:  <br/> |IUnknown  <br/> |
|Implemented by:  <br/> |PST store provider  <br/> |
|Called by:  <br/> |Client applications  <br/> |
|Interface identifier:  <br/> |IID_IPSTOVERRIDEREQ  <br/> |
   
## Vtable order

|Member |Description |
|:-----|:-----|
|[IPSTOVERRIDEREQ::RegisterTrustedPSTOverrideHandler](ipstoverridereq-registertrustedpstoverridehandler.md) <br/> |Initiates the unlocking procedure for a Personal Folders (.pst) file. |
   
## Remarks

The PST Override Handler Interface Identifiers might not be defined in the downloadable header file you currently have, in which case you will find them in the [MAPI Constants](mapi-constants.md) topic, and can copy and add them to your code. Use the DEFINE_GUID macro defined in the Microsoft Windows Software Development Kit (SDK) header file guiddef.h to associate globally unique identifier (GUID) symbolic names with their values. 
  
For more information see [How to implement a PST override handler to bypass the PSTDisableGrow policy in Outlook 2007](https://support.microsoft.com/kb/956070).
  
## See also



[IPSTOVERRIDE1 : IUnknown](ipstoverride1iunknown.md)

