---
title: Продукты и возможности
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: В этой статье представлены подробные сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и об операциях исходной среды, которые необходимо выполнить перед началом работы. На основе вашей текущей конфигурации мы работаем над вами для создания плана исправления, который приведем к исходной среде до минимальных требований для успешного подключения.
ms.openlocfilehash: d25c1df8e628f14487952cacc86ccf8fb9dad8c1
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817704"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="bc3db-104">Продукты и возможности</span><span class="sxs-lookup"><span data-stu-id="bc3db-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="bc3db-105">Службы и сценарии, поддерживаемые FastTrack</span><span class="sxs-lookup"><span data-stu-id="bc3db-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="bc3db-106">В этой статье представлены подробные сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и об операциях исходной среды, которые необходимо выполнить перед началом работы.</span><span class="sxs-lookup"><span data-stu-id="bc3db-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="bc3db-107">На основе вашей текущей конфигурации мы работаем над вами для создания плана исправления, который приведем к исходной среде до минимальных требований для успешного подключения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="bc3db-108">FastTrack предоставляет рекомендации, которые помогут вам сначала ознакомиться с основными возможностями (общие для всех служб Microsoft Online Services), а затем с подключением каждой возможной службы:</span><span class="sxs-lookup"><span data-stu-id="bc3db-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="bc3db-109">Общие сведения</span><span class="sxs-lookup"><span data-stu-id="bc3db-109">General</span></span>](#general)
  - [<span data-ttu-id="bc3db-110">Office 365</span><span class="sxs-lookup"><span data-stu-id="bc3db-110">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="bc3db-111">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="bc3db-111">Enterprise Mobility & Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="bc3db-112">Windows 10</span><span class="sxs-lookup"><span data-stu-id="bc3db-112">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="bc3db-113">Служба Assure для приложений</span><span class="sxs-lookup"><span data-stu-id="bc3db-113">App Assure</span></span>](Win-10-app-assure.md)
  - [<span data-ttu-id="bc3db-114">Новая версия Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="bc3db-114">The new Microsoft Edge</span></span>](Win-10-microsoft-edge.md)

> [!NOTE]
> <span data-ttu-id="bc3db-115">Сведения о ожиданиях исходной среды для Office 365 для государственных организаций США см. в статье "Требованиям к исходной среде [для Office 365 для государственных организаций США".](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)</span><span class="sxs-lookup"><span data-stu-id="bc3db-115">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span>
 
## <a name="general"></a><span data-ttu-id="bc3db-116">Общие</span><span class="sxs-lookup"><span data-stu-id="bc3db-116">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bc3db-117"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-117"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="bc3db-118"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-118"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="bc3db-119"><strong>Ограничения, касание исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-119"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc3db-120"><strong>Базовое подключение</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-120"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-121">Мы предоставляем удаленное руководство по базовому подключению, включающему подготовку служб, клиентов и интеграцию удостоверений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-121">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="bc3db-122">Она также включает шаги по предоставлению основы для таких служб входящей миграции, как Exchange Online, SharePoint Online и Microsoft Teams, в том числе обсуждение <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">вопросов обеспечения безопасности, сетевого подключения и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="bc3db-122">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="bc3db-123">Подключение одной или нескольких поддерживаемых служб можно начать после завершения базового подключения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-123">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="bc3db-124"></li>
</ul>  

<strong> Интеграция удостоверений </strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-124"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="bc3db-125">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-125">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="bc3db-126">Подготовка локальных удостоверений Active Directory для синхронизации с Azure Active Directory (Azure AD), в том числе установки и настройки Azure AD Connect (одного или нескольких лесов) и лицензирования (в том числе лицензионного соглашения по группам).</span><span class="sxs-lookup"><span data-stu-id="bc3db-126">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="bc3db-127">Создание облачных удостоверений, в том числе пакетного импорта и лицензирования, в том числе с помощью группового лицензирования.</span><span class="sxs-lookup"><span data-stu-id="bc3db-127">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="bc3db-128">Выбор и включение правильного метода проверки подлинности для вашего облачного цикла, синхронизации хэша паролей, сквозной проверки подлинности или служб федерации Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="bc3db-128">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="bc3db-129">Включение служб федерации Active Directory для клиентов с одним лесом Active Directory и удостоверениями, синхронизируемыми с помощью средства Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="bc3db-129">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="bc3db-130">Для этого требуются службы федерации Active Directory Windows Server 2012 R2 2.0 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="bc3db-130">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="bc3db-131">Перенос аутентификации из AD FS в Azure AD с помощью синхронизации хэша паролей или сквозной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="bc3db-131">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="bc3db-132">Перенос предварительно интегрированных приложений (например, приложений коллекции "программное обеспечение как услуга" (SaaS) Azure AD) с AD FS в Azure AD для единого входа.</span><span class="sxs-lookup"><span data-stu-id="bc3db-132">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="bc3db-133">Включение интеграции приложений SaaS с единым входом из галереи Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-133">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="bc3db-134">Включение автоматической подготовки пользователей для предварительно интегрированных приложений SaaS, как указано в списке руководства по интеграции <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">приложений</a> (ограничено приложениями коллекции Azure AD и только для исходящей подготовки).</span><span class="sxs-lookup"><span data-stu-id="bc3db-134">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="bc3db-135"><strong>Включение сети </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="bc3db-135"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="bc3db-136">В рамках преимущества FastTrack мы рекомендуем вам подключаться к облачным службам, чтобы обеспечить максимально высокий уровень производительности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-136">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="bc3db-137"><strong>Леса Active Directory</strong> Функциональный лес имеет режим Windows Server 2003 или более поздней версии с такой конфигурацией:</span><span class="sxs-lookup"><span data-stu-id="bc3db-137"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-138">Один лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="bc3db-138">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-139">Топологии с одним лесом учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="bc3db-139">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-140">Топологии с несколькими лесами учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="bc3db-140">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-141">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory, включающим Exchange и/или Lync 2010, Lync 2013 или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="bc3db-141">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-142">Несколько лесов учетных записей Active Directory, каждый из которых включает свою организацию Exchange.</span><span class="sxs-lookup"><span data-stu-id="bc3db-142">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-143">При необходимости требуются задачи для настройки клиентов и интеграции с Azure Active Directory.   </span><span class="sxs-lookup"><span data-stu-id="bc3db-143">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.   </span></span></li>
</ul><span data-ttu-id="bc3db-144">
  <strong>Важно!</strong>  </span><span class="sxs-lookup"><span data-stu-id="bc3db-144">
  <strong>Important:</strong>  </span></span><ul>
<li>  <span data-ttu-id="bc3db-145">В сценариях с несколькими лесами Active Directory, если развернут Lync 2010, Lync 2013 или Skype для бизнеса, необходимо развернуть его в том же лесу Active Directory, что и Exchange.</span><span class="sxs-lookup"><span data-stu-id="bc3db-145">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-146">При реализации нескольких лесов Active Directory с несколькими организациями Exchange в гибридной конфигурации Exchange общие пространства имен участников-пользователей (UPN) между исходными лесами не поддерживаются.</span><span class="sxs-lookup"><span data-stu-id="bc3db-146">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="bc3db-147">Основные пространства имен SMTP между организациями Exchange также должны быть отдельными.</span><span class="sxs-lookup"><span data-stu-id="bc3db-147">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="bc3db-148">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/?linkid=845444">гибридных развертываниях с несколькими лесами Active Directory.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-148">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-149">Развертывание служб федерации Active Directory (AD FS) с несколькими лесами непредусмотрено для развертывания.</span><span class="sxs-lookup"><span data-stu-id="bc3db-149">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="bc3db-150">Для <a href="https://go.microsoft.com/fwlink/?linkid=2080150">получения поддержки обратитесь</a> к партнеру Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="bc3db-150">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-151"><strong>Приложения Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-151"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-152">Мы предоставляем руководство по удаленному развертыванию для:</span><span class="sxs-lookup"><span data-stu-id="bc3db-152">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-153">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="bc3db-153">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-154">Назначение пользователям и устройствам лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="bc3db-154">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-155">Установка приложений Microsoft 365 с портала Office 365 с помощью технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="bc3db-155">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-156">Установка приложений Office Mobile (например, Outlook Mobile, Word Mobile, Excel Mobile и PowerPoint Mobile) на устройствах с iOS или Android.</span><span class="sxs-lookup"><span data-stu-id="bc3db-156">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-157">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-157">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-158">Выбор и настройка локальной или облачной установки.</span><span class="sxs-lookup"><span data-stu-id="bc3db-158">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-159">Создание XML-файла конфигурации средства развертывания Office с помощью центра развертывания Office или встроенного XML-файла для настройки пакета развертывания.</span><span class="sxs-lookup"><span data-stu-id="bc3db-159">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-160">Развертывание с помощью Microsoft Endpoint Configuration Manager, а также создание пакета Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="bc3db-160">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="bc3db-161">Кроме того, если у вас есть макрос или надстройка, которые работали с предыдущими версиями Office и имеются проблемы совместимости, мы предоставим вам руководство по устранению проблемы совместимости без дополнительной платы в рамках программы App Assure.</span><span class="sxs-lookup"><span data-stu-id="bc3db-161">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="bc3db-162">Дополнительные <strong>сведения см. в</strong> разделе App Assure Windows <a href="#windows-10">10.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-162">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="bc3db-163">Сетевое программное обеспечение в сети должно соответствовать минимальным требованиям к <a href="https://go.microsoft.com/fwlink/?LinkID=723597">системе для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-163">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-164"><strong>Работоспособность сети</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-164"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-165">Мы предоставляем удаленное руководство по получению и интерпретации ключевых данных о подключении к сети от вашей среды, показывающему, как сайты вашей организации согласились с принципами сетевого <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">подключения Майкрософт.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-165">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="bc3db-166">Этот показатель будет непонятно в лишь влиянию на пропускную способность миграции, взаимодействие с пользователем, производительность службы и надежность.</span><span class="sxs-lookup"><span data-stu-id="bc3db-166">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="bc3db-167">Также мы поможем вам выполнить все действия по исправлению, выделенные данными, чтобы помочь вам улучшить оценку сети.</span><span class="sxs-lookup"><span data-stu-id="bc3db-167">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="bc3db-168">Доступ к Центру администрирования Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-168">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-169">Требуются актуальные версии приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-169">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-170">Службы определения расположения включены <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">согласно рекомендациям по производительности сети в Центре администрирования Microsoft 365 (предварительная версия).</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-170">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="bc3db-171">Office 365</span><span class="sxs-lookup"><span data-stu-id="bc3db-171">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bc3db-172"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-172"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="bc3db-173"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-173"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="bc3db-174"><strong>Ограничения, касание исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-174"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc3db-175"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-175"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-176">Ниже описывается подготовка организации к использованию электронной почты.</span><span class="sxs-lookup"><span data-stu-id="bc3db-176">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="bc3db-177">Конкретный этап зависит от исходной и планов миграции электронной почты.</span><span class="sxs-lookup"><span data-stu-id="bc3db-177">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="bc3db-178">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-178">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-179">Настройка функций Exchange Online Protection (EOP) для всех доменов, поддерживающих почту и проверенных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-179">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-180">Настройка записей обмена электронной почтой (MX) на Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-180">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-181">Настройка функции Office 365 ATP, если она входит в состав подписки.</span><span class="sxs-lookup"><span data-stu-id="bc3db-181">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="bc3db-182">Дополнительные сведения см. в <strong>разделе этой таблицы, посвященной Office 365 Advanced Threat Protection.</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-182">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-p113">Настройка функции защиты от потери данных (DLP) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-p113">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="bc3db-p114">Настройка шифрования сообщений Office 365 (OME) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-p114">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="bc3db-187">
  <strong>Примечание.</strong> Служба репликации почтовых ящиков (MRS) попытается перенести сообщения с управляемыми правами на доступ к данным (IRM) из локального почтового ящика в соответствующий почтовый ящик Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-187">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="bc3db-188">Возможность чтения защищенных данных после переноса зависит от сопоставления клиентом шаблонов службы Active Directory Rights Managed Services (AD RMS) и их копирования в службу Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="bc3db-188">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="bc3db-189">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="bc3db-189">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-190">Настройка DNS, в том числе обязательного автообнаружения, инфраструктуры политики отправителей (SPF), DomainKeys Identified Mail (DKIM), проверки подлинности сообщений на основе домена, отчетности и соответствие записей DMARC и MX (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="bc3db-190">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-191">Настройка потока обработки почты между исходной средой обмена сообщениями и Exchange Online (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="bc3db-191">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-192">Перенос почты из исходной среды обмена сообщениями в Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-192">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-193">Настройка почтовых клиентов (Outlook для Windows, Outlook в Интернете, Outlook для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="bc3db-193">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="bc3db-194">
  <strong>Перенос данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="bc3db-194">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="bc3db-195">Сведения об использовании преимущества FastTrack для переноса данных в Office 365: см. в <a href="https://review.docs.microsoft.com/fasttrack/data-migration">статье "Перенос данных".</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-195">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="bc3db-196">Исходная среда должна иметь один из указанных ниже минимальных уровней.</span><span class="sxs-lookup"><span data-stu-id="bc3db-196">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-197">Одна или несколько организаций Exchange с Exchange Server 2003 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="bc3db-197">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-198">Одна почтовая среда, поддерживающая протокол IMAP.</span><span class="sxs-lookup"><span data-stu-id="bc3db-198">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-199">Одна среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="bc3db-199">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-200">Сведения о поддержке нескольких регионов см. в статье <a href="https://go.microsoft.com/fwlink/?linkid=872776">"Поддержка нескольких регионов" в Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-200">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-201">Клиентское программное обеспечение с доступом к Интернету (например, Project для Office 365, Outlook для Windows, Outlook для iOS и Android, клиент синхронизации OneDrive для бизнеса, Power BI Desktop и Skype для бизнеса) должно соответствовать минимальным <a href="https://go.microsoft.com/fwlink/?LinkID=723597">требованиям к системе для Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-201">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-202"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-202"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-203">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-203">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-204">Управление информацией.</span><span class="sxs-lookup"><span data-stu-id="bc3db-204">Information governance.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-205">Метки и политики хранения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-205">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-206">Управление записями.</span><span class="sxs-lookup"><span data-stu-id="bc3db-206">Records management.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-207">Политики удаления.</span><span class="sxs-lookup"><span data-stu-id="bc3db-207">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-208">Соответствие требованиям к обмену данными.</span><span class="sxs-lookup"><span data-stu-id="bc3db-208">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-209">Управление внутренними рисками.</span><span class="sxs-lookup"><span data-stu-id="bc3db-209">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-210">Advanced eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="bc3db-210">Advanced eDiscovery.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-211">Помещаясь <strong>от базового подключения</strong> в <a href="#general">целом,</a>минимальные системные требования отсутствуют.</span><span class="sxs-lookup"><span data-stu-id="bc3db-211">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-212"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-212"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-213">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-213">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-214">Классификация данных.</span><span class="sxs-lookup"><span data-stu-id="bc3db-214">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-215">Типы конфиденциальной информации.</span><span class="sxs-lookup"><span data-stu-id="bc3db-215">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-216">Создание меток конфиденциальности.</span><span class="sxs-lookup"><span data-stu-id="bc3db-216">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-217">Применение меток конфиденциальности.</span><span class="sxs-lookup"><span data-stu-id="bc3db-217">Applying Sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-218">Унифицированное применение меток.</span><span class="sxs-lookup"><span data-stu-id="bc3db-218">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-219">Обучаемые классификаторы.</span><span class="sxs-lookup"><span data-stu-id="bc3db-219">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-220">Знакомство с данными посредством обозревателя содержимого и обозревателя действий.</span><span class="sxs-lookup"><span data-stu-id="bc3db-220">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-221">Публикация меток с помощью политик (вручную и автоматически).</span><span class="sxs-lookup"><span data-stu-id="bc3db-221">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-222">Создание политик защиты от потери данных для чатов и каналов Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="bc3db-222">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-223">Помещаясь <strong>от базового подключения</strong> в <a href="#general">целом,</a>минимальные системные требования отсутствуют.</span><span class="sxs-lookup"><span data-stu-id="bc3db-223">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-224"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-224"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-225">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-225">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-226">Проверка минимальных требований в Exchange Online, SharePoint Online, группах Office 365 и Azure AD для поддержки Teams.</span><span class="sxs-lookup"><span data-stu-id="bc3db-226">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-227">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="bc3db-227">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-228">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="bc3db-228">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-229">Подтверждение того, что рабочее пространство Teams включено в клиенте Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-229">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-230">Включение или отключение пользовательских лицензий.</span><span class="sxs-lookup"><span data-stu-id="bc3db-230">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-231">Оценка сети для Teams:</span><span class="sxs-lookup"><span data-stu-id="bc3db-231">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-232">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="bc3db-232">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-233">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-233">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-234">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="bc3db-234">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="bc3db-235">Настройка политики приложений Teams (веб-приложение Teams, классическое приложение Teams, а также приложение Teams для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="bc3db-235">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-236">Если применимо, мы также предоставляем руководство по следующим вопросам:</span><span class="sxs-lookup"><span data-stu-id="bc3db-236">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-237">Устройства комнат Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="bc3db-237">Microsoft Teams Room Devices:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="bc3db-238">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств телефонной и конференц-связи, перечисленных в <a href="https://go.microsoft.com/fwlink/?linkid=2066478">каталоге устройств Teams.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-238">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="bc3db-239">Включение Аудиоконференций:</span><span class="sxs-lookup"><span data-stu-id="bc3db-239">Enabling Audio Conferencing:</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="bc3db-240">Настройка организации с использованием параметров по умолчанию для схемы конференции.</span><span class="sxs-lookup"><span data-stu-id="bc3db-240">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-241">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="bc3db-241">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="bc3db-242">Телефонная система:</span><span class="sxs-lookup"><span data-stu-id="bc3db-242">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-243">Настройка облачных голосовых функций для организации.</span><span class="sxs-lookup"><span data-stu-id="bc3db-243">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-244">Руководство по тарифным планам (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">доступные страны):</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-244">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-245">Назначение номеров лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="bc3db-245">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-246">Рекомендации по портированию локальных номеров до 999 в пользовательском интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="bc3db-246">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-247">Поддержка запросов на обслуживание для портирования локальных номеров выше 999.</span><span class="sxs-lookup"><span data-stu-id="bc3db-247">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-248">Руководство по прямой маршрутизации:</span><span class="sxs-lookup"><span data-stu-id="bc3db-248">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-249">Руководство по настройке организации для схемы прямой маршрутизации в сценариях с размещением у партнера или развертывания клиентом для одного сайта.</span><span class="sxs-lookup"><span data-stu-id="bc3db-249">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for a single site.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="bc3db-250">Включение прямых трансляций Teams.</span><span class="sxs-lookup"><span data-stu-id="bc3db-250">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-251">Настройка организации и интеграция в Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="bc3db-251">Organization setup and integration into Microsoft Stream.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="bc3db-252">Удостоверения включены в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-252">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-253">Пользователи, для которых включен SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-253">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-254">Есть почтовые ящики Exchange (в сети и локально в гибридной конфигурации Exchange).</span><span class="sxs-lookup"><span data-stu-id="bc3db-254">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-255">Включено для групп Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-255">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="bc3db-256">
  <strong>Примечание.</strong>   Если пользователям не назначены лицензии SharePoint Online, у них не будет хранилища OneDrive для бизнеса в Office 365:.</span><span class="sxs-lookup"><span data-stu-id="bc3db-256">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="bc3db-257">Пользователи могут обмениваться файлами в каналах, но пользователи не смогут обмениваться файлами в чатах без хранилища OneDrive для бизнеса в Office 365:.</span><span class="sxs-lookup"><span data-stu-id="bc3db-257">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="bc3db-258">Teams не поддерживает локальную среду SharePoint.</span><span class="sxs-lookup"><span data-stu-id="bc3db-258">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="bc3db-259">
  <strong>Примечание.</strong>   В идеале почтовые ящики всех пользователей должны находиться в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-259">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="bc3db-260">Удостоверения пользователей, чьи почтовые ящики размещены локально, должны быть синхронизированы с каталогом Office 365 с помощью Средства Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="bc3db-260">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="bc3db-261">Если почтовый ящик пользователя находится в локальной среде, пользователи не могут добавлять или настраивать соединители.</span><span class="sxs-lookup"><span data-stu-id="bc3db-261">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="bc3db-262">Установщики клиентов Microsoft Teams для настольных компьютеров Windows и Mac можно скачать  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> с.</span><span class="sxs-lookup"><span data-stu-id="bc3db-262">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-263"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-264">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-264">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-265">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="bc3db-265">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-266">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-266">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-267">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="bc3db-267">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-268">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="bc3db-268">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-269">Помещаясь <strong>от базового подключения</strong> в <a href="#general">целом,</a>минимальные системные требования отсутствуют.</span><span class="sxs-lookup"><span data-stu-id="bc3db-269">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-270"><strong>Outlook для iOS и Android</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-270"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-271">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-271">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-272">Скачивание Outlook для iOS и Android через Apple App Store или Google Play.</span><span class="sxs-lookup"><span data-stu-id="bc3db-272">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-273">Настройка учетных записей и оценка почтового ящика Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-273">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-274">Защита Outlook Mobile (дополнительные сведения см. в разделе <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">"Защита Outlook для iOS</a> и Android в Exchange Online").</span><span class="sxs-lookup"><span data-stu-id="bc3db-274">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="bc3db-275">Удостоверения включены в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-275">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-276">Выполнена настройка Exchange Online, назначены соответствующие лицензии.</span><span class="sxs-lookup"><span data-stu-id="bc3db-276">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-277"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-277"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-278">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-278">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-279">Назначение лицензий на Power BI.</span><span class="sxs-lookup"><span data-stu-id="bc3db-279">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-280">Развертывание приложения Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="bc3db-280">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-281">Сетевое веб-программное обеспечение, например Power BI Desktop, должно соответствовать минимальным требованиям <a href="https://go.microsoft.com/fwlink/?LinkID=723597">к системе для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-281">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-282"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-282"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-283">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-283">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-284">Проверка основных функций SharePoint, необходимых для работы Project Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-284">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-285">Добавление службы Project Online в клиент (в том числе добавление подписок для пользователей).</span><span class="sxs-lookup"><span data-stu-id="bc3db-285">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-286">Настройка пула корпоративных ресурсов (ERP).</span><span class="sxs-lookup"><span data-stu-id="bc3db-286">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-287">Создание первого проекта.</span><span class="sxs-lookup"><span data-stu-id="bc3db-287">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-288">Клиентское программное обеспечение с online, например Project для Office 365, должно соответствовать минимальным требованиям <a href="https://go.microsoft.com/fwlink/?LinkID=723597">к системе для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-288">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-289"><strong>Project Online профессиональный и расширенный</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-289"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-290">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-291">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="bc3db-291">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-292">Назначение пользователям лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="bc3db-292">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-293">Установка клиента Project Online для настольных ПК с использованием портала Office 365 и технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="bc3db-293">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-294">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-294">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-295">Настройка одного внутреннего сервера распространения для клиента Project Online для настольных ПК, в том числе помощь по созданию файла configuration.xml для его последующего использования в средстве развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-295">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-296">Подключение клиента Project Online для настольных ПК к Project Online профессиональный или Project Online расширенный.</span><span class="sxs-lookup"><span data-stu-id="bc3db-296">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-297">Клиентское программное обеспечение с online, например Project для Office 365, должно соответствовать минимальным требованиям <a href="https://go.microsoft.com/fwlink/?LinkID=723597">к системе для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-297">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-298"><strong>SharePoint Online и OneDrive для бизнеса</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-298"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-299">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-299">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-300">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="bc3db-300">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-301">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="bc3db-301">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-302">Подготовка пользователей и лицензий.</span><span class="sxs-lookup"><span data-stu-id="bc3db-302">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="bc3db-303">Создание сайтов для администратора SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-303">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="bc3db-304">Планирование семейств веб-сайтов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-304">Planning site collections.</span></span></li>
<li><span data-ttu-id="bc3db-305">Защита контента и управление разрешениями.</span><span class="sxs-lookup"><span data-stu-id="bc3db-305">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="bc3db-306">Настройка функций SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-306">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="bc3db-307">Настройка функций гибридной среды SharePoint, таких как гибридный поиск, гибридные сайты, гибридная таксономия, типы контента, гибридная функция самостоятельного создания сайтов (только для SharePoint Server 2013), расширенное средство запуска приложений, гибридная служба OneDrive для бизнеса и сайты экстрасети.</span><span class="sxs-lookup"><span data-stu-id="bc3db-307">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-308">Способ миграции.</span><span class="sxs-lookup"><span data-stu-id="bc3db-308">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-309">В зависимости от версии SharePoint предоставляются дополнительные рекомендации для OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="bc3db-309">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-310">Определение вариантов интеграции, а также проверка локальной и сетевой инфраструктуры и пропускной способности сети.</span><span class="sxs-lookup"><span data-stu-id="bc3db-310">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-311">Установка SharePoint Online 2013 с пакетом обновления 1 (SP1), если это применимо), планированию и реализации требований синхронизации и удостоверения, а также идентификация клиента синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="bc3db-311">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-312">Планирование и реализация единого выпуска для всех пользователей (или поэтапного развертывания).</span><span class="sxs-lookup"><span data-stu-id="bc3db-312">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-313">Назначение лицензий, перенаправление личных сайтов и библиотек документов в Office 365 (применимо к SharePoint Online 2013), настройка аудиторий для управления доступом к OneDrive (применимо к SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="bc3db-313">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="bc3db-314">Перенаправление и перемещение известных папок в OneDrive.</span><span class="sxs-lookup"><span data-stu-id="bc3db-314">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="bc3db-315">Развертывание клиентской синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="bc3db-315">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="bc3db-316">
  <strong>Перенос данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="bc3db-316">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="bc3db-317">Сведения об использовании преимущества FastTrack для переноса данных в Office 365: см. в <a href="https://review.docs.microsoft.com/fasttrack/data-migration">статье "Перенос данных".</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-317">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://review.docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="bc3db-318"><strong>Для гибридной среды SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-318"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="bc3db-319">Конфигурация гибридной среды SharePoint включает настройку гибридных сайтов, поиска, таксономии, типов контента, версии OneDrive для бизнеса, расширенного средства запуска приложений, сайтов экстрасети, а также функции самостоятельного создания сайтов с локальным подключением к одной целевой среде SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-319">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="bc3db-320">
  <strong>Примечание.</strong> Самостоятельное создание сайтов не повысит область действия локальных серверов под управлением SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="bc3db-320">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="bc3db-321">Чтобы включить гибридную среду SharePoint, вам потребуется одна из следующих локальных сред SharePoint Server: 2013, 2016 или 2019.</span><span class="sxs-lookup"><span data-stu-id="bc3db-321">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="bc3db-322">
  <strong>Примечание.</strong> Обновление локальных сред SharePoint до SharePoint Server не предусмотрено.</span><span class="sxs-lookup"><span data-stu-id="bc3db-322">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="bc3db-323">Для <a href="https://go.microsoft.com/fwlink/?linkid=2080150">получения поддержки обратитесь</a> к партнеру Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="bc3db-323">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="bc3db-324">Дополнительные сведения см. в разделе <a href="https://go.microsoft.com/fwlink/?linkid=853548">"Минимальные уровни общедоступных обновлений для гибридных функций SharePoint".</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="bc3db-324">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="bc3db-325">
  <strong>Примечание.</strong> Сведения о поддержке нескольких регионов см. в статье <a href="https://go.microsoft.com/fwlink/?linkid=831056">"Поддержка нескольких регионов" в OneDrive и SharePoint Online в Office 365.</a><em>.</em>  </span><span class="sxs-lookup"><span data-stu-id="bc3db-325">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-326"><strong>Skype для бизнеса Online</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-326"><strong>Skype for Business Online</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-327">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-328">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="bc3db-328">Configuring firewall ports.</span></span>  </li>

<li>  <span data-ttu-id="bc3db-329">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="bc3db-329">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-330">Оценка сети:</span><span class="sxs-lookup"><span data-stu-id="bc3db-330">Network assessment:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-331">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="bc3db-331">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-332">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-332">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-333">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="bc3db-333">Bandwidth estimates.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-334">Создание учетных записей для устройств системы комнат.</span><span class="sxs-lookup"><span data-stu-id="bc3db-334">Creating accounts for any room system devices.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-335">Развертывание поддерживаемого клиента Skype для бизнеса Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-335">Deploying a supported Skype for Business Online client.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-336">Настройка серверов с разделенным доменом (локальная версия Lync 2010, Lync 2013 или серверная среда Skype для бизнеса 2015 и клиент Skype для бизнеса Online при определенных условиях), компонентов "План звонков", "Трансляция собраний Skype", а также компонентов "Телефонная система" и "План звонков" (не во всех регионах).</span><span class="sxs-lookup"><span data-stu-id="bc3db-336">Establishing split domain server configuration between your on-premises Lync 2010, Lync 2013, or Skype for Business 2015 server environment and Skype for Business Online tenant (if applicable), Calling Plans, Skype Meeting Broadcast, and Phone System and Calling Plans (in available markets).</span></span>  
  <span data-ttu-id="bc3db-337">Если это возможно, FastTrack также поможет:</span><span class="sxs-lookup"><span data-stu-id="bc3db-337">If applicable, FastTrack also guides you through:</span></span>  </li>
<li>  <span data-ttu-id="bc3db-338">Настройка системного устройства комнаты:</span><span class="sxs-lookup"><span data-stu-id="bc3db-338">Configuring room system device:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-339">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств для конференц-связи. Устройства перечислены на вкладке "Системы комнаты собраний" в <a href="https://go.microsoft.com/fwlink/?LinkId=615775">каталоге решений Skype для бизнеса.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-339">Creation of online accounts needed for supported conference room devices listed on the Meeting Room Systems tab in the <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype for Business solutions catalog</a>.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-340">Настройка гибридных серверов и разделенных доменов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-340">Configuring hybrid and split domain servers.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-341">Настройка аудиоконференций:</span><span class="sxs-lookup"><span data-stu-id="bc3db-341">Configuring Audio Conferencing:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-342">Настройка организации с использованием параметров моста конференции по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="bc3db-342">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-343">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="bc3db-343">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-344">Настройка параметров по умолчанию телефонной системы:</span><span class="sxs-lookup"><span data-stu-id="bc3db-344">Configuring Phone System default settings:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-345">Планы звонков:</span><span class="sxs-lookup"><span data-stu-id="bc3db-345">Calling Plans:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-346">Назначение номеров пользователям лицензий.</span><span class="sxs-lookup"><span data-stu-id="bc3db-346">Assignment of numbers to licenses users.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-347">Рекомендации по портированию локальных номеров до 99 в пользовательском интерфейсе</span><span class="sxs-lookup"><span data-stu-id="bc3db-347">Local number porting guidance through user interface up to 99</span></span>  </li>
<li>  <span data-ttu-id="bc3db-348">Поддержка запросов на обслуживание для портирования локальных номеров выше 999</span><span class="sxs-lookup"><span data-stu-id="bc3db-348">Local number porting service request support over 999</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="bc3db-349">Настройте трансляцию собраний Skype для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="bc3db-349">Configure Skype for Business Meeting Broadcast:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-350">Настройка организации для федерации со службой трансляции собраний.</span><span class="sxs-lookup"><span data-stu-id="bc3db-350">Organization setup for federation with Meeting Broadcast service.</span></span>  </li>
</ul></li>
</ul></td>
<td>  <span data-ttu-id="bc3db-351"><strong>Для гибридной среды Lync:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-351"><strong>For Lync hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="bc3db-352">Один локальный лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="bc3db-352">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-353">Среда Lync 2010 Server со средствами администрирования Lync 2013 или средствами администрирования Skype для бизнеса 2015 и ролью пограничного сервера Lync 2010.</span><span class="sxs-lookup"><span data-stu-id="bc3db-353">A Lync 2010 Server environment with Lync 2013 admin tools or Skype for Business 2015 admin tools and a Lync 2010 edge server role.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-354">Среда Lync 2013 Server и роль пограничного сервера Lync 2013.</span><span class="sxs-lookup"><span data-stu-id="bc3db-354">A Lync 2013 Server environment and a Lync 2013 edge server role.</span></span>  </li>
</ul><span data-ttu-id="bc3db-355">
  <strong>Для гибридной среды Skype для бизнеса:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-355">
  <strong>For Skype for Business hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="bc3db-356">Один локальный лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="bc3db-356">A single on-premises Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-357">Один лес учетных записей Active Directory и топологии леса ресурсов (Exchange и/или Skype для бизнеса)</span><span class="sxs-lookup"><span data-stu-id="bc3db-357">A single Active Directory account forest onward and resource forest (Exchange and/or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-358">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory с Exchange и/или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="bc3db-358">Multiple Active Directory account forests, with one forest being a centralized Active Directory account forest with Exchange and/or Skype for Business in it.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-359">Среда Skype для бизнеса Server 2015, включающая роль пограничного сервера Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="bc3db-359">A Skype for Business Server 2015 environment including a Skype for Business edge server role.</span></span>  </li>
</ul><span data-ttu-id="bc3db-360">
  <strong>Примечание.</strong> Эта дополнительная услуга предназначена для настройки и проверки задач разделенного домена (гибридного) и не включает установку локальных компонентов (например, средств администрирования Lync 2013, серверов Lync 2013/Skype для бизнеса Online или пограничных серверов Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="bc3db-360">
  <strong>Note:</strong> This additional service is for configuring and validating of the split domain (hybrid) tasks and doesn't include introducing on-premises components (for example, Lync 2013 admin tools or Lync 2013/Skype for Business Online servers, or Lync 2010, Lync 2013, or Skype for Business edge servers).</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-361"><strong>Yammer корпоративный</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-361"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="bc3db-362">Мы предоставляем удаленное руководство по включению службы Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="bc3db-362">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="bc3db-363">Сетевое программное обеспечение в сети должно соответствовать минимальным требованиям к <a href="https://go.microsoft.com/fwlink/?LinkID=723597">системе для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-363">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="bc3db-364">Enterprise Mobility & Security</span><span class="sxs-lookup"><span data-stu-id="bc3db-364">Enterprise Mobility & Security</span></span>

<table>
<thead>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-365"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-365"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-366">Мы предоставляем удаленное руководство по обеспечению безопасности облачных удостоверений в следующих сценариях.</span><span class="sxs-lookup"><span data-stu-id="bc3db-366">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="bc3db-367">

<strong>Безопасная базовая инфраструктура</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="bc3db-367">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="bc3db-368">Настройка и включение надежной проверки подлинности для ваших удостоверений, включая защиту с помощью многофакторной идентификации Azure (только облака), приложение Microsoft Authenticator, а также комбинированную регистрацию для Azure MFA и самостоятельного сброса пароля (SSPR).</span><span class="sxs-lookup"><span data-stu-id="bc3db-368">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-369">Для клиентов, не использующих Azure AD Premium, предоставляются рекомендации по защите удостоверений с использованием параметров безопасности по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="bc3db-369">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-370">Руководство по защите удостоверений при использовании условного доступа предоставляется пользователям Azure AD премиум-сервера.</span><span class="sxs-lookup"><span data-stu-id="bc3db-370">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-371">Обнаружение и блокировка использования ненадежных паролей с защитой паролем Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-371">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-372">Защита удаленного доступа к локальным веб-приложениям с помощью прокси-сервера приложения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-372">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-373">Включение обнаружения рисков и исправления с помощью защиты идентификации Azure.</span><span class="sxs-lookup"><span data-stu-id="bc3db-373">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-374">включение настраиваемого экрана входа, включая логотип, текст и изображения с настраиваемой фирменной символикой;</span><span class="sxs-lookup"><span data-stu-id="bc3db-374">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-375">Безопасный общий доступ к приложениям и службам с гостевыми пользователями, использующими Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="bc3db-375">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-376">Управление доступом для администраторов Office 365 с помощью управления доступом на основе ролей (RBAC) с помощью встроенных административных ролей и сокращения количества привилегированных учетных записей администраторов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-376">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-377">Настройка гибридного присоединения к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-377">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-378">Настройка присоединения к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-378">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="bc3db-379">
  
<strong>Мониторинг и создание отчетов</strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-379">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="bc3db-380">Включение удаленного мониторинга для AD FS, Azure AD Connect и контроллеров домена с помощью Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="bc3db-380">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="bc3db-381">
  
<strong>Управление</strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-381">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="bc3db-382">Управление удостоверениями Azure AD и жизненным циклом доступа в крупномасштабном масштабе с помощью управления правами в Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-382">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="bc3db-383">Управление членством в группах Azure AD, доступом к корпоративным приложениям и назначениями ролей с помощью проверок доступа Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-383">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-384">Оценка условий использования Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-384">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-385">Управление доступом к привилегированным учетным записям администраторов с помощью Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="bc3db-385">Managing and controling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="bc3db-386">
  
<strong>Автоматизация и эффективность </strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-386">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="bc3db-387">Включение Azure AD SSPR.</span><span class="sxs-lookup"><span data-stu-id="bc3db-387">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="bc3db-388">Предоставление пользователям возможности создавать и управлять собственными группами Office 365 с помощью самостоятельного управления группами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-388">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-389">Управление делегированным доступом к корпоративным приложениям с помощью управления делегированными группами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-389">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-390">Включение динамических групп Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-390">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-391">уощение приложений на портале "Мои приложения" с использованием коллекций.</span><span class="sxs-lookup"><span data-stu-id="bc3db-391">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="bc3db-392">Локальная служба Active Directory и ее среда подготовлены к службе Azure AD Premium, в том числе об исправлении выявленных проблем, препятствующих интеграции с Azure AD и функциями Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="bc3db-392">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc3db-393"><strong>Azure Information Protection (P2 или EMS E5)</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-393"><strong>Azure Information Protection (P2 or EMS E5)</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-394">Мы предоставляем руководство по посылкам:</span><span class="sxs-lookup"><span data-stu-id="bc3db-394">We provide guidance on how to:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-395">Активируйте и настройте клиент.</span><span class="sxs-lookup"><span data-stu-id="bc3db-395">Activate and configure your tenant.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-396">Создание и настройка меток и политик.</span><span class="sxs-lookup"><span data-stu-id="bc3db-396">Create and set up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-397">Применение защиты данных к документам.</span><span class="sxs-lookup"><span data-stu-id="bc3db-397">Apply information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-398">Автоматическая классификация и пометка сведений в приложениях Office (например, Word, PowerPoint, Excel и Outlook), работающих в Windows и использующих клиент Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="bc3db-398">Automatically classify and label information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-399">Использование неактивных файлов с помощью сканера Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="bc3db-399">Use files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-400">Отслеживание сообщений электронной почты в пути с помощью правил потока обработки почты Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc3db-400">Monitor emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-401">Также мы предоставляем рекомендации, если вы хотите применить защиту с помощью служб Microsoft Azure Rights Management (Azure RMS), шифрования сообщений Office 365 (OME) и защиты от потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="bc3db-401">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="bc3db-402">Уже должны выполняться:</span><span class="sxs-lookup"><span data-stu-id="bc3db-402">You should already:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-403">Используйте Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-403">Use Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-404">Используйте Windows или iOS (операционные системы выходят за рамки этой области).</span><span class="sxs-lookup"><span data-stu-id="bc3db-404">Use either Windows or iOS (other operating systems are out of scope).</span></span>  
  </ul><span data-ttu-id="bc3db-405">
<strong>Примечание.</strong>Компьютеры и мобильные устройства должны работать в <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">операционной системе,</a> поддерживающем Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="bc3db-405">
<strong>Note</strong>: Computers and mobile devices must run on an <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">operating system</a> that supports Azure Information Protection.</span></span>  
<li>  <span data-ttu-id="bc3db-406">Ваши основные расположения файловых ресурсов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-406">Have your main file share locations.</span></span>  </li><span data-ttu-id="bc3db-407">
<strong>Примечание.</strong>Для гибридной поддержки требуется соединитель AD RMS.</span><span class="sxs-lookup"><span data-stu-id="bc3db-407">
<strong>Note</strong>: Hybrid support requires the AD RMS connector.</span></span> 
<li>  <span data-ttu-id="bc3db-408">Наличие утвержденной таксономии классификации.</span><span class="sxs-lookup"><span data-stu-id="bc3db-408">Have an approved classification taxonomy.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-409">Узнайте обо всех нормативных ограничениях, связанных с защитой ключами.</span><span class="sxs-lookup"><span data-stu-id="bc3db-409">Understand any regulatory restrictions for your protected key management.</span></span>  </li><span data-ttu-id="bc3db-410">
</ul>
  
<strong>Сканер Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-410">
</ul>
  
<strong>Azure Information Protection scanner</strong></span></span>  
  
<span data-ttu-id="bc3db-411">Уже должны выполняться:</span><span class="sxs-lookup"><span data-stu-id="bc3db-411">You should already:</span></span>  
<ul>
<li>  <span data-ttu-id="bc3db-412">Используйте Windows Server 2012 R2 или Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="bc3db-412">Use Windows Server 2012 R2 or Windows Server 2016.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-413">Подключение к Интернету;</span><span class="sxs-lookup"><span data-stu-id="bc3db-413">Have an internet connection.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-414">Поместите Microsoft SQL Server 2012 или более поздней версии в локальном или удаленном экземпляре.</span><span class="sxs-lookup"><span data-stu-id="bc3db-414">Have Microsoft SQL Server 2012 onward in a local or remote instance.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-415">Создать учетную запись для локальной службы Active Directory и синхронизировать ее с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-415">Have a service account created for your on-premises Active Directory and synchronized with Azure AD.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-416">Скачали AzInfoProtection.exe.</span><span class="sxs-lookup"><span data-stu-id="bc3db-416">Have downloaded AzInfoProtection.exe.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-417">Метки настроены для автоматической классификации и защиты.</span><span class="sxs-lookup"><span data-stu-id="bc3db-417">Have labels configured for Automatic Classification/Protection.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc3db-418"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-418"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-419">Мы предоставляем рекомендации по подготовке Intune в качестве облачного решения управления мобильными устройствами (MDM) и службы управления мобильными приложениями (MAM) для ваших приложений и устройств.</span><span class="sxs-lookup"><span data-stu-id="bc3db-419">We provide guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="bc3db-420">Конкретные действия зависят от исходной среды и основаны на мобильном устройстве и требованиях к управлению мобильными приложениями.</span><span class="sxs-lookup"><span data-stu-id="bc3db-420">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="bc3db-421">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="bc3db-421">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-422">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="bc3db-422">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-423">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory или облачных удостоверений (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="bc3db-423">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-424">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="bc3db-424">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-425">Настройка центра MDM в соответствии с потребностями управления, в том числе:</span><span class="sxs-lookup"><span data-stu-id="bc3db-425">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-426">Настройка Intune в качестве центра MDM, когда Intune является единственным решением MDM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-426">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-427">Предоставление рекомендаций по MDM для следующих действий:</span><span class="sxs-lookup"><span data-stu-id="bc3db-427">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-428">Настройка тестовых групп, используемых для проверки политик управления MDM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-428">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-429">Настройка политик управления MDM и таких служб, как:</span><span class="sxs-lookup"><span data-stu-id="bc3db-429">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-430">Развертывание приложений для каждой поддерживаемой платформы с помощью веб-ссылок или глубоких ссылок.</span><span class="sxs-lookup"><span data-stu-id="bc3db-430">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-431">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="bc3db-431">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-432">Развертывание профилей электронной почты, беспроводных сетей и VPN), если в вашей организации есть центр сертификации, беспроводная сеть или VPN.</span><span class="sxs-lookup"><span data-stu-id="bc3db-432">Deployment of email, wireless networks, and VPN)profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-433">Настройка соединителя Microsoft Intune с Exchange (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="bc3db-433">Setting up the Microsoft Intune Exchange Connector (when applicable).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-434">Подключение к хранилищу данных Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-434">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-435">Интеграция Intune со следующими компонентами:</span><span class="sxs-lookup"><span data-stu-id="bc3db-435">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-436">Team Viewer для удаленной поддержки (необходима подписка На Team Viewer).</span><span class="sxs-lookup"><span data-stu-id="bc3db-436">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-437">Решения партнера Mobile Threat Defense (MTD) (требуется подписка MTD).</span><span class="sxs-lookup"><span data-stu-id="bc3db-437">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-438">Решение для управления совпадениями на теневые стоитящие (требуется подписка на решение для управления предыдущими сервисами).</span><span class="sxs-lookup"><span data-stu-id="bc3db-438">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-439">ATP в Microsoft Defender (требуется лицензия Windows E5 или Microsoft 365 E5);</span><span class="sxs-lookup"><span data-stu-id="bc3db-439">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-440">Регистрация устройств всех поддерживаемых платформ в Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-440">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="bc3db-441">Предоставление рекомендаций по защите приложений:</span><span class="sxs-lookup"><span data-stu-id="bc3db-441">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-442">Настройка политик защиты приложений для каждой поддерживаемой платформы.</span><span class="sxs-lookup"><span data-stu-id="bc3db-442">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-443">Настройка политик условного доступа для управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-443">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-444">Выбор соответствующих групп пользователей с помощью ранее упомянутых политик MAM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-444">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-445">Использование отчетов об использовании управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-445">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-446">Предоставление рекомендаций по миграции со старого управления компьютерами в Intune MDM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-446">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="bc3db-447">
  <strong>Примечание.</strong>Управление устаревшими компьютерами с 15 октября 2020 г. и более поздних.</span><span class="sxs-lookup"><span data-stu-id="bc3db-447">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="bc3db-448"></li>
</ul>
  
<strong>Подключение к облаку</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-448"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="bc3db-449">Мы поможем вам подготовиться к облачному подключению существующих сред диспетчера конфигураций с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-449">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="bc3db-450">Конкретные действия зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="bc3db-450">The exact steps depend on your source environment.</span></span> <span data-ttu-id="bc3db-451">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="bc3db-451">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="bc3db-452">Объяснение преимуществ облачного подключения диспетчера конфигураций с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-452">Explaining the benefits of cloud-attaching Configuration Manager with Intune.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-453">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="bc3db-453">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-454">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory и облачных удостоверений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-454">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-455">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="bc3db-455">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-456">Включение подключения к облаку в консоли диспетчера конфигураций.</span><span class="sxs-lookup"><span data-stu-id="bc3db-456">Enabling cloud-attach in the Configuration Manager console.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-457">Предоставление рекомендаций по настройке гибридного присоединению к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="bc3db-457">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-458">Предоставление рекомендаций по настройке Azure AD для автоматической регистрации MDM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-458">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-459">Предоставление рекомендаций по настройке шлюза управления облачными клиентами.</span><span class="sxs-lookup"><span data-stu-id="bc3db-459">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-460">Настройка поддерживаемых рабочих нагрузок, которые нужно перевести в Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-460">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-461">Установка клиента диспетчера конфигураций на устройствах, зарегистрированных в Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-461">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="bc3db-462"><strong>Безопасное развертывание Outlook Mobile для iOS и Android</strong> Мы предлагаем рекомендации, которые помогут вам безопасно развернуть Outlook Mobile для iOS и Android в вашей организации, чтобы гарантировать установку всех необходимых приложений для пользователей.</span><span class="sxs-lookup"><span data-stu-id="bc3db-462"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="bc3db-463">Действия по безопасному развертыванию Outlook Mobile для iOS и Android с помощью Intune зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="bc3db-463">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="bc3db-464">К ним могут относиться:</span><span class="sxs-lookup"><span data-stu-id="bc3db-464">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-465">Скачивание приложений Outlook для iOS и Android, Microsoft Authenticator и корпоративного портала Intune через Магазин Apple App Store или Google Play Маркет.</span><span class="sxs-lookup"><span data-stu-id="bc3db-465">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-466">Предоставление рекомендаций по настройке указанных ниже возможностей.</span><span class="sxs-lookup"><span data-stu-id="bc3db-466">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-467">Развертывание приложений Outlook для iOS и Android, Microsoft Authenticator и "Корпоративный портал Intune" с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-467">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-468">Политики защиты приложений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-468">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-469">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="bc3db-469">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-470">Политики настройки приложений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-470">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="bc3db-471"><strong>Примечание.</strong>FastTrack не поддерживает защиту Outlook для iOS и Android с помощью политик почтовых ящиков мобильных устройств Exchange.</span><span class="sxs-lookup"><span data-stu-id="bc3db-471"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="bc3db-472">Для <a href="https://go.microsoft.com/fwlink/?linkid=2080150">получения поддержки обратитесь</a> к партнеру Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="bc3db-472">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="bc3db-473">При планировании развертывания беспроводных сетей и профилей VPN с помощью Intune ИТ-администраторы должны иметь существующие инфраструктуры центра сертификации, беспроводных сетей и VPN, уже испорченных в рабочих средах.</span><span class="sxs-lookup"><span data-stu-id="bc3db-473">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="bc3db-474"><strong>Примечание.</strong>Преимущество службы FastTrack не включает помощь по настройке центров сертификации, беспроводных сетей, VPN или push-сертификатов MDM Apple для Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-474"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  

<span data-ttu-id="bc3db-475"><strong>Облачное подключение диспетчера конфигураций с помощью Intune</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-475"><strong>Cloud-attach Configuration Manager with Intune</strong></span></span>  

 <span data-ttu-id="bc3db-476">При использовании подключения к облаку ИТ-администраторы несут ответственность за подготовку локальной среды.</span><span class="sxs-lookup"><span data-stu-id="bc3db-476">With cloud-attach, IT admins are responsible for preparing the on-premises environment.</span></span> <span data-ttu-id="bc3db-477">Сюда может входить исправление проблем, препятствующих подключению к облаку сред configuration Manager с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="bc3db-477">This can include remediation of issues that prevent you from cloud-attaching your Configuration Manager environments with Intune.</span></span>  
  <span data-ttu-id="bc3db-478"><strong>Примечание</strong>. Преимущество службы FastTrack не включает помощь по настройке или обновлению сервера сайта диспетчера конфигураций или клиента диспетчера конфигураций до минимальных требований, необходимых для поддержки подключения к облаку.</span><span class="sxs-lookup"><span data-stu-id="bc3db-478"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="bc3db-479">Для <a href="https://go.microsoft.com/fwlink/?linkid=2080150">получения поддержки обратитесь</a> к партнеру Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="bc3db-479">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="bc3db-480"><strong>Интеграция Intune с Advanced Threat Protection (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-480"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="bc3db-481"><strong>Примечание.</strong>Мы предоставляем помощь по интеграции Intune с ATP в Microsoft Defender и созданию политик соответствия требованиям для устройств на основе оценки уровня риска Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-481"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="bc3db-482">Мы не предоставляем помощь по покупкам, лицензированию и активации.</span><span class="sxs-lookup"><span data-stu-id="bc3db-482">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="bc3db-483">Для <a href="https://go.microsoft.com/fwlink/?linkid=2080150">получения поддержки обратитесь</a> к партнеру Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="bc3db-483">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="bc3db-484"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-484"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="bc3db-485">ИТ-администраторы отвечают за регистрацию устройств в организации путем отправки поставщиком оборудования идентификаторов оборудования от имени администраторов или с помощью самостоятельной их отправки в службу Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="bc3db-485">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
<span data-ttu-id="bc3db-486"><strong>Безопасное развертывание Outlook для iOS и Android с помощью Intune </strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-486"><strong>Deploy Outlook for iOS and Android securely with Intune </strong></span></span>  
<ul>
<li>  <span data-ttu-id="bc3db-487">Удостоверения пользователей включены в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-487">User identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-488">Exchange Online или гибридная среда Exchange настроена с использованием назначенных лицензий пользователей.</span><span class="sxs-lookup"><span data-stu-id="bc3db-488">Exchange Online or hybrid Exchange configured with user licenses assigned.</span></span>  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="bc3db-489">Windows 10</span><span class="sxs-lookup"><span data-stu-id="bc3db-489">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bc3db-490"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-490"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="bc3db-491"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-491"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="bc3db-492"><strong>Ограничения, касание исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-492"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc3db-493"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-493"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-494">Мы предоставляем рекомендации, которые помогут вам перенести С Windows 7 Профессиональная и Windows 8.1 Профессиональная до Windows 10 Корпоративная.</span><span class="sxs-lookup"><span data-stu-id="bc3db-494">We provide guidance to help you upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="bc3db-495">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-495">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-496">Понимание намерения, касающуюся Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-496">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-497">Оценка исходной среды и требований (обеспечьте обновление Microsoft Endpoint Configuration Manager до необходимого уровня для поддержки развертывания Windows 10).</span><span class="sxs-lookup"><span data-stu-id="bc3db-497">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-498">Развертывание Windows 10 Корпоративная и приложений Microsoft 365 с помощью Microsoft Endpoint Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-498">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-499">Рекомендуемые варианты оценки приложений для Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-499">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-500">Обеспечение использования службы "Аналитика компьютеров" и указания посозданию плана развертывания "Аналитика компьютеров".</span><span class="sxs-lookup"><span data-stu-id="bc3db-500">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-501">Оценка совместимости приложений Microsoft 365 с помощью панели мониторинга готовности к Office 365 в Configuration Manager или автономном средстве readiness Toolkit for Office plussistance, в которой развертываются приложения Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-501">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-502">Оценка современных стратегий управления, в том числе подключение к облаку Configuration Manager с Microsoft Intune или развертывание Intune в качестве единственного облачного решения для управления.</span><span class="sxs-lookup"><span data-stu-id="bc3db-502">Assessing your modern management strategies, including cloud-attaching Configuration Manager with Microsoft Intune or deploying Intune as the sole cloud management solution.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-503">Создайте контрольный список устранения проблем, чтобы принудить к исходной среде до минимальных требований для успешного развертывания.</span><span class="sxs-lookup"><span data-stu-id="bc3db-503">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-504">Предоставление рекомендаций по обновлению для существующих устройств до Windows 10 Корпоративная, если они соответствуют требованиям к оборудованию устройства.</span><span class="sxs-lookup"><span data-stu-id="bc3db-504">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-505">Предоставление рекомендаций по обновлению для поддержки существующего процесса развертывания.</span><span class="sxs-lookup"><span data-stu-id="bc3db-505">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="bc3db-506">FastTrack предоставляет рекомендации и инструкции по обновлению до Windows 10 на месте.</span><span class="sxs-lookup"><span data-stu-id="bc3db-506">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="bc3db-507">Кроме того, предоставляются инструкции по установке чистых образов Windows и для сценариев развертывания Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="bc3db-507">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-508">Развертывание приложений Microsoft 365 с помощью Configuration Manager в рамках развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-508">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="bc3db-509">Предоставление рекомендаций по обеспечению актуальности Windows 10 Корпоративная и приложений Microsoft 365 с помощью существующей среды Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="bc3db-509">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-510">Предоставление рекомендаций по обеспечению возможности современного управления с помощью облачного подключения Configuration Manager к Intune или посредством развертывания автономного режима Intune (если это необходимо).</span><span class="sxs-lookup"><span data-stu-id="bc3db-510">Providing guidance to enable modern management by cloud-attaching Configuration Manager to Intune or by deploying Intune standalone (where required).</span></span>  </li>
</ul><span data-ttu-id="bc3db-511">
  <strong>Ниже приведен аналогичные действия вне области разрешений </strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-511">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="bc3db-512">Обновление Configuration Manager до Current Branch.</span><span class="sxs-lookup"><span data-stu-id="bc3db-512">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-513">Создание настраиваемых образов для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-513">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-514">Создание и поддержка сценариев для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-514">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-515">Переход с BIOS на UEFI в системах с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-515">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-516">Включение функций безопасности Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-516">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-517">Настройка служб развертывания Windows (WDS) для загрузки с помощью протокола удаленной загрузки (PXE).</span><span class="sxs-lookup"><span data-stu-id="bc3db-517">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-518">Запись и развертывание образов Windows 10 с помощью набора средств Microsoft Deployment Toolkit (MDT).</span><span class="sxs-lookup"><span data-stu-id="bc3db-518">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-519">Использование средства миграции пользовательской среды (USMT).</span><span class="sxs-lookup"><span data-stu-id="bc3db-519">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-520">Обратитесь за <a href="https://go.microsoft.com/fwlink/?linkid=2080150">помощью к партнеру</a> Майкрософт за помощью с этими службами.</span><span class="sxs-lookup"><span data-stu-id="bc3db-520">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="bc3db-521">Для обновления ПК должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="bc3db-521">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-522">Исходная ОС: Windows 7 Корпоративная или Профессиональная, Windows 8.1 Корпоративная или Профессиональная.</span><span class="sxs-lookup"><span data-stu-id="bc3db-522">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-523">Устройства: настольный ПК, ноутбук или планшет.</span><span class="sxs-lookup"><span data-stu-id="bc3db-523">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-524">Целевая ОС: Window 10 Корпоративная.</span><span class="sxs-lookup"><span data-stu-id="bc3db-524">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="bc3db-525">Для обновления инфраструктуры должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="bc3db-525">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-526">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="bc3db-526">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-527">Версия Configuration Manager должна поддерживаться целевой версией Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-527">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="bc3db-528">Дополнительные сведения см. в таблице поддержки Configuration Manager в <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">разделе "Поддержка Windows 10 в Configuration Manager".</a></span><span class="sxs-lookup"><span data-stu-id="bc3db-528">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="bc3db-529"><strong>Расширенная защита от угроз (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="bc3db-529"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="bc3db-530">Расширенная защита от угроз (ATP) в Microsoft Defender — это платформа, разработанная для обнаружения, предотвращения и исследования расширенных угроз в корпоративных сетях, а также для реагирования на них.</span><span class="sxs-lookup"><span data-stu-id="bc3db-530">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="bc3db-531">Мы предоставляем удаленные рекомендации по по следующие задачи:</span><span class="sxs-lookup"><span data-stu-id="bc3db-531">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="bc3db-532">Развертывание технологий для защиты конечных точек.</span><span class="sxs-lookup"><span data-stu-id="bc3db-532">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-533">Настройка защиты конечных точек и профилей ограничений для устройств.</span><span class="sxs-lookup"><span data-stu-id="bc3db-533">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-534">Оценка версии ОС и управления устройствами (включая Intune, Microsoft Endpoint Configuration Manager, объекты групповой политики (GPO), сторонние конфигурации, а также состояние служб антивируса Защитника Windows или другого программного обеспечения для обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="bc3db-534">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-535">Оценка состояния антивирусных служб Windows или других программ для обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="bc3db-535">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-536">Оценка прокси-серверов и брандмауэров, ограничивающие сетевой трафик.</span><span class="sxs-lookup"><span data-stu-id="bc3db-536">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-537">Включение службы ATP в Microsoft Defender путем разъяснения способа развертывания профиля агента ATP с помощью подключенной конечной точки.</span><span class="sxs-lookup"><span data-stu-id="bc3db-537">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-538">Руководство по развертыванию, помощь по настройке и обучение:</span><span class="sxs-lookup"><span data-stu-id="bc3db-538">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-539">Управление угрозами и уязвимостями.</span><span class="sxs-lookup"><span data-stu-id="bc3db-539">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-540">Сокращение направлений атак.</span><span class="sxs-lookup"><span data-stu-id="bc3db-540">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-541">Защита нового поколения.</span><span class="sxs-lookup"><span data-stu-id="bc3db-541">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-542">Выявление конечных точек и реагирование на них.</span><span class="sxs-lookup"><span data-stu-id="bc3db-542">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-543">Автоматическое исследование и защита.</span><span class="sxs-lookup"><span data-stu-id="bc3db-543">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-544">Оценка безопасности</span><span class="sxs-lookup"><span data-stu-id="bc3db-544">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-545">Просмотр эмуляций и учебных материалов (например, сценарии практических занятий, подделка вредоносных программ и автоматизированное исследование).</span><span class="sxs-lookup"><span data-stu-id="bc3db-545">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-546">Общие сведения о функциях создания отчетов и аналитики угроз.</span><span class="sxs-lookup"><span data-stu-id="bc3db-546">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-547">Интеграция ATP Office 365 с ATP в Microsoft Defender</span><span class="sxs-lookup"><span data-stu-id="bc3db-547">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-548">Пошаговые руководства по поведению на портале Центра безопасности в Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="bc3db-548">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-549">Следующие операционные системы:</span><span class="sxs-lookup"><span data-stu-id="bc3db-549">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-550">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="bc3db-550">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-551">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="bc3db-551">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-552">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="bc3db-552">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-553">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="bc3db-553">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-554">Windows Server Semi-Annual Channel (SAC) версии 1803.</span><span class="sxs-lookup"><span data-stu-id="bc3db-554">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-555">версии macOS 10.13, 10.14 и 10.15.</span><span class="sxs-lookup"><span data-stu-id="bc3db-555">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="bc3db-556">
<strong>Примечание.</strong> Все версии Windows Server должны управляться последней версией System Center Configuration Manager 2012 (версии 1012 R2, 1511 или 1602) или Microsoft Endpoint Configuration Manager (версия 2002 или выше).</span><span class="sxs-lookup"><span data-stu-id="bc3db-556">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="bc3db-557"></li>
</ul>

<strong>Ниже приведен аналогичные действия вне области разрешений </strong>  
</span><span class="sxs-lookup"><span data-stu-id="bc3db-557"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="bc3db-558">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="bc3db-558">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-559">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="bc3db-559">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-560">Текущее управление и реагирование на угрозы.</span><span class="sxs-lookup"><span data-stu-id="bc3db-560">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-561">Подключение и настройка следующих агентов ATP в Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="bc3db-561">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-562">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="bc3db-562">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-563">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="bc3db-563">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-564">Linux.</span><span class="sxs-lookup"><span data-stu-id="bc3db-564">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-565">Мобильные устройства (Android и iOS).</span><span class="sxs-lookup"><span data-stu-id="bc3db-565">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-566">Входящая миграция и настройка сервера:</span><span class="sxs-lookup"><span data-stu-id="bc3db-566">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-567">Настройка прокси-сервера для подключений в автономном режиме.</span><span class="sxs-lookup"><span data-stu-id="bc3db-567">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-568">Настройка пакетов развертывания Configuration Manager для экземпляров и версий Configuration Manager нижнего уровня.</span><span class="sxs-lookup"><span data-stu-id="bc3db-568">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-569">Подключение серверов к центру безопасности Azure.</span><span class="sxs-lookup"><span data-stu-id="bc3db-569">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-570">Серверы не управляются с помощью Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="bc3db-570">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-571">Подключение и настройка macOS:</span><span class="sxs-lookup"><span data-stu-id="bc3db-571">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-572">Развертывание на основе Intune вручную.</span><span class="sxs-lookup"><span data-stu-id="bc3db-572">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-573">Развертывание на основе JAMF.</span><span class="sxs-lookup"><span data-stu-id="bc3db-573">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="bc3db-574">Другие развертывания на основе продукта решения управления мобильными устройствами (MDM).</span><span class="sxs-lookup"><span data-stu-id="bc3db-574">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-575">Развертывание вручную.</span><span class="sxs-lookup"><span data-stu-id="bc3db-575">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-576">Конфигурация следующих возможностей сокращения направлений атак:</span><span class="sxs-lookup"><span data-stu-id="bc3db-576">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="bc3db-577">Аппаратная изоляция.</span><span class="sxs-lookup"><span data-stu-id="bc3db-577">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-578">Управление приложениями.</span><span class="sxs-lookup"><span data-stu-id="bc3db-578">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-579">Защита от эксплойтов.</span><span class="sxs-lookup"><span data-stu-id="bc3db-579">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="bc3db-580">Сетевой брандмауэр.</span><span class="sxs-lookup"><span data-stu-id="bc3db-580">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="bc3db-581">Развертывание или конфигурация экспертов Майкрософт по угрозам.</span><span class="sxs-lookup"><span data-stu-id="bc3db-581">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-582">Настройка или обучение просмотра API или подключений sIEM.</span><span class="sxs-lookup"><span data-stu-id="bc3db-582">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-583">Развертывание или конфигурация защиты от угроз (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="bc3db-583">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="bc3db-584">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="bc3db-584">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="bc3db-585">Учебные материалы или руководства по использованию или созданию запросов Kusto.</span><span class="sxs-lookup"><span data-stu-id="bc3db-585">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="bc3db-586">Обратитесь за <a href="https://go.microsoft.com/fwlink/?linkid=2080150">помощью к партнеру</a> Майкрософт за помощью с этими службами.</span><span class="sxs-lookup"><span data-stu-id="bc3db-586">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>
