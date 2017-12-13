---
title: "SNAInitLinkPerfmon2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 46233cc4-4053-4ea6-aabe-6bd4759c1376
caps.latest.revision: 3
---
# SNAInitLinkPerfmon
The **SNAInitLinkPerfmon** function initializes the Perfmon data structures and code for an SNA link. The user defines the address of a handle and a void pointer that are passed as parameters to this function. This function returns values in these parameters that are then used by subsequent calls to the Perfmon code. The SNA link driver should not modify the parameters returned by this function.  
  
## Syntax  
  
```  
  
            void SNAInitLinkPerfmon(   
    HANDLE *shrlockmutx,  
        void **shrptr  
);  
```  
  
#### Parameters  
 *shrlockmutx*  
 An address of a handle of a mutex used to protect a block of shared memory. This handle address is used when calling other Perfmon functions after initialization.  
  
 *shrptr*  
 The address of a pointer to a block of shared memory used by subsequent Perfmon functions.