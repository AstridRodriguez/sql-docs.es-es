---
title: Broker Activation (objeto de SQL Server) | Microsoft Docs
ms.custom: ''
ms.date: 06/13/2017
ms.prod: sql-server-2014
ms.reviewer: ''
ms.technology: performance
ms.topic: conceptual
helpviewer_keywords:
- SQLServer:Broker Activation
- Broker Activation object
ms.assetid: cd9b6880-c924-42c7-b333-09c303317c0b
author: MikeRayMSFT
ms.author: mikeray
manager: craigg
ms.openlocfilehash: 59c66bc237b496fd913658f168b7b1c0089fdc00
ms.sourcegitcommit: ceb7e1b9e29e02bb0c6ca400a36e0fa9cf010fca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2018
ms.locfileid: "52803447"
---
# <a name="sql-server-broker-activation-object"></a>Broker Activation (objeto de SQL Server)
  El objeto de rendimiento **SQLServer:BrokerActivation** incluye contadores de rendimiento que aportan información acerca de la activación de procedimientos almacenados. En la siguiente tabla se enumeran los contadores incluidos en este objeto.  
  
|Contadores de Broker Activation de SQL Server|Descripción|  
|-------------------------------------------|-----------------|  
|**Procedimientos almacenados invocados/seg.**|Este contador informa del número total de procedimientos de activación almacenados que han invocado todos los monitores de cola en la instancia por segundo.|  
|**Límite de tareas alcanzado**|Este contador informa del número total de veces que un monitor de cola habría iniciado una tarea y no lo hizo porque ya se estaba ejecutando el máximo de tareas de la cola.|  
|**Límite de tareas alcanzado/seg.**|Este contador informa del número de veces por segundo que un monitor de cola habría iniciado una tarea y no lo hizo porque ya se estaba ejecutando el máximo de tareas de la cola.|  
|**Tareas anuladas/seg.**|Este contador informa del número de tareas de procedimiento almacenado de activación que finalizan con un error o que un monitor de cola anula porque no recibe mensajes.|  
|**Tareas en ejecución**|Este contador informa del número de procedimientos almacenados de activación que se están ejecutando.|  
|**Tareas iniciadas/seg.**|Este contador informa del número de procedimientos de activación almacenados que han iniciado por segundo todos los monitores de cola en la instancia.|  
  
## <a name="see-also"></a>Vea también  
 [sys.dm_broker_activated_tasks &#40;Transact-SQL&#41;](/sql/relational-databases/system-dynamic-management-views/sys-dm-broker-activated-tasks-transact-sql)   
 [sys.dm_broker_queue_monitors &#40;Transact-SQL&#41;](/sql/relational-databases/system-dynamic-management-views/sys-dm-broker-queue-monitors-transact-sql)   
 [Supervisar el uso de recursos&#40;Monitor de sistema&#41;](monitor-resource-usage-system-monitor.md)  
  
  
