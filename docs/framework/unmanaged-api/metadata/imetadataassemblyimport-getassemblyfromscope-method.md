---
title: "IMetaDataAssemblyImport::GetAssemblyFromScope Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "IMetaDataAssemblyImport.GetAssemblyFromScope"
apilocation: 
  - "mscoree.dll"
apitype: "COM"
f1_keywords: 
  - "IMetaDataAssemblyImport::GetAssemblyFromScope"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IMetaDataAssemblyImport::GetAssemblyFromScope method [.NET Framework metadata]"
  - "GetAssemblyFromScope method [.NET Framework metadata]"
ms.assetid: 0b437f70-561d-48c7-abe0-0cb9ace10c08
caps.latest.revision: 10
author: "mairaw"
ms.author: "mairaw"
manager: "wpickett"
---
# IMetaDataAssemblyImport::GetAssemblyFromScope Method
Gets a pointer to the assembly in the current scope.  
  
## Syntax  
  
```  
HRESULT GetAssemblyFromScope (  
    [out] mdAssembly  *ptkAssembly  
);  
```  
  
#### Parameters  
 `ptkAssembly`  
 [out] A pointer to the retrieved `mdAssembly` token that identifies the assembly.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** Cor.h  
  
 **Library:** Used as a resource in MsCorEE.dll  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [IMetaDataAssemblyImport Interface](../../../../docs/framework/unmanaged-api/metadata/imetadataassemblyimport-interface.md)