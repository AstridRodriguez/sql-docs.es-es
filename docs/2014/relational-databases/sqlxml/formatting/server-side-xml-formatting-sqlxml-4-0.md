---
title: Formato XML en el servidor (SQLXML 4.0) | Microsoft Docs
ms.custom: ''
ms.date: 03/06/2017
ms.prod: sql-server-2014
ms.reviewer: ''
ms.technology: xml
ms.topic: reference
helpviewer_keywords:
- FOR XML clause, formatting
- server-side XML formatting
ms.assetid: ae9ea068-0857-4505-a3b2-f53d256b644c
author: douglaslMS
ms.author: douglasl
manager: craigg
ms.openlocfilehash: 664149dd8aa1441e94dfdc4d11033e5d777a75fb
ms.sourcegitcommit: ceb7e1b9e29e02bb0c6ca400a36e0fa9cf010fca
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/03/2018
ms.locfileid: "52804577"
---
# <a name="server-side-xml-formatting-sqlxml-40"></a>Aplicación de formato XML en el servidor (SQLXML 4.0)
  En este tema se proporciona información sobre cómo aplicar formato a los documentos XML en el servidor desde los conjuntos de filas generados por consultas ejecutadas en una base de datos de Microsoft [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)].  
  
 En [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)], puede almacenar y recuperar los documentos XML en y de las tablas de base de datos. Para recuperar un documento XML, utilice la extensión de consulta FOR XML en una consulta SELECT.  
  
 Por ejemplo, suponga que una aplicación cliente ejecuta un comando en [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] que consta de los siguientes [!INCLUDE[tsql](../../../includes/tsql-md.md)] consulta:  
  
```  
SELECT FirstName, LastName  
FROM   Person.Contact  
FOR XML AUTO  
```  
  
 El servidor ejecuta la consulta en dos pasos. Primero, el servidor ejecuta esta instrucción SELECT:  
  
```  
SELECT FirstName, LastName  
FROM   Person.Contact  
```  
  
 A continuación, el servidor aplica la transformación FOR XML al conjunto de filas generado. A continuación, el XML resultante se envía al cliente como un conjunto de filas de una columna. En esta documentación, este proceso se conoce como aplicación de formato XML en el servidor.  
  
 En el servidor, puede especificar los modos siguientes con una cláusula FOR XML:  
  
-   RAW  
  
-   AUTO  
  
-   EXPLICIT  
  
 Para obtener más información acerca de la cláusula FOR XML, vea [generar XML mediante FOR XML](../../xml/for-xml-sql-server.md).  
  
## <a name="see-also"></a>Vea también  
 [Arquitectura de formato XML del lado cliente y servidor &#40;SQLXML 4.0&#41;](architecture-of-client-side-and-server-side-xml-formatting-sqlxml-4-0.md)   
 [Aplicación de formato XML del lado cliente &#40;SQLXML 4.0&#41;](client-side-xml-formatting-sqlxml-4-0.md)   
 [FOR XML &#40;SQL Server&#41;](../../xml/for-xml-sql-server.md)  
  
  
