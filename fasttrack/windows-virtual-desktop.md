---
title: Виртуальный рабочий стол Windows
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack предоставляет рекомендации по развертыванию виртуальных настольных компьютеров Windows, чтобы помочь вам на борту этого рабочего стола.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996242"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="76d81-103">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="76d81-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="76d81-104"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="76d81-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="76d81-105"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="76d81-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="76d81-106"><strong>Требования к исходной среде</strong></span><span class="sxs-lookup"><span data-stu-id="76d81-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="76d81-107">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="76d81-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="76d81-108">FastTrack предоставляет рекомендации по развертыванию виртуальных настольных компьютеров Windows, чтобы помочь вам в этой службе виртуализации настольных компьютеров и приложений с легкостью использовать много сеансы Windows 10, оптимизированные для Microsoft 365 Apps для предприятия с интегрированной безопасностью и управлением для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="76d81-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="76d81-109">Вы работаете со специалистами FastTrack, чтобы:</span><span class="sxs-lookup"><span data-stu-id="76d81-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-110">Развертывание среды WVD с несколькими сеансами Windows 10 Enterprise + Microsoft 365 Apps для предприятия с помощью следующих ниже.</span><span class="sxs-lookup"><span data-stu-id="76d81-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-111">Azure Marketplace Image</span><span class="sxs-lookup"><span data-stu-id="76d81-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="76d81-112">Общий образ</span><span class="sxs-lookup"><span data-stu-id="76d81-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="76d81-113">Развертывание office набор средств (ODT)</span><span class="sxs-lookup"><span data-stu-id="76d81-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="76d81-114">Настроить FSLogic</span><span class="sxs-lookup"><span data-stu-id="76d81-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-115">Развертывание агента FSLogix с контейнером профилей</span><span class="sxs-lookup"><span data-stu-id="76d81-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="76d81-116">Развертывание агента FSLogix с контейнером Office</span><span class="sxs-lookup"><span data-stu-id="76d81-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="76d81-117">Настройка папки FSLogix с исключениями контента</span><span class="sxs-lookup"><span data-stu-id="76d81-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="76d81-118">Развертывание Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="76d81-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="76d81-119">Развертывание Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="76d81-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="76d81-120">Подключение с помощью виртуальных клиентов настольных компьютеров Windows</span><span class="sxs-lookup"><span data-stu-id="76d81-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="76d81-121"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="76d81-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-122">Управление проектами развертывания виртуального рабочего стола клиента с Windows.</span><span class="sxs-lookup"><span data-stu-id="76d81-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="76d81-123">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="76d81-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="76d81-124">Виртуализация и развертывание сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="76d81-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="76d81-125">Настраиваемые изображения.</span><span class="sxs-lookup"><span data-stu-id="76d81-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="76d81-126">Миграции и сценарии с участием VMware и Citrix.</span><span class="sxs-lookup"><span data-stu-id="76d81-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="76d81-127">Сценарии Linux.</span><span class="sxs-lookup"><span data-stu-id="76d81-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="76d81-128">Преобразование или миграция профилей пользователей.</span><span class="sxs-lookup"><span data-stu-id="76d81-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="76d81-129">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="76d81-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="76d81-130">У вас уже должно быть следующее:</span><span class="sxs-lookup"><span data-stu-id="76d81-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Требования к лицензированию WVD</a></span><span class="sxs-lookup"><span data-stu-id="76d81-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="76d81-132">Azure Networking:</span><span class="sxs-lookup"><span data-stu-id="76d81-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-133">Подсети создания &amp; VNET</span><span class="sxs-lookup"><span data-stu-id="76d81-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="76d81-134">Брандмауэр / Группы безопасности сети</span><span class="sxs-lookup"><span data-stu-id="76d81-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="76d81-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="76d81-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="76d81-136">Маршрутиротка в Azure из локальной области</span><span class="sxs-lookup"><span data-stu-id="76d81-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="76d81-137">Правила брандмауэра, позволяющие подключаться к WVD</span><span class="sxs-lookup"><span data-stu-id="76d81-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Справка по docs</a></span><span class="sxs-lookup"><span data-stu-id="76d81-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="76d81-139">Установка общего каталога Azure Active</span><span class="sxs-lookup"><span data-stu-id="76d81-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-140">Стратегия <strong>удостоверений (Выберите ТОЛЬКО 1 из следующих 3 параметров)</strong></span><span class="sxs-lookup"><span data-stu-id="76d81-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="76d81-141">Active Directory с Подключением Azure AD в Azure</span><span class="sxs-lookup"><span data-stu-id="76d81-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="76d81-142">Active Directory с Azure AD Connect on Premise over VPN /ER</span><span class="sxs-lookup"><span data-stu-id="76d81-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="76d81-143">Доменные службы Active Directory</span><span class="sxs-lookup"><span data-stu-id="76d81-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
