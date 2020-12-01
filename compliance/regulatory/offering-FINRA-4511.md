---
title: Regla de la autoridad reguladora del sector financiero (FINRA) 4511 (c) Estados Unidos
description: Una empresa de evaluación independiente ha validado que Azure y Office 365 pueden ayudar a las empresas financieras a cumplir con los requisitos de retención de FINRA reglas 4511 registros y de almacenamiento inmutable.
keywords: Microsoft 365, cumplimiento, ofertas
localization_priority: None
ms.prod: microsoft-365-enterprise
ms.topic: article
f1.keywords:
- NOCSH
ms.author: robmazz
author: robmazz
manager: laurawi
audience: itpro
ms.collection:
- M365-security-compliance
- MS-Compliance
hideEdit: true
titleSuffix: Microsoft Compliance
ms.openlocfilehash: 06d95969cfcb748251352e79e21720380a54a395
ms.sourcegitcommit: 626b0076d133e588cd28598c149a7f272fc18bae
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 11/30/2020
ms.locfileid: "49510002"
---
# <a name="financial-industry-regulatory-authority-finra-rule-4511c-united-states"></a>Regla de la autoridad reguladora del sector financiero (FINRA) 4511 (c) Estados Unidos

## <a name="about-finra-rule-4511"></a>Acerca de la regla 4511 de FINRA

