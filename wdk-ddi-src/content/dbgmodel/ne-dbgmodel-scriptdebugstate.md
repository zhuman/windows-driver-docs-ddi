---
UID: NE:dbgmodel.ScriptDebugState
title: ScriptDebugState
author: windows-driver-content
description: 
ms.assetid: 4e89a344-ef44-479e-a97a-ce78a89d3273
ms.author: windowsdriverdev
ms.date: 07/16/2018
ms.topic: enum
ms.keywords: ScriptDebugState, , 
ms.prod: windows-hardware
ms.technology: windows-devices
req.header: dbgmodel.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.ddi-compliance:
req.max-support:
req.typenames: 
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	dbgmodel.h
api_name: 
-	ScriptDebugState
product: Windows
targetos: Windows
tech.root: debugger
---

# ScriptDebugState enumeration

## -description

Defines the current debugging state of a script

## -enum-fields

### -field ScriptDebugNoDebugger
Indicates that debugging is not active on the script

### -field ScriptDebugNotExecuting 
Indicates that no code within the script is actively executing

### -field ScriptDebugExecuting 
Indicates that the script is executing code

### -field ScriptDebugBreak
The script status is that it is broken into the script debugger 

## -remarks

## -see-also

[Debugger Data Model C++ Overview](https://review.docs.microsoft.com/en-us/windows-hardware/drivers/debugger/data-model-cpp-overview?branch=debugger-op-ref-docs)