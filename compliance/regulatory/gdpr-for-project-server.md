---
title: RGPD para Project Server
description: Aprenda a cumplir con los requisitos de la Normativa general de protección de datos (GDPR) en un Servidor de proyectos in situ.
f1.keywords:
- NOCSH
ms.author: mikeplum
author: MikePlumleyMSFT
manager: pamgreen
audience: ITPro
ms.topic: article
ms.service: O365-seccomp
localization_priority: Priority
titleSuffix: Microsoft GDPR
ms.custom: seo-marvel-apr2020
ms.collection: MS-Compliance
ms.openlocfilehash: 5f753b5d522649575f92178e6f9c932d5ae4725f
ms.sourcegitcommit: 626b0076d133e588cd28598c149a7f272fc18bae
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 11/30/2020
ms.locfileid: "49509885"
---
# <a name="gdpr-for-project-server"></a><span data-ttu-id="0114e-103">RGPD para Project Server</span><span class="sxs-lookup"><span data-stu-id="0114e-103">GDPR for Project Server</span></span>

<span data-ttu-id="0114e-p101">Project Server usa scripts personalizados para exportar y redactar datos de usuario en Project Web App. El proceso básico es:</span><span class="sxs-lookup"><span data-stu-id="0114e-p101">Project Server uses custom scripts to export and redact user data in Project Web App. The basic process is:</span></span>

1.  <span data-ttu-id="0114e-106">Busque los sitios de Project Web App en la granja de servidores.</span><span class="sxs-lookup"><span data-stu-id="0114e-106">Find the Project Web App sites in your farm.</span></span>

2.  <span data-ttu-id="0114e-107">Busque los proyectos en cada sitio que contiene el usuario.</span><span class="sxs-lookup"><span data-stu-id="0114e-107">Find the projects in each site that contain the user.</span></span>

3.  <span data-ttu-id="0114e-108">Exporte y revise los tipos de datos que desee revisar.</span><span class="sxs-lookup"><span data-stu-id="0114e-108">Export and review the types of data that you want to review.</span></span>

4.  <span data-ttu-id="0114e-109">Redacte los datos según sea necesario.</span><span class="sxs-lookup"><span data-stu-id="0114e-109">Redact data as needed.</span></span>

<span data-ttu-id="0114e-110">Estos pasos se tratan con detalle en los siguientes artículos:</span><span class="sxs-lookup"><span data-stu-id="0114e-110">These steps are covered in detail in the following articles:</span></span>

- [<span data-ttu-id="0114e-111">Exportar datos de usuario de Project Server</span><span class="sxs-lookup"><span data-stu-id="0114e-111">Export user data from Project Server</span></span>](/Project/export-user-data-from-project-server?toc=/Office365/Enterprise/toc.json)

- [<span data-ttu-id="0114e-112">Eliminar datos de usuario de Project Server</span><span class="sxs-lookup"><span data-stu-id="0114e-112">Delete user data from Project Server</span></span>](/Project/delete-user-data-from-project-server?toc=/Office365/Enterprise/toc.json)


<span data-ttu-id="0114e-p102">Tenga en cuenta que Project Server se basa en SharePoint Server y registra los eventos en los registros de ULS de SharePoint y la base de datos de uso. Para obtener más información, vea [RGPD para SharePoint Server](gdpr-for-sharepoint-server.md).</span><span class="sxs-lookup"><span data-stu-id="0114e-p102">Note that Project Server is built on top of SharePoint Server and logs events to the SharePoint ULS logs and Usage database. See [GDPR for SharePoint Server](gdpr-for-sharepoint-server.md) for more information.</span></span>
