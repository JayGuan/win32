---
title: log
description: Returns the base-e logarithm of the specified value.
ms.assetid: 443e7aa7-7219-40ad-aafc-4bce09c8f596
keywords:
- log HLSL
topic_type:
- apiref
api_name:
- log
api_type:
- NA
ms.topic: article
ms.date: 05/31/2018
api_location: 
---

# log

Returns the base-e logarithm of the specified value.



| *ret* log(*x*) |
|----------------|



 

## Parameters



| Item                                                   | Description                            |
|--------------------------------------------------------|----------------------------------------|
| <span id="x"></span><span id="X"></span>*x*<br/> | \[in\] The specified value.<br/> |



 

## Return Value

The base-e logarithm of the *x* parameter. If the *x* parameter is negative, this function returns indefinite. If the *x* parameter is 0, this function returns -INF.

## Type Description



| Name  | [**Template Type**](dx-graphics-hlsl-intrinsic-functions.md)                                                  | [**Component Type**](dx-graphics-hlsl-intrinsic-functions.md) | Size                           |
|-------|----------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|--------------------------------|
| *x*   | [**scalar**](dx-graphics-hlsl-intrinsic-functions.md), **vector**, or **matrix** | [**float**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)                        | any                            |
| *ret* | same as input *x*                                                                                              | [**float**](https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types)                        | same dimension(s) as input *x* |



 

## Minimum Shader Model

This function is supported in the following shader models.



| Shader Model                                                                       | Supported           |
|------------------------------------------------------------------------------------|---------------------|
| [Shader Model 2 (DirectX HLSL)](dx-graphics-hlsl-sm2.md) and higher shader models | yes                 |
| [Shader Model 1 (DirectX HLSL)](dx-graphics-hlsl-sm1.md)                          | yes (vs\_1\_1 only) |



 

## See also

<dl> <dt>

[**Intrinsic Functions (DirectX HLSL)**](dx-graphics-hlsl-intrinsic-functions.md)
</dt> </dl>

 

 





