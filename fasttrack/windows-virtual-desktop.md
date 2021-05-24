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
description: FastTrack предоставляет Windows для развертывания виртуальных настольных компьютеров, чтобы помочь вам на борту этого рабочего стола.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592442"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="e8780-103">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="e8780-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e8780-104"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e8780-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e8780-105"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e8780-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="e8780-106"><strong>Требования к исходной среде</strong></span><span class="sxs-lookup"><span data-stu-id="e8780-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e8780-107">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="e8780-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="e8780-108">FastTrack предоставляет Windows руководство по развертыванию виртуальных настольных компьютеров, чтобы помочь вам в этой службе виртуализации настольных компьютеров и приложений с легкостью использовать Windows 10 много сеансов, оптимизированные для Приложения Microsoft 365 для Enterprise с интегрированной безопасностью и управлением для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e8780-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="e8780-109">Вы работаете со специалистами FastTrack, чтобы:</span><span class="sxs-lookup"><span data-stu-id="e8780-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-110">Развертывание среды WVD с Windows 10 Корпоративная нескольких сеансов + Приложения Microsoft 365 для Enterprise с помощью следующих ниже.</span><span class="sxs-lookup"><span data-stu-id="e8780-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-111">Azure Marketplace Image</span><span class="sxs-lookup"><span data-stu-id="e8780-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="e8780-112">Общий образ</span><span class="sxs-lookup"><span data-stu-id="e8780-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="e8780-113">Office Развертывание набор средств (ODT)</span><span class="sxs-lookup"><span data-stu-id="e8780-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="e8780-114">Настроить FSLogic</span><span class="sxs-lookup"><span data-stu-id="e8780-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-115">Развертывание агента FSLogix с контейнером профилей</span><span class="sxs-lookup"><span data-stu-id="e8780-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="e8780-116">Развертывание агента FSLogix с Office контейнером</span><span class="sxs-lookup"><span data-stu-id="e8780-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="e8780-117">Настройка папки FSLogix с исключениями контента</span><span class="sxs-lookup"><span data-stu-id="e8780-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="e8780-118">Развертывание Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="e8780-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="e8780-119">Развертывание Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="e8780-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="e8780-120">Подключение с Windows виртуальных настольных клиентов</span><span class="sxs-lookup"><span data-stu-id="e8780-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="e8780-121"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="e8780-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-122">Project управления развертыванием виртуального рабочего стола Windows клиента.</span><span class="sxs-lookup"><span data-stu-id="e8780-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="e8780-123">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="e8780-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="e8780-124">Виртуализация и развертывание сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="e8780-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="e8780-125">Настраиваемые изображения.</span><span class="sxs-lookup"><span data-stu-id="e8780-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="e8780-126">Миграции и сценарии с участием VMware и Citrix.</span><span class="sxs-lookup"><span data-stu-id="e8780-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="e8780-127">Сценарии Linux.</span><span class="sxs-lookup"><span data-stu-id="e8780-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="e8780-128">Преобразование или миграция профилей пользователей.</span><span class="sxs-lookup"><span data-stu-id="e8780-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="e8780-129">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e8780-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="e8780-130">У вас уже должно быть следующее:</span><span class="sxs-lookup"><span data-stu-id="e8780-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="e8780-131">Требования к лицензированию WVD</span><span class="sxs-lookup"><span data-stu-id="e8780-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="e8780-132">Azure Networking:</span><span class="sxs-lookup"><span data-stu-id="e8780-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-133">Подсети создания &amp; VNET</span><span class="sxs-lookup"><span data-stu-id="e8780-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="e8780-134">Брандмауэр / Группы безопасности сети</span><span class="sxs-lookup"><span data-stu-id="e8780-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="e8780-135">VPN / ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="e8780-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="e8780-136">Маршрутиротка в Azure из локальной области</span><span class="sxs-lookup"><span data-stu-id="e8780-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="e8780-137">Правила брандмауэра, позволяющие подключаться к WVD</span><span class="sxs-lookup"><span data-stu-id="e8780-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="e8780-138">Справка по docs</span><span class="sxs-lookup"><span data-stu-id="e8780-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="e8780-139">Azure Active Directory Общая настройка</span><span class="sxs-lookup"><span data-stu-id="e8780-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-140">Стратегия <strong>удостоверений (Выберите ТОЛЬКО 1 из следующих 3 параметров)</strong></span><span class="sxs-lookup"><span data-stu-id="e8780-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="e8780-141">Active Directory с azure AD Подключение Azure</span><span class="sxs-lookup"><span data-stu-id="e8780-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="e8780-142">Active Directory с azure AD Подключение локально над VPN / ER</span><span class="sxs-lookup"><span data-stu-id="e8780-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="e8780-143">Доменные службы Active Directory</span><span class="sxs-lookup"><span data-stu-id="e8780-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
