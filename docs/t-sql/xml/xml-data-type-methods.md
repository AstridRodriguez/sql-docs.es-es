---
title: Métodos de tipo de datos xml | Microsoft Docs
ms.custom: ''
ms.date: 03/16/2017
ms.prod: sql
ms.reviewer: ''
ms.technology: t-sql
ms.topic: language-reference
dev_langs:
- TSQL
helpviewer_keywords:
- xml data type [SQL Server], methods
- methods [XML in SQL Server]
ms.assetid: d112b9c9-be9f-435c-a9e6-d21b65778fb7
author: MightyPen
ms.author: genemi
manager: craigg
ms.openlocfilehash: 715effa0eb16a298f5064f08d2751df07bfa8677
ms.sourcegitcommit: dfb1e6deaa4919a0f4e654af57252cfb09613dd5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 02/11/2019
ms.locfileid: "56020217"
---
# <a name="xml-data-type-methods"></a>Métodos de tipo de datos xml
[!INCLUDE[tsql-appliesto-ss2012-xxxx-xxxx-xxx-md](../../includes/tsql-appliesto-ss2012-xxxx-xxxx-xxx-md.md)]

  Puede usar los métodos del tipo de datos **xml** para realizar una consulta en una instancia XML almacenada en una variable o columna de tipo **xml**. En los temas de esta sección se describe cómo usar los métodos del tipo de datos **xml**.  
  
## <a name="in-this-section"></a>En esta sección  
  
|Tema|Descripción|  
|-----------|-----------------|  
|[Método query&#40;&#41; &#40;tipo de datos xml&#41;](../../t-sql/xml/query-method-xml-data-type.md)|Describe cómo utilizar el método query() para realizar una consulta en una instancia XML.|  
|[Método value&#40;&#41; &#40;tipo de datos xml&#41;](../../t-sql/xml/value-method-xml-data-type.md)|Describe cómo utilizar el método value() para recuperar un valor de tipo SQL de una instancia XML.|  
|[Método exist&#40;&#41; &#40;tipo de datos xml&#41;](../../t-sql/xml/exist-method-xml-data-type.md)|Describe cómo utilizar el método exist() para determinar si una consulta devuelve un resultado no vacío.|  
|[Método modify&#40;&#41; &#40;tipo de datos xml&#41;](../../t-sql/xml/modify-method-xml-data-type.md)|Describe cómo usar el método modify() para especificar instrucciones de [Lenguaje de manipulación de datos XML &#40;XML DML&#41;](../../t-sql/xml/xml-data-modification-language-xml-dml.md) para realizar las actualizaciones.|  
|[Método nodes&#40;&#41; &#40;tipo de datos xml&#41;](../../t-sql/xml/nodes-method-xml-data-type.md)|Describe cómo utilizar el método nodes() para dividir XML en varias filas, lo que propaga partes de documentos XML en conjuntos de filas.|  
|[Enlace de datos relacionales dentro de datos XML](../../t-sql/xml/binding-relational-data-inside-xml-data.md)|Describe cómo enlazar datos no XML dentro de XML.|  
|[Directrices para usar los métodos del tipo de datos xml](../../t-sql/xml/guidelines-for-using-xml-data-type-methods.md)|Describe instrucciones para usar los métodos de tipo de datos **xml**.|  
  
 Estos métodos se llaman mediante la sintaxis de llamada de métodos de tipo definido por el usuario. Por ejemplo:  
  
```  
SELECT XmlCol.query(' ... ')  
FROM   Table  
```  
  
> [!NOTE]  
>  Los métodos de tipo de datos **xml** **query()**, **value()** y **exist()** devuelven NULL si se ejecutan en una instancia NULL de XML. Además, **modify()** no devuelve ningún resultado, pero **nodes()** devuelve conjuntos de filas y un conjunto de filas vacío con una entrada NULL.  
  
## <a name="see-also"></a>Consulte también  
 [Comparar XML con tipo y XML sin tipo](../../relational-databases/xml/compare-typed-xml-to-untyped-xml.md)   
 [Crear instancias de datos XML](../../relational-databases/xml/create-instances-of-xml-data.md)  
  
  
