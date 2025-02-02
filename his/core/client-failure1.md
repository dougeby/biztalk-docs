---
description: "Learn more about: Client Failure"
title: "Client Failure1 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: c5041852-076a-4829-84df-72730a3dd6c6
caps.latest.revision: 3
author: "christopherhouser"
ms.author: "hisdocs"
manager: "anneta"
---
# Client Failure
If the client computer fails, the local node terminates the application's PLU-SLU session (if it is active) by sending **TERM-SELF**. The system services control point (SSCP) and primary logical unit (PLU) connections are both marked as closed and cannot be reused without being reopened. Internally, the local node treats such a failure in the same way as the receipt of a [Close(SSCP) Request](./close-sscp-request2.md) from the application.  
  
## See Also  
 [Application CANCEL](../core/application-cancel2.md)   
 [Direction after Receiving a Negative Response](../core/direction-after-receiving-a-negative-response1.md)   
 [Direction after Sending a Negative Response](../core/direction-after-sending-a-negative-response2.md)   
 [Critical Failure](../core/critical-failure2.md)   
 [RQR and CLEAR](../core/rqr-and-clear1.md)   
 [STSN](../core/stsn2.md)   
 [Link Service Failure](../core/link-service-failure1.md)   
 [Local Node Failure](../core/local-node-failure2.md)