La [autoridad reguladora del sector financiero (FINRA)](https://www.finra.org/#/) es el cuerpo independiente más grande que regula a las empresas de valores con supervisión de más de 4.500 de empresas de corretaje en los Estados Unidos. Fue autorizado por el Congreso estadounidense "para proteger a los inversores de America asegurándose de que la industria de agentes del agente opera de manera equitativa y honesta".

En 2011, la Comisión estadounidense Security and Exchange Commission (SEC) aprobó la FINRA adopción de reglas de la SEC que rigen la retención de libros y registros en medios de almacenamiento electrónicos. La [regla 4511 de FINRA](https://www.finra.org/sites/default/files/NoticeDocument/p123548.pdf) especifica que "todos los libros y los registros que deben realizarse con arreglo a las reglas de FINRA se conservarán en un formato y en un medio que cumpla con la norma" marítima (Ley de intercambio de valores) Rule 17a-4 ".

Además, la regla de FINRA 4511 (c) requiere que las empresas conserven durante un período de al menos seis años los libros y los registros para los que no haya un período de retención especificado en las reglas aplicables de FINRA o mar. De hecho, si los libros y los registros pertenecen a una cuenta, el período de retención debe ser seis años después del cierre de la cuenta. De lo contrario, el período de retención es de seis años tras la creación de estos libros y registros.

## <a name="microsoft-and-finra-rule-4511c"></a>4511 de reglas de Microsoft y FINRA (c)

Los clientes de servicios financieros, que representan una de las industrias reguladas más intensamente del mundo, están sujetos a complejas provisiones como la retención de transacciones financieras y la comunicación relacionada en un estado no modificable y que no se puede borrar. Entre ellas se encuentra la regla 4511 de la autoridad reguladora del sector financiero (FINRA) que estipula estrictos requisitos para las entidades reguladas que eligen conservar libros y registros en medios de almacenamiento electrónicos. Los registros almacenados deben ser inalterables sin capacidad para modificarlos o eliminarlos hasta después del período de retención designado.

El almacenamiento de blobs inmutable de Microsoft Azure con bloqueo de directivas y Microsoft Office 365 con bloqueo de preservación puede ayudar a las instituciones financieras a cumplir los requisitos de almacenamiento inmutables de la regla de FINRA 4511 (c).

## <a name="microsoft-azure"></a>Microsoft Azure

Para evaluar el cumplimiento de Azure con FINRA regla 4511 (c), Microsoft reservó una empresa de evaluación independiente que se especializa en la administración de registros y el gobierno de la información, Cohasset Associates. El informe resultante, la [SEC 17a-4 (f) & CFTC 1,31 (c-d) Compliance Assessment: Microsoft Azure Storage](https://servicetrust.microsoft.com/ViewPage/MSComplianceGuide?command=Download&downloadType=Document&downloadId=19b08fd4-d276-43e8-9461-715981d0ea20&docTab=4ce99610-c9c0-11e7-8c2c-f908a777fa4d_GRC_Assessment_Reports), engloba el cumplimiento de Azure con FINRA Rule 4511 (c), que se pospone al formato y los requisitos de medios de la regla SEC 17a-4 (f).

Cohasset validó que [Azure inmutable Storage BLOB](https://docs.microsoft.com/azure/storage/blobs/storage-blob-immutable-storage) con la opción de bloqueo de Directiva, cuando se usa para conservar los blobs basados en tiempo en un formato no regrabable y no regrabable (Worm), cumple los requisitos de almacenamiento de FINRA relevantes. Cada BLOB (registro) está protegido contra modificaciones, sobrescritos o eliminaciones hasta que haya expirado el período de retención requerido y se hayan lanzado todas las retenciones legales asociadas.

Los proveedores de software y los asociados con cargas de trabajo confidenciales ahora pueden confiar en Azure inmutable BLOB Storage como una solución de nube de tienda integrada para la retención de registros y el almacenamiento inmutable. Las instituciones financieras ahora pueden crear sus propias aplicaciones aprovechando estas características a la vez que cumplen con los requisitos restantes.

## <a name="microsoft-365"></a>Microsoft 365

Para los requisitos de la [regla 4511 (c) de FINRA](https://docs.microsoft.com/microsoft-365/compliance/retention-regulatory-requirements#sec-17a-4f-finra-4511c-and-cftc-131c-d) , Cohasset validó que Microsoft 365 incluye características de archivado que permiten a los clientes regulados, incluidos los distribuidores de agentes, almacenar datos de manera que les ayuden a cumplir con los requisitos de la SEC para la retención de registros. Las características de retención de Microsoft 365 ayudan a conservar una amplia gama de datos, incluidos el correo electrónico, el correo de voz, los documentos compartidos, los mensajes instantáneos y los datos de terceros. En concreto, el archivado en Microsoft 365 permite a los clientes establecer directivas de retención de mensajería globales o granulares para almacenar datos durante un período definido y más adelante en un formato no regrabable y no borrable.

## <a name="microsoft-in-scope-cloud-services"></a>En el ámbito de los Servicios en la nube de Microsoft 

- [Azure](https://gallery.technet.microsoft.com/Overview-of-Azure-c1be3942)
- [Office 365](https://aka.ms/Office365ComplianceOfferings)

## <a name="audits-reports-and-certificates"></a>Auditorías, informes y certificados

### <a name="azure--finra-rule-4511c"></a>4511 de reglas de Azure & FINRA (c)

[Evaluación de cumplimiento de SEC 17a-4 (f) & CFTC 1,31 (c-d) de Azure Storage](https://servicetrust.microsoft.com/ViewPage/MSComplianceGuide?command=Download&downloadType=Document&downloadId=19b08fd4-d276-43e8-9461-715981d0ea20&docTab=4ce99610-c9c0-11e7-8c2c-f908a777fa4d_GRC_Assessment_Reports)

### <a name="office-365--finra-rule-4511c"></a>Office 365 & FINRA de reglas de 4511 (c)

[Archivado en Office 365, retención de datos y cumplimiento de la norma 17a-4 de la SEC](https://www.microsoft.com/microsoft-365/blog/2015/11/10/office-365-exchange-online-archiving-now-meets-sec-rule-17a-4-requirements/)

## <a name="how-to-implement"></a>Cómo se debe implementar

- **Reglamento de servicios financieros**: mapa de cumplimiento de los principios clave de los Estados Unidos para la informática en la nube y los servicios en línea de Microsoft. [Más información](https://servicetrust.microsoft.com/ViewPage/TrustDocuments?command=Download&downloadType=Document&downloadId=5b483567-00b0-4d86-96ae-ee887dadb61c&docTab=6d000410-c9e9-11e7-9a91-892aae8839ad_Compliance_Guides)
- **Guía de evaluación de riesgos y cumplimiento normativo**: Cree un modelo de gobernanza para la evaluación de riesgos sobre los Servicios en la Nube de Microsoft y las notificaciones reglamentarias. [Más información](https://servicetrust.microsoft.com/ViewPage/TrustDocuments?command=Download&downloadType=Document&downloadId=edee9b14-3661-4a16-ba83-c35caf672bd7&docTab=6d000410-c9e9-11e7-9a91-892aae8839ad_FAQ_and_White_Papers)
- **Casos de uso de servicios financieros**: Use visiones generales sobre los casos, tutoriales u otros recursos para compilar soluciones de Azure para servicios financieros. [Más información](https://docs.microsoft.com/azure/industry/financial/)

## <a name="resources"></a>Recursos

- [Programa de cumplimiento de servicios financieros de Microsoft](https://download.microsoft.com/download/6/4/7/64707E3E-6D3E-45D0-8207-A0EA3201B4A6/Microsoft%20Cloud%20-%20Financial%20Services%20Compliance%20Program%20\(Print\).pdf)
- [Servicios financieros y servicios empresariales en la nube de Microsoft](https://servicetrust.microsoft.com/viewpage/financialservicesoverview)
- [Cumplimiento de los servicios financieros en Azure](https://azure.microsoft.com/resources/videos/azurecon-2015-financial-services-compliance-in-azure/)
- [Herramienta de evaluación de riesgos en la nube para servicios financieros de Azure](https://servicetrust.microsoft.com/ViewPage/FFIECBlueprint?command=Download&downloadType=Document&downloadId=079a1973-711a-428f-9312-9ddd290cff7b&docTab=c726d5c0-2d1e-11e8-a485-57140ec19669_PaaS)
- [Directivas de retención de Microsoft Office 365](https://docs.microsoft.com/office365/securitycompliance/retention-policies)
- [Blog de servicios financieros de Microsoft](https://techcommunity.microsoft.com/t5/Financial-Services-Blog/bg-p/FinancialServicesBlog)
- [Cumplimiento en el centro de confianza de Microsoft ](https://www.microsoft.com/trust-center/compliance/compliance-overview)
