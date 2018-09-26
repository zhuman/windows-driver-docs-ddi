---
UID: NF:dbgmodel.IDebugHostMemory2.GetDisplayStringForLocation
title: IDebugHostMemory2::GetDisplayStringForLocation
author: windows-driver-content
description: TBD
ms.assetid: 0b7327dc-22ae-4bc3-b222-fa2f3210c453
ms.author: windowsdriverdev
ms.date: 09/18/2018
ms.topic: method
ms.keywords: IDebugHostMemory2::GetDisplayStringForLocation, GetDisplayStringForLocation, IDebugHostMemory2.GetDisplayStringForLocation, IDebugHostMemory2::GetDisplayStringForLocation, IDebugHostMemory2.GetDisplayStringForLocation
req.header: dbgmodel.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
-	apiref
api_type: 
-	COM
api_location: 
-	dbgmodel.h
api_name: 
-	IDebugHostMemory2.GetDisplayStringForLocation
product: Windows
targetos: Windows


tech.root: debugger
---

# IDebugHostMemory2::GetDisplayStringForLocation


## -description

For a given location within the address space of the target as defined by context and location, convert the location to a displayable string (according to whatever format the host chooses).

If the "verbose" argument is true, the string conversion may be "more verbose"

## -parameters

### -param context

### -param location

### -param verbose

### -param locationName


## -returns
This method returns HRESULT which indicates success or failure.

## -remarks

## -see-also

[IDebugHostMemory2 interface](nn-dbgmodel-idebughostmemory2.md)