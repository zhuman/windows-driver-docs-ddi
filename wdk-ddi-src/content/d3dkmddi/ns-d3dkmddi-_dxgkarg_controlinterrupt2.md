---
UID: NS:d3dkmddi._DXGKARG_CONTROLINTERRUPT2
title: _DXGKARG_CONTROLINTERRUPT2 (d3dkmddi.h)
description: The DXGKARG_CONTROLINTERRUPT2 structure is used in DxgkDdi_ControlInterrupt2 calls to describe the state of interrupts.
old-location: display\dxgkarg_controlinterrupt2.htm
ms.assetid: 881F93B2-999F-4E3A-A71D-731946E8AA97
ms.date: 03/24/2020
ms.keywords: DXGKARG_CONTROLINTERRUPT2, DXGKARG_CONTROLINTERRUPT2 structure [Display Devices], DXGKARG_CONTROLINTTERUPT2, DXGKARG_CONTROLINTTERUPT2 structure [Display Devices], _DXGKARG_CONTROLINTERRUPT2, d3dkmddi/DXGKARG_CONTROLINTERRUPT2, display.dxgkarg_controlinterrupt2
f1_keywords:
 - "d3dkmddi/DXGKARG_CONTROLINTTERUPT2"
 - "DXGKARG_CONTROLINTTERUPT2"
req.header: d3dkmddi.h
req.include-header: D3dkmddi.h
req.target-type: Windows
req.target-min-winverclnt: Available in Windows 10 and later versions of the Windows operating systems.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- d3dkmddi.h
api_name:
- DXGKARG_CONTROLINTTERUPT2
targetos: Windows
tech.root: display
req.typenames: DXGKARG_CONTROLINTERRUPT2
---

# _DXGKARG_CONTROLINTERRUPT2 structure

## -description

The **DXGKARG_CONTROLINTERRUPT2** structure is used in [**DxgkDdi_ControlInterrupt2**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/nc-d3dkmddi-dxgkddi_controlinterrupt2) calls to describe the state of interrupts.

## -struct-fields

### -field InterruptType

A [**DXGK_INTERRUPT_TYPE**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ne-d3dkmddi-_dxgk_interrupt_type) enumeration that indicates the type of interrupt.

### -field InterruptState

A [**DXGK_INTERRUPT_STATE**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ne-d3dkmddi-_dxgk_interrupt_state) enumeration that indicates whether interrupts are enabled for the driver.

### -field CrtcVsyncState

A [**DXGK_CRTC_VSYNC_STATE**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ne-d3dkmddi-_dxgk_crtc_vsync_state) enumeration that indicates whether VSYNCs are enabled if interrupts are also enabled for the driver.

## -remarks

**InterruptState** and **CrtcVsyncState** are members of a union.

## -see-also

[**DXGK_INTERRUPT_STATE**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ne-d3dkmddi-_dxgk_interrupt_state)

[**DXGK_INTERRUPT_TYPE**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ne-d3dkmddi-_dxgk_interrupt_type)

[**DXGKARG_CONTROLINTERRUPT3**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/ns-d3dkmddi-_dxgkarg_controlinterrupt3)

[**DxgkDdi_ControlInterrupt2**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/nc-d3dkmddi-dxgkddi_controlinterrupt2)

[**DxgkDdi_ControlInterrupt3**](https://docs.microsoft.com/windows-hardware/drivers/ddi/d3dkmddi/nc-d3dkmddi-dxgkddi_controlinterrupt3)
