---
title: Propiedad Rowset (ADO) | Microsoft Docs
ms.prod: sql
ms.prod_service: connectivity
ms.technology: connectivity
ms.custom: ''
ms.date: 01/19/2017
ms.reviewer: ''
ms.topic: conceptual
apitype: COM
f1_keywords:
- ADORecordsetConstruction::PutRowset
- ADORecordsetConstruction::GetRowset
- ADORecordsetConstruction::Rowset
- ADORecordsetConstruction::put_Rowset
- ADORecordsetConstruction::get_Rowset
helpviewer_keywords:
- Rowset property [ADO]
ms.assetid: 7d359294-4ff2-47e0-8111-0c221b24d80e
author: MightyPen
ms.author: genemi
manager: craigg
ms.openlocfilehash: 4bb98bb7c23d20baf696c553a088cd03f2aa76e1
ms.sourcegitcommit: 61381ef939415fe019285def9450d7583df1fed0
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 10/01/2018
ms.locfileid: "47701663"
---
# <a name="rowset-property-ado"></a>Propiedad Rowset (ADO)
Obtiene o establece OLE DB **conjunto de filas** objeto desde/en un **ADORecordsetConstruction** objeto. Cuando se utiliza put_Rowset, el conjunto de filas se convierte en ADO **Recordset** objeto.  
  
 Lectura/escritura  
  
## <a name="syntax"></a>Sintaxis  
  
```  
HRESULT get_Rowset([out, retval] IUnknown** ppRowset);  
HRESULT put_Rowset([in] IUnknown* pRowset);  
```  
  
## <a name="parameters"></a>Parámetros  
 *ppRowset*  
 Puntero a OLE DB **conjunto de filas** objeto.  
  
 *PRowset*  
 OLE DB **conjunto de filas** objeto.  
  
## <a name="return-values"></a>Valores devueltos  
 Este método de propiedad devuelve los valores HRESULT estándar, incluidos S_OK y E_FAIL.  
  
## <a name="applies-to"></a>Se aplica a  
 [Interfaz ADORecordsetConstruction](../../../ado/reference/ado-api/adorecordsetconstruction-interface.md)
