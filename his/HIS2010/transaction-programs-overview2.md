---
title: "Transaction Programs Overview2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 14ddee80-cd88-4b1a-8ed9-15ba0bf098ca
caps.latest.revision: 3
---
# Transaction Programs Overview
A processing task accomplished by programs using Advanced Program-to-Program Communications (APPC) is called a transaction. Consequently, programs that use APPC are called transaction programs (TP)s. These programs communicate as peers, on an equal (rather than hierarchical) basis. The TPs use APPC verbs to exchange status information and application data. Each TP uses APPC verbs to supply parameters to APPC, which performs the desired function and returns parameters to the TP.  
  
 TPs distributed across a local or wide area network perform distributed transaction processing.  
  
 This section describes how to write TPs and how to configure the systems on which TPs run. The topics in this section cover the following general areas:  
  
-   Understanding fundamental concepts related to TPs  
  
-   Designing and coding TPs  
  
-   Configuring registry and environment variables for invokable TPs  
  
-   Configuring [!INCLUDE[hishostintegrationserver2009](../includes/hishostintegrationserver2009-md.md)] to work with your TPs  
  
-   Sync Point Level 2 support  
  
 This section contains:  
  
-   [Communication between TPs](../HIS2010/communication-between-tps1.md)  
  
-   [Designing and Coding TPs](../HIS2010/designing-and-coding-tps1.md)  
  
-   [Configuring Invokable TPs](../HIS2010/configuring-invokable-tps2.md)  
  
-   [Configuring TPs on Host Integration Server](../HIS2010/configuring-tps-on-host-integration-server2.md)  
  
-   [Arranging TPs Within an SNA Network](../HIS2010/arranging-tps-within-an-sna-network1.md)  
  
-   [Sync Point Level 2 Support in Host Integration Server](../HIS2010/sync-point-level-2-support-in-host-integration-server1.md)