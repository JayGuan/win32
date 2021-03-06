---
Description: The get\_OffsetY method retrieves the vertical offset of the target rectangle.
ms.assetid: 78bb3565-7a98-4a64-a2f2-6c34edb47733
title: IDxtCompositor::get_OffsetY method
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtCompositor.get_OffsetY
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IDxtCompositor::get\_OffsetY method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `get_OffsetY` method retrieves the vertical offset of the target rectangle.

## Syntax


```C++
HRESULT get_OffsetY(
  [out, retval] long *pVal
);
```



## Parameters

<dl> <dt>

*pVal* \[out, retval\]
</dt> <dd>

Receives the vertical offset of the target rectangle, in pixels.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://go.microsoft.com/fwlink/p/?linkid=129787). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IDxtCompositor Interface**](idxtcompositor.md)
</dt> </dl>

 

 




