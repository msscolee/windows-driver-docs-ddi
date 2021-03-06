---
UID: NF:ntintsafe.RtlShortToUIntPtr
title: RtlShortToUIntPtr function (ntintsafe.h)
description: Converts a value of type SHORT to a value of type UINT_PTR.
old-location: kernel\rtlshorttouintptr.htm
tech.root: kernel
ms.assetid: C9E81C1A-56F2-414F-8FE5-847E291A022A
ms.date: 04/30/2018
ms.keywords: RtlShortToUIntPtr, RtlShortToUIntPtr function [Kernel-Mode Driver Architecture], kernel.rtlshorttouintptr, ntintsafe/RtlShortToUIntPtr
ms.topic: function
req.header: ntintsafe.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: 
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
- Ntintsafe.h
api_name:
- RtlShortToUIntPtr
product:
- Windows
targetos: Windows
req.typenames: 
---

# RtlShortToUIntPtr function


## -description


Converts a value of type <b>SHORT</b> to a value of type <b>UINT_PTR</b>.


## -parameters




### -param sOperand [in]

The value to be converted.


### -param puResult [out]

A pointer to the converted value. In the case where the conversion causes a truncation of the original value, the function returns STATUS_INTEGER_OVERFLOW and this parameter is not valid.


## -remarks



This is one of a set of inline functions designed to provide type conversions and perform validity checks with minimal impact on performance.

This function uses the following alternate name:

<ul>
<li>RtlShortToSizeT
</li>
<li>RtlInt16ToUIntPtr
</li>
<li>RtlInt16ToSizeT
</li>
</ul>


