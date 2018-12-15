---
title: "API Reference (Visual Studio Debugging) | Microsoft Docs"
ms.custom: ""
ms.date: 11/15/2016
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
helpviewer_keywords: 
  - "debugging [Debugging SDK], API reference"
ms.assetid: e4e429da-3667-41f7-9158-a8207d13e91a
caps.latest.revision: 10
ms.author: gregvanl
manager: "ghogen"
---
# API Reference (Visual Studio Debugging)
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The reference section includes a conceptual overview of the API, a guide that shows the syntax and usage for all API elements, and an assortment of code examples. All references are listed alphabetically by category.  
  
 The following table shows the common `HRESULT` values returned by methods.  
  
|Name|Description|Value|  
|----------|-----------------|-----------|  
|S_OK|Success.|0x00000000|  
|E_UNEXPECTED|Unexpected failure.|0x8000FFFF|  
|E_NOTIMPL|Not implemented.|0x80004001|  
|E_OUTOFMEMORY|Not enough memory to complete the operation.|0x8007000E|  
|E_INVALIDARG|One or more arguments are invalid.|0x80070057|  
|E_NOINTERFACE|No such interface supported.|0x80004002|  
|E_POINTER|Invalid pointer.|0x80004003|  
|E_HANDLE|Invalid handle.|0x80070006|  
|E_ABORT|Operation aborted.|0x80004004|  
|E_FAIL|Unexpected failure.|0x80004005|  
|E_ACCESSDENIED|General access denied error.|0x80070005|  
  
> [!NOTE]
>  When a [!INCLUDE[vsprvs](../../../includes/vsprvs-md.md)] debugging method returns `S_OK`, it is assumed that all out parameter pointers are valid, that is, no validation is conducted on out parameter pointers when `S_OK` is returned.  
  
> [!NOTE]
>  Invalid or `NULL` [out] parameters may cause the IDE to crash.  
  
## See Also  
 [Interfaces](../../../extensibility/debugger/reference/interfaces-visual-studio-debugging.md)   
 [Enumerations](../../../extensibility/debugger/reference/enumerations-visual-studio-debugging.md)   
 [Structures and Unions](../../../extensibility/debugger/reference/structures-and-unions.md)   
 [SDK Helpers for Debugging](../../../extensibility/debugger/reference/sdk-helpers-for-debugging.md)   
 [Visual Studio Debugger Extensibility](../../../extensibility/debugger/visual-studio-debugger-extensibility.md)
