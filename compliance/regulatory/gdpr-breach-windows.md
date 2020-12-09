---
title: Notificación del servicio de tratamiento de datos para Windows Enterprise en virtud del RGPD
description: Cómo el servicio de tratamiento de datos para Windows Enterprise protege contra las infracciones de datos personales y cómo Microsoft responde y le avisa si se produce una infracción.
keywords: Servicio de tratamiento de datos para Windows Enterprise, Microsoft 365, documentación de Microsoft 365, RGPD
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
ms.prod: microsoft-365-enterprise
ms.topic: article
f1.keywords:
- NOCSH
ms.author: robmazz
author: robmaz
manager: laurawi
ms.reviewer: delinat
audience: itpro
ms.collection:
- GDPR
- M365-security-compliance
- MS-Compliance
ms.openlocfilehash: d6052a046dc13d2579806519bc579b7530132a33
ms.sourcegitcommit: b366fb7c148b4da40f8c5d8ff41adbff0bcb850e
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 12/07/2020
ms.locfileid: "49585395"
---
# <a name="data-processor-service-for-windows-enterprise-breach-notification-under-the-gdpr"></a>Notificación de infracción del servicio de tratamiento de datos para Windows Enterprise en virtud del RGPD

>[!NOTE]
>Este tema está dirigido a los participantes en el servicio de tratamiento de datos para el programa de vista previa de Windows Enterprise y requiere aceptar condiciones específicas de uso. Para obtener más información sobre el programa y aceptar las condiciones de uso, consulte [https://aka.ms/WindowsEnterprisePublicPreview](https://aka.ms/WindowsEnterprisePublicPreview).

El servicio de tratamiento de datos de Microsoft para Windows Enterprise se toma muy en serio sus obligaciones en virtud del Reglamento General de Protección de Datos (RGPD). El servicio de tratamiento de datos de Microsoft para Windows Enterprise toma amplias medidas de seguridad para proteger contra las infracciones de datos. Entre ellas se encuentran los equipos dedicados de administración de amenazas que trabajan proactivamente para prever, impedir y mitigar los accesos malintencionados.  Las medidas de seguridad interna, como el análisis de puertos, el análisis de vulnerabilidades perimetrales y la detección de intrusiones, detectan e impiden los accesos malintencionados, al igual que los procesos de seguridad automatizados, las directivas integrales de privacidad y protección de la información, y la formación en seguridad y privacidad que se imparte a todo el personal. 

La seguridad está integrada en el servicio de tratamiento de datos de Microsoft para Windows Enterprise desde los cimientos, empezando por el [Ciclo de vida de desarrollo de seguridad](https://www.microsoft.com/sdl/), un proceso de desarrollo obligatorio que incorpora metodologías de privacidad por diseño y privacidad predeterminada. El principio fundamental de la estrategia de seguridad de Microsoft es "asumir que se producirán infracciones", lo que supone una extensión intensiva de la estrategia de defensa. Al poner a prueba de forma constante las funcionalidades de seguridad del servicio de tratamiento de datos para Windows Enterprise, Microsoft puede ir un paso por delante de las amenazas emergentes. Para obtener más información sobre la seguridad del servicio de tratamiento de datos para Windows Enterprise, consulte los siguientes [recursos](https://www.microsoft.com/TrustCenter/Security/windows10-security). El servicio de tratamiento de datos para Windows Enterprise responde a una posible infracción de datos conforme al proceso de respuesta a incidentes de seguridad. La respuesta a incidentes de seguridad del servicio de tratamiento de datos para Windows Enterprise se implementa mediante un proceso de cinco fases: detección, evaluación, diagnóstico, estabilización y cierre. El equipo de respuesta a incidentes de seguridad puede alternar entre las fases de diagnóstico y estabilización a medida que avanza la investigación. A continuación, se muestra una descripción general del proceso de respuesta a incidentes de seguridad: 

|**Stage**|**Descripción**|
|:------- |:------------- |
| **_1: Detección_* _ | Primera indicación de un posible incidente. |
| _*_2: evaluación_*_ | Un miembro del equipo de respuesta ante incidentes evalúa el impacto y la gravedad del evento. Según las pruebas, la evaluación puede o no provocar una escalación al equipo de respuesta de seguridad. |
| _*_3: diagnóstico_*_ | Los expertos en respuestas de seguridad llevan a cabo la investigación técnica o forense, la identificación de estrategias de contención, la mitigación y la aplicación de soluciones alternativas. Si el equipo de seguridad cree que los datos del cliente pueden haberse expuesto a una ejecución individual ilegal o no autorizada, se inicia el proceso de notificación de incidentes del cliente de forma paralela. |
| _*_4: estabilización y recuperación_*_ | El equipo de respuesta ante incidentes crea un plan de recuperación para mitigar el problema. De forma inmediata y en paralelo al diagnóstico, pueden darse pasos de contención de crisis, como poner en cuarentena los sistemas afectados. Pueden planearse mitigaciones a largo plazo después de solucionar el riesgo inmediato. |
| _*_5: Cierre y análisis posterior_*_ | El equipo de respuesta ante incidentes crea un análisis posterior que expone los detalles del incidente con la intención de revisar directivas, procedimientos y procesos y evitar que se vuelva a producir. |

Los procesos de detección usados por el servicio de tratamiento de datos de Microsoft para Windows Enterprise están diseñados para detectar eventos que puedan poner en riesgo la confidencialidad, integridad y disponibilidad del servicio de tratamiento de datos para Windows Enterprise. Varios eventos pueden desencadenar una investigación: 

 - Alertas automatizadas del sistema mediante marcos internos de monitoreo y alerta. Estas alertas pueden interferir con alarmas basadas en firmas, como antimalware, detección de intrusiones o mediante algoritmos diseñados para identificar actividades previstas y generar alertas ante anomalías.
 - Informes internos de los servicios Microsoft ejecutándose en Microsoft Azure y Azure Government.
 - Las vulnerabilidades de seguridad se notifican al [Centro de respuestas de seguridad de Microsoft (MSRC)](https://technet.microsoft.com/security/dn440717) a través de [secure@microsoft.com] (mailto:secure@microsoft.com). El Centro de respuestas de seguridad de Microsoft trabaja con asociados e investigadores de seguridad de todo el mundo para impedir que se produzcan incidentes de seguridad y mejorar la seguridad de los productos de Microsoft.
 - Los informes de cliente a través del Portal de soporte técnico al cliente o el portal de administración de Microsoft Azure y Azure Government, que describen la actividad sospechosa atribuida a la infraestructura de Azure (en lugar de la actividad que se produce en el ámbito de responsabilidad del cliente).
 - Actividad de los [equipos de seguridad rojo y azul](https://azure.microsoft.com/blog/red-teaming-using-cutting-edge-threat-simulation-to-harden-the-microsoft-enterprise-cloud/). Esta estrategia usa un equipo Rojo de expertos altamente cualificados en seguridad ofensiva de Microsoft para descubrir y atacar debilidades potenciales en los servicios de Azure. El equipo Azul de respuesta de seguridad debe detectar la actividad del equipo rojo y defenderse contra ella. Las acciones de los equipos Rojo y Azul se usan para comprobar que los esfuerzos de respuesta de seguridad de Azure son efectivos a la hora de administrar incidentes de seguridad. Las actividades de los equipos de seguridad Rojo y Azul se basan en las reglas de compromiso para garantizar la protección de los datos de clientes.
 - Remisiones a una instancia superior por parte de los operadores de servicios de Azure. Los empleados de Microsoft están preparados para identificar y escalar los posibles problemas de seguridad.

 ## <a name="data-processor-service-for-windows-enterprise-data-breach-response"></a>Respuesta a infracciones del servicio de tratamiento de datos para Windows Enterprise 

 Microsoft asigna los niveles de prioridad y gravedad adecuados investigando el impacto funcional, la capacidad de recuperación y el impacto de la información del incidente. Tanto la prioridad como la gravedad pueden cambiar a lo largo de la investigación, en función de nuevos resultados y conclusiones. Los eventos de seguridad que impliquen un riesgo inminente o confirmado para los datos de los clientes se tratan como muy graves y se trabaja de forma urgente para su resolución. El servicio de tratamiento de datos de Microsoft para Windows Enterprise clasifica la información sobre el impacto del incidente en las siguientes categorías de vulneraciones: 

| _ *Categoría** | **Definición** |
|:------------ |:-------------- |
| **_Ninguna_* _ | No se ha extraído, cambiado, eliminado o comprometido ninguna información. |
| _*_Vulneración de privacidad_*_ | Se ha eliminado o se ha accedido a datos personales confidenciales de contribuyentes, empleados, beneficiarios, etc. |
| _*_Vulneración de propiedad_*_ | Se ha eliminado o se ha accedido a información no clasificada de propiedad, como información de infraestructura crítica protegida (PCII). |
| _*_Pérdida de integridad_*_ | Se ha modificado o eliminado información confidencial o de propiedad. |

El equipo de respuesta de seguridad trabaja con los ingenieros de seguridad del servicio de tratamiento de datos de Microsoft para Windows Enterprise y con los expertos en la materia para clasificar el evento en función de los datos reales que se obtienen de las evidencias. Se puede clasificar un evento de seguridad como: 

 - _*Falso positivo**: un evento que cumple con los criterios de detección pero que se considera parte de una práctica comercial normal y es preciso que sea filtrado. El equipo de servicio se ocupará de identificar la causa principal de los falsos positivos y afrontarlos de forma sistemática aprovechando las fuentes de detección y afinarlas en caso necesario. 
 - **Incidente de seguridad**: un incidente en el que se produce un acceso ilegal a los datos de los clientes o de soporte técnico almacenados en equipos o instalaciones de Microsoft; o un acceso no autorizado a dichos equipos o instalaciones, que da como resultado la pérdida, divulgación o modificación de datos de clientes o de soporte técnico. 
 - **Incidente de seguridad que debe notificarse al cliente (CRSI):** un acceso o uso ilegal o no autorizado a sistemas, equipos o instalaciones de Microsoft, que resulta en la divulgación, modificación o pérdida de datos de clientes. 
 - **Infracción de privacidad**: caso específico de un incidente relativo a la seguridad que involucra datos personales. Los procedimientos de control son los mismos que los de un incidente de seguridad. 

 Para que se declare una CRSI, Microsoft debe determinar que el acceso no autorizado a los datos del cliente se ha producido, o es probable que lo haya hecho, o existe un compromiso legal o contractual que fuerce la notificación. Es preferible, aunque no se requiere, que se conozcan los pasos de impacto del cliente específico, acceso a los recursos y reparación. Por lo general, se declara que una incidencia es un CRSI tras la conclusión de la etapa de diagnóstico de una incidencia de seguridad; sin embargó, la declaración puede producirse en cualquier momento si la información pertinente se encuentra disponible. El administrador de la incidencia de seguridad debe establecer pruebas más allá de la duda razonable de que se ha producido un evento del que informar para iniciar la ejecución del proceso de notificación de incidencias del cliente. 

Durante la investigación, el equipo de respuesta de seguridad trabaja junto a asistentes legales de todo el mundo para ayudar a garantizar que los análisis se realizan siguiendo los compromisos y las obligaciones legales con los clientes. También hay importantes restricciones sobre el visionado de datos de clientes y sistemas, además de sobre su manejo en varios entornos operativos. Los datos confidenciales y de los clientes no se transfieren fuera del entorno de producción sin la aprobación escrita del administrador de incidencias registrada en el tique de incidencia correspondiente. 

Microsoft comprueba que el riesgo para los clientes y negocios se ha contenido con éxito y que las medidas correctivas se han implementado. En caso necesario, se llevan a cabo pasos de atenuación de emergencia para resolver los riesgos de seguridad inmediatos asociados con el evento. 

Microsoft también realiza un análisis final interno para las vulneraciones de datos. Como parte de este ejercicio, se evalúan los procedimientos operativos y la suficiencia de respuesta y se identifican e implementan las actualizaciones necesarias para la respuesta ante incidentes de seguridad o procesos relacionados. Los análisis finales internos para las vulneraciones de datos son registros muy confidenciales no disponibles para los clientes. Pero los análisis posteriores pueden resumirse e incluirse en otras notificaciones de eventos del cliente. Estos informes se proporcionan a auditores externos para que los revisen como parte del ciclo de auditoría rutinario de Windows Enterprise. 

## <a name="customer-notice"></a>Aviso al cliente

El servicio de tratamiento de datos de Microsoft para Windows Enterprise envía notificaciones a los clientes y a las autoridades competentes sobre las infracciones de datos según sea necesario. Microsoft se apoya en una sólida compartimentación interna en las operaciones del servicio de tratamiento de datos para Windows Enterprise. También son sólidos los registros de flujo de datos. Una de las ventajas de este diseño es que permite determinar a qué clientes específicos se aplican la mayoría de los incidentes. El objetivo es notificar a los clientes afectados a la mayor brevedad y de manera precisa y útil que se ha producido una vulneración de sus datos. 

Una vez que se declara un CRSI, el proceso de notificación tiene lugar tan pronto como sea posible, pero hay que considerar los riesgos de seguridad de actuar demasiado rápido. Por lo general, el proceso de redacción de notificaciones se produce durante la investigación de la incidencia. Los avisos se entregan a los clientes en un plazo máximo de 72 horas desde el momento en el que se declara la infracción, excepto en las siguientes circunstancias: 

 - Microsoft considera que el acto de realizar una notificación incrementará el riesgo para otros clientes. Por ejemplo, el acto de enviar una notificación puede alertar a un adversario e impedir una corrección adecuada. 
 - Otras circunstancias inusuales o extremas expuestas por el departamento legal de Microsoft, asuntos legales y externos corporativos (CELA), y el administrador de incidentes ejecutivo. 

 El servicio de tratamiento de datos de Microsoft para Windows Enterprise proporciona a los clientes información detallada, lo que les permite realizar investigaciones internas y satisfacer los compromisos contraídos con los usuarios finales sin retrasar indebidamente el proceso de notificación. 

La notificación de una vulneración de datos personales se entregará al cliente por cualquier medio elegido por Microsoft, incluyendo el correo electrónico. La notificación de una vulneración de datos se enviará a la lista de contactos de seguridad proporcionada en Azure Security Center, que puede configurarse siguiendo las [directrices de implementación](https://docs.microsoft.com/azure/security-center/security-center-provide-security-contact-details). Si no se proporciona información de contacto en el centro de seguridad de Azure, la notificación se envía a uno o varios administradores de una suscripción de Azure. Para asegurar que la notificación pueda entregarse correctamente, es responsabilidad del cliente proporcionar información de contacto administrativa correcta en cada suscripción y portal de servicios en línea aplicables.

El equipo del servicio de tratamiento de datos para Windows Enterprise también puede elegir enviar notificaciones a otros miembros del personal de Microsoft, como, por ejemplo, el servicio de atención al cliente, los administradores de cuentas de clientes o los administradores de cuentas técnicas. Por lo general, estas personas suelen tener relaciones estrechas con los clientes y pueden hacer que las correcciones se lleven a cabo más rápidamente. 

Para obtener más información sobre cómo Microsoft detecta y responde ante una vulneración de datos personales, vea [Notificación de vulneraciones de datos según el RGPD](https://servicetrust.microsoft.com/ViewPage/GDPRBreach) en el Portal de confianza del servicio.
