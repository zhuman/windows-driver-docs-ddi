---
UID: NC:d3dkmthk.PFND3DKMT_MARKDEVICEASERROR
title: PFND3DKMT_MARKDEVICEASERROR (d3dkmthk.h)
description: Pfnd3dkmtMarkdeviceaserror marks a device as error.
ms.assetid: 12dc7034-0fec-46ec-aa90-5a3068fca98e
ms.date: 10/19/2018
keywords: ["PFND3DKMT_MARKDEVICEASERROR callback function"]
f1_keywords:
 - "d3dkmthk/PFND3DKMT_MARKDEVICEASERROR"
 - "PFND3DKMT_MARKDEVICEASERROR"
req.header: d3dkmthk.h
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
- apiref
api_type: 
- UserDefined
api_location: 
- d3dkmthk.h
api_name: 
- PFND3DKMT_MARKDEVICEASERROR
targetos: Windows
ms.custom: RS5
dev_langs:
 - c++
tech.root: display
---

# PFND3DKMT_MARKDEVICEASERROR callback function

## -description

Pfnd3dkmtMarkdeviceaserror marks a device as error.

## -prototype

```cpp
//Declaration

PFND3DKMT_MARKDEVICEASERROR Pfnd3dkmtMarkdeviceaserror; 

// Definition

NTSTATUS Pfnd3dkmtMarkdeviceaserror 
(
	D3DKMT_MARKDEVICEASERROR *
)
{...}

```

## -parameters

### -param Arg1

Pointer to a [D3DKMT_MARKDEVICEASERROR](ns-d3dkmthk-_d3dkmt_markdeviceaserror.md) structure.

## -returns

Returns NTSTATUS.


## -remarks




## -see-also
