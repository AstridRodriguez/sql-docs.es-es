---
title: Propiedad RSWindowsExtendedProtectionLevel (WMI MSReportServer_ConfigurationSetting) | Microsoft Docs
ms.custom: ''
ms.date: 06/14/2017
ms.prod: sql-server-2014
ms.reviewer: ''
ms.technology:
- reporting-services-native
ms.topic: conceptual
ms.assetid: 162ffe86-69c3-49d2-b9ed-49d097c05551
author: markingmyname
ms.author: maghan
manager: kfile
ms.openlocfilehash: 3eed88e178311fc47cb0feae43d63673ff5211ae
ms.sourcegitcommit: dfb1e6deaa4919a0f4e654af57252cfb09613dd5
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 02/11/2019
ms.locfileid: "56022096"
---
# <a name="rswindowsextendedprotectionlevel-property-wmi-msreportserverconfigurationsetting"></a>Propiedad RSWindowsExtendedProtectionLevel (WMI MSReportServer_ConfigurationSetting)
  Devuelve un valor de cadena que indica el nivel de protección con que se ha configurado el servidor de informes. Esta propiedad es de solo lectura.  
  
## <a name="syntax"></a>Sintaxis  
  
```vb  
Public Dim RSWindowsExtendedProtectionLevel As String  
```  
  
```csharp  
public string RSWindowsExtendedProtectionLevel;  
```  
  
## <a name="remarks"></a>Comentarios  
 Devuelve un valor de cadena que indica el nivel de protección con que se ha configurado el servidor de informes. Si el servidor de informes al que se conecta el proveedor de WMI no admite la protección extendida, se devuelve "" (cadena vacía). En la lista siguiente se muestran los valores válidos:  
  
 `"Off" | "Allow" | "Require"`  
  
## <a name="example-code"></a>Código de ejemplo  
 [Clase MSReportServer_ConfigurationSetting](msreportserver-configurationsetting-class.md)  
  
## <a name="see-also"></a>Vea también  
 [Propiedad RSWindowsExtendedProtectionScenario &#40;MSReportServer_ConfigurationSetting de WMI&#41;](rswindowsextendedprotectionscenario-property.md)   
 [Método SetExtendedProtectionSettings &#40;WMI MSReportServer_ConfigurationSetting&#41;](configurationsetting-method-setextendedprotectionsettings.md)   
 [Protección ampliada para la autenticación con Reporting Services](../security/extended-protection-for-authentication-with-reporting-services.md)   
 [Archivo de configuración RSReportServer](../report-server/rsreportserver-config-configuration-file.md)  
  
  
