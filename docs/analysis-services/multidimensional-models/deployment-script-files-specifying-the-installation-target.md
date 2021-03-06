---
title: Especificar el destino de instalación | Microsoft Docs
ms.date: 05/02/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: multidimensional-models
ms.topic: conceptual
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
ms.openlocfilehash: 0c9b5e72bdf58cf10f3ab30db720a2434ff9e41b
ms.sourcegitcommit: 2429fbcdb751211313bd655a4825ffb33354bda3
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/28/2018
ms.locfileid: "52540207"
---
# <a name="deployment-script-files---specifying-the-installation-target"></a>Archivos de Script de implementación: especificar el destino de instalación
[!INCLUDE[ssas-appliesto-sqlas-all-aas](../../includes/ssas-appliesto-sqlas-all-aas.md)]

  El [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] Asistente para implementación de lee la información del destino de instalación la \< *nombre del proyecto*> .deploymenttargets archivo. [!INCLUDE[ssBIDevStudioFull](../../includes/ssbidevstudiofull-md.md)] crea este archivo cuando se genera el proyecto de [!INCLUDE[msCoName](../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] . [!INCLUDE[ssBIDevStudioFull](../../includes/ssbidevstudiofull-md.md)] usa la base de datos y servidor especificados en el **implementación** página de la  *\<nombre del proyecto >* **las páginas de propiedades** cuadro de diálogo para crear el \< *nombre del proyecto*> archivo .targets.  
  
## <a name="modifying-the-installation-target-for-deployment"></a>Modificar el destino de instalación para la implementación  
 En algunas situaciones, puede que necesite implementar un proyecto de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] en una base de datos o en una instancia de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] que sea diferente a la especificada en la página **Implementación** . Por ejemplo, puede que desee implementar el proyecto en un servidor para realizar pruebas antes de la implementación y, a continuación, implementarlo en un servidor de producción. Puede que también desee implementar un proyecto finalizado y probado en varios servidores de producción de un clúster de equilibrio de carga de red (NLB), o en un servidor de ensayo y un servidor de producción.  
  
 Para implementar un proyecto de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] en una base de datos o una instancia de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] diferentes, puede cambiar el destino de instalación del archivo de entrada mediante uno de los métodos descritos en el siguiente procedimiento.  
  
#### <a name="to-change-the-installation-target-after-the-input-files-have-been-generated"></a>Para cambiar el destino de instalación después de haber generado los archivos de entrada  
  
-   Ejecute el Asistente para la implementación de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] de forma interactiva. En la página **Destino de instalación** , especifique un nuevo destino para la instancia de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] y la base de datos.  
  
     -o bien-  
  
-   Ejecute el Asistente para la implementación de [!INCLUDE[ssASnoversion](../../includes/ssasnoversion-md.md)] en el símbolo del sistema y ajuste el asistente de manera que se ejecute en modo de archivo de respuesta. Para obtener más información acerca del modo de archivo de respuesta, vea [Running the Analysis Services Deployment Wizard](../../analysis-services/multidimensional-models/running-the-analysis-services-deployment-wizard.md).  
  
     -o bien-  
  
-   Modificar el \< *nombre del proyecto*> archivo .deploymenttargets usando cualquier editor de texto.  
  
## <a name="see-also"></a>Vea también  
 [Especificar opciones de implementación de roles y particiones](../../analysis-services/multidimensional-models/deployment-script-files-partition-and-role-deployment-options.md)   
 [Especificar la configuración para la implementación de soluciones](../../analysis-services/multidimensional-models/deployment-script-files-solution-deployment-config-settings.md)   
 [Especificar opciones de procesamiento](../../analysis-services/multidimensional-models/deployment-script-files-specifying-processing-options.md)  
  
  
