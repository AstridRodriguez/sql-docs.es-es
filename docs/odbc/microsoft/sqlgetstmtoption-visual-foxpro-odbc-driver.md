---
title: SQLGetStmtOption (controlador ODBC de Visual FoxPro) | Microsoft Docs
ms.custom: ''
ms.date: 01/19/2017
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ''
ms.technology: connectivity
ms.topic: conceptual
helpviewer_keywords:
- SQLGetStmtOption function [ODBC], Visual FoxPro ODBC Driver
ms.assetid: 984a8b1d-f12c-420c-8be4-f555114c764b
author: MightyPen
ms.author: genemi
manager: craigg
ms.openlocfilehash: 373f5e13712ef7b0864401ea3d2c204cb03ebb09
ms.sourcegitcommit: 61381ef939415fe019285def9450d7583df1fed0
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2018
ms.locfileid: "47647003"
---
# <a name="sqlgetstmtoption-visual-foxpro-odbc-driver"></a>SQLGetStmtOption (controlador ODBC de Visual FoxPro)
> [!NOTE]  
>  Este tema contiene información específica del controlador ODBC de Visual FoxPro. Para obtener información general acerca de esta función, vea el tema correspondiente en [referencia de la API de ODBC](../../odbc/reference/syntax/odbc-api-reference.md).  
  
 Soporte técnico: completo  
  
 Conformidad de la API de ODBC: Uno de nivel  
  
 Devuelve el valor actual de una opción de instrucción.  
  
|*fOption*|Devuelve|  
|---------------|-------------|  
|SQL_GET_BOOKMARK|valor entero de 32 bits que es el marcador para el número de registro actual|  
|SQL_ROW_NUMBER|entero de 32 bits que especifica la posición de la fila actual en el resultado establecido|  
|SQL_TRANSLATE_DLL|Error: "el controlador no capaz."|  
  
 El controlador ODBC de Visual FoxPro no tiene ninguna traducción de archivos DLL.  
  
 Para obtener más información, consulte [SQLGetStmtOption](../../odbc/reference/syntax/sqlgetstmtoption-function.md) en el *referencia del programador de ODBC*.
