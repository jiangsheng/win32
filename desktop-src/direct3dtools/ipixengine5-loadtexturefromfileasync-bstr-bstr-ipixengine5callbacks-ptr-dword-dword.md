---
Description: Loads a texture from a file and notifies the host asynchronously when it completes.
MS-HAID: vspixengine.IPixEngine5\_LoadTextureFromFileAsync\_BSTR\_BSTR\_IPixEngine5Callbacks\_ptr\_DWORD\_DWORD
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: IPixEngine5::LoadTextureFromFileAsync method
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.ipixengine5_loadtexturefromfileasync_bstr_bstr_ipixengine5callbacks_ptr_dword_dword"></span>IPixEngine5::LoadTextureFromFileAsync method

Loads a texture from a file and notifies the host asynchronously when it completes.

## Syntax


```C++
);
```

## Parameters

*fileName*   
A COM string containing the name of the texture file.

*histogramDataFileName*   
A COM string containing the name of the histogram data file associated with the texture.

*callbacks*   
The address of an object that provides the IPixEngine5 callbacks interface.

*requestCookie*   
A cookie that uniquely idenfies the request, and can be used to signal for it to be canceled.

*progressIntervalMsecs*   
Not used.

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Header</p></td><td>Vspixengine.h</td></tr></tbody></table>

## <span id="see_also"></span>See also

[**IPixEngine5**](https://msdn.microsoft.com/library/windows/desktop/mt432755)

 

 


