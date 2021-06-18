---
title: Продукты и возможности
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 6/16/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack и ожиданиях исходных сред, необходимых перед началом работы. На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.
ms.openlocfilehash: 0d5272079471b7dafe40e45f6c72189f1dad4c12
ms.sourcegitcommit: cff44abb4212a768ccdcfd00226793d4dc3b02d6
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/17/2021
ms.locfileid: "52994872"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="929a4-104">Продукты и возможности</span><span class="sxs-lookup"><span data-stu-id="929a4-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="929a4-105">Службы и сценарии, поддерживаемые FastTrack</span><span class="sxs-lookup"><span data-stu-id="929a4-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="929a4-106">В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack и ожиданиях исходных сред, необходимых перед началом работы.</span><span class="sxs-lookup"><span data-stu-id="929a4-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="929a4-107">На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.</span><span class="sxs-lookup"><span data-stu-id="929a4-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="929a4-108">FastTrack предоставляет рекомендации, которые помогут вам сначала с основными возможностями (общими для всех Microsoft Online Services), а затем с наведением на борт каждой службы:</span><span class="sxs-lookup"><span data-stu-id="929a4-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="929a4-109">Общие</span><span class="sxs-lookup"><span data-stu-id="929a4-109">General</span></span>](#general)
  - [<span data-ttu-id="929a4-110">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="929a4-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="929a4-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="929a4-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="929a4-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="929a4-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="929a4-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="929a4-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="929a4-114">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="929a4-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="929a4-115">Служба Assure для приложений</span><span class="sxs-lookup"><span data-stu-id="929a4-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="929a4-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="929a4-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="929a4-117">Сведения о требованиях к исходной среде для Office 365 для государственных организаций США см. в статье [Требования к исходной среде для Office 365 для государственных организаций США](/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="929a4-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="929a4-118">Общий</span><span class="sxs-lookup"><span data-stu-id="929a4-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-119"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-120"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-121"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="929a4-122"><strong>Базовое подключение</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="929a4-123">Мы предоставляем удаленные рекомендации по основной интеграции, которая включает в себя подготовка службы, клиент и интеграцию удостоверений.</span><span class="sxs-lookup"><span data-stu-id="929a4-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="929a4-124">Она также включает шаги по обеспечению основы для бортовых служб, таких как Exchange Online, SharePoint Online и Microsoft Teams, включая обсуждение вопросов <a href="/office365/enterprise/office-365-network-connectivity-principles">безопасности,</a>подключения к сети и соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>   

<span data-ttu-id="929a4-125">Подключение одной или нескольких поддерживаемых служб можно начать после завершения базового подключения.</span><span class="sxs-lookup"><span data-stu-id="929a4-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="929a4-126"></li>
</ul>  

<strong> Интеграция удостоверений </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="929a4-127">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="929a4-128">Подготовка локального удостоверения Active Directory для синхронизации с Azure Active Directory (Azure AD), включая установку и настройку Azure AD Подключение (одно- или нескольких лесных) и лицензирование (включая лицензирование на основе групп).</span><span class="sxs-lookup"><span data-stu-id="929a4-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="929a4-129">Создание облачных удостоверений, включая массовый импорт и лицензирование, включая использование группового лицензирования.</span><span class="sxs-lookup"><span data-stu-id="929a4-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="929a4-130">Выбор и включение правильного метода проверки подлинности для облачного путешествия, синхронизация хеш-паролей, сквозная проверка подлинности или службы Федерации Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="929a4-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="929a4-131">Выбор и включение более удобного опыта проверки подлинности для пользователей с помощью проверки подлинности без паролей (Fast Identity Online (FIDO)2 или Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="929a4-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="929a4-132">Включение AD FS для клиентов с одним лесом Active Directory и удостоверениями, синхронизированными с средством Azure AD Подключение.</span><span class="sxs-lookup"><span data-stu-id="929a4-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="929a4-133">Для этого Windows Server 2012 R2 Active Directory Federation Services 2.0 или больше.</span><span class="sxs-lookup"><span data-stu-id="929a4-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="929a4-134">Перенос проверки подлинности из AD FS в Azure AD с помощью синхронизации с использованием хаширования паролей или сквозной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="929a4-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="929a4-135">Перенос предварительно интегрированных приложений (например, приложений azure AD gallery software-as-a-service (SaaS) из AD FS в Azure AD для единого входного (SSO).</span><span class="sxs-lookup"><span data-stu-id="929a4-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="929a4-136">Включение интеграции приложений SaaS с SSO из галереи Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="929a4-137">Включение автоматической подготовки пользователей для предварительно интегрированных приложений <a href="/azure/active-directory/saas-apps/tutorial-list"></a> SaaS, указанных в списке учебников по интеграции приложений (ограниченных приложениями SaaS-галереи Azure AD и только исходящие подготовки).</span><span class="sxs-lookup"><span data-stu-id="929a4-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list </a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>

</td>

<td>  <span data-ttu-id="929a4-138"><strong>Включить сеть </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="929a4-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="929a4-139">В рамках FastTrack мы советуем вам рекомендации по подключению к облачным службам для обеспечения максимальной производительности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="929a4-140"><strong>Леса Active Directory</strong> Они имеют функциональный уровень леса, задав Windows Server 2003 с следующей конфигурацией леса:</span><span class="sxs-lookup"><span data-stu-id="929a4-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-141">Один лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="929a4-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="929a4-142">Топологии с одним лесом учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="929a4-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-143">Топологии с несколькими лесами учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="929a4-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-144">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory, включающим Exchange и/или Lync 2010, Lync 2013 или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="929a4-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="929a4-145">Несколько лесов учетных записей Active Directory, каждый из которых включает свою организацию Exchange.</span><span class="sxs-lookup"><span data-stu-id="929a4-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="929a4-146">Задачи, необходимые для конфигурации клиента и интеграции с Azure Active Directory, если это необходимо.</span><span class="sxs-lookup"><span data-stu-id="929a4-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="929a4-147">
  <strong>Важно</strong>  </span><span class="sxs-lookup"><span data-stu-id="929a4-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="929a4-148">Для многолесных сценариев Active Directory, если развернуты Lync 2010, Lync 2013 или Skype для бизнеса, его необходимо развернуть в том же лесу Active Directory, что и Exchange.</span><span class="sxs-lookup"><span data-stu-id="929a4-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="929a4-149">При реализации нескольких лесов Active Directory с несколькими Exchange организациями в Exchange-гибридной конфигурации общие пространства имен пользователя (UPN) между исходными лесами не поддерживаются.</span><span class="sxs-lookup"><span data-stu-id="929a4-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="929a4-150">Основные пространства имен SMTP между организациями Exchange также должны быть отдельными.</span><span class="sxs-lookup"><span data-stu-id="929a4-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="929a4-151">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/?linkid=845444">гибридных развертываниях с несколькими лесами Active Directory.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="929a4-152">Для всех конфигураций нескольких лесов развертывание служб Федерации Active Directory (AD FS) выходит за рамки.</span><span class="sxs-lookup"><span data-stu-id="929a4-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="929a4-153">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="929a4-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-154"><strong>Приложения Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="929a4-155">Мы предоставляем рекомендации по удаленному развертыванию для:</span><span class="sxs-lookup"><span data-stu-id="929a4-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-156">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="929a4-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="929a4-157">Назначение пользователям и устройствам лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="929a4-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="929a4-158">Установка приложений Microsoft 365 с портала Office 365 с помощью технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="929a4-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="929a4-159">Установка приложений Office Mobile (например, Outlook Mobile, Word Mobile, Excel Mobile и PowerPoint Mobile) на устройствах с iOS или Android.</span><span class="sxs-lookup"><span data-stu-id="929a4-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="929a4-160">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="929a4-161">Выбор и настройка локальной или облачной установки.</span><span class="sxs-lookup"><span data-stu-id="929a4-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="929a4-162">Создание XML-файла конфигурации средства развертывания Office с помощью центра развертывания Office или встроенного XML-файла для настройки пакета развертывания.</span><span class="sxs-lookup"><span data-stu-id="929a4-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="929a4-163">Развертывание с помощью Microsoft Endpoint Configuration Manager, а также создание пакета Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="929a4-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="929a4-164">Кроме того, если у вас есть макрос или надстройка, которая работала с предшествующими версиями Office и у вас проблемы с совместимостью, мы предоставляем рекомендации по исправлению проблемы совместимости без дополнительных затрат с помощью программы App Assure.</span><span class="sxs-lookup"><span data-stu-id="929a4-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="929a4-165">Дополнительные сведения см. в Windows 10 <a href="#windows-10">app</a> <strong>Assure.</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="929a4-166">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, определенном в требованиях системы для Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">и Office.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-167"><strong>Сетевое здоровье</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="929a4-168">Мы предоставляем удаленные рекомендации по получению и интерпретации данных подключения к ключевым сетям из среды, показывающие соответствие сайтов организации принципам сетевого подключения Корпорации <a href="/office365/enterprise/office-365-network-connectivity-principles">Майкрософт.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="929a4-169">Это подчеркивает оценку сети, которая напрямую влияет на скорость миграции, пользовательский опыт, производительность службы и надежность.</span><span class="sxs-lookup"><span data-stu-id="929a4-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="929a4-170">Мы также поможем вам с помощью любых действий по исправлению последствий, которые будут выделены в этих данных, чтобы помочь вам улучшить оценку сети.</span><span class="sxs-lookup"><span data-stu-id="929a4-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="929a4-171">Microsoft 365 Admin Доступ в центр.</span><span class="sxs-lookup"><span data-stu-id="929a4-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="929a4-172">Требуются новые версии Microsoft 365 приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="929a4-173">Службы расположения, включенные в качестве рекомендаций по производительности Сети в <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">центре Microsoft 365 Admin (предварительный просмотр).</a></span><span class="sxs-lookup"><span data-stu-id="929a4-173">Location services enabled as per <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="929a4-174">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="929a4-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-175"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-176"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-177"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="929a4-178"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="929a4-179">Мы предоставляем удаленные рекомендации по обеспечению безопасности облачных удостоверений для следующих сценариев.</span><span class="sxs-lookup"><span data-stu-id="929a4-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="929a4-180">

<strong>Безопасная инфраструктура фундамента</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="929a4-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="929a4-181">Настройка и включение сильной проверки подлинности для удостоверений, включая защиту с помощью многофакторной проверки подлинности Azure (только в облаке), приложения Microsoft Authenticator и комбинированной регистрации для azure MFA и сброса пароля самообслуживления (SSPR).</span><span class="sxs-lookup"><span data-stu-id="929a4-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="929a4-182">Развертывание FIDO2 или Microsoft Authenticator App.</span><span class="sxs-lookup"><span data-stu-id="929a4-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="929a4-183">Для не Azure AD Premium клиентов предоставляются рекомендации по обеспечению безопасности удостоверений с помощью по умолчанию безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="929a4-184">Для премиум-клиентов Azure AD предоставляются рекомендации по обеспечению безопасности удостоверений с помощью условного доступа.</span><span class="sxs-lookup"><span data-stu-id="929a4-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="929a4-185">Обнаружение и блокировка использования слабых паролей с помощью Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="929a4-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="929a4-186">Обеспечение удаленного доступа к локальному веб-приложениям с помощью прокси-сервера Приложения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="929a4-187">Включение обнаружения и устранения рисков с помощью Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="929a4-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="929a4-188">Включение настраиваемого экрана регистрации, включая логотип, текст и изображения с настраиваемым брендингом.</span><span class="sxs-lookup"><span data-stu-id="929a4-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="929a4-189">Безопасное совместное использование приложений и служб с гостевых пользователей с помощью Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="929a4-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="929a4-190">Управление доступом для Office 365 администраторов с помощью встроенных административных ролей управления доступом на основе ролей и уменьшение числа привилегированных учетных записей администратора.</span><span class="sxs-lookup"><span data-stu-id="929a4-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="929a4-191">Настройка гибридного присоединиться Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="929a4-192">Настройка присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="929a4-193">
  
<strong>Мониторинг и отчетность</strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-194">Включение удаленного мониторинга для AD FS, azure AD Подключение и контроллеров домена с помощью Azure AD Подключение Health.</span><span class="sxs-lookup"><span data-stu-id="929a4-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="929a4-195">
  
<strong>Управление</strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-196">Управление удостоверением Azure AD и доступ к жизненному циклу в масштабе с помощью управления правами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="929a4-197">Управление членством в группах Azure AD, доступом к корпоративным приложениям и назначениями ролей с помощью обзоров доступа к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-198">Просмотр терминов использования Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-199">Управление и управление доступом к привилегированным учетным записям администратора с помощью Azure AD управление привилегированными пользователями.</span><span class="sxs-lookup"><span data-stu-id="929a4-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="929a4-200">
  
<strong>Автоматизация и эффективность </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-201">Включение SSPR Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="929a4-202">Разрешение пользователям создавать и управлять собственными группами облачной безопасности или Office 365 с помощью управления группами самообслуживающихся Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="929a4-203">Управление делегированием доступа к корпоративным приложениям с помощью делегирования группы Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="929a4-204">Включение динамических групп Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="929a4-205">Организация приложений на портале Мои приложения с помощью коллекций.</span><span class="sxs-lookup"><span data-stu-id="929a4-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="929a4-206">Локальное active Directory и его среда были подготовлены для Azure AD Premium, включая устранение выявленных проблем, которые препятствуют интеграции с Azure AD и Azure AD Premium функциями.</span><span class="sxs-lookup"><span data-stu-id="929a4-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-207"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="929a4-208">Дополнительные сведения о Azure Information Protection <strong>см.</strong> в Microsoft Information Protection в этой таблице.</span><span class="sxs-lookup"><span data-stu-id="929a4-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="929a4-209"><strong>Откройте для себя & Respond</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="929a4-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="929a4-211">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="929a4-212">Создание нового случая.</span><span class="sxs-lookup"><span data-stu-id="929a4-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="929a4-213">Удержание хранителей.</span><span class="sxs-lookup"><span data-stu-id="929a4-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="929a4-214">Выполнение поиска.</span><span class="sxs-lookup"><span data-stu-id="929a4-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="929a4-215">Добавление результатов поиска в набор для проверки.</span><span class="sxs-lookup"><span data-stu-id="929a4-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="929a4-216">Запуск аналитики в наборе обзоров.</span><span class="sxs-lookup"><span data-stu-id="929a4-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="929a4-217">Проверка и пометка документов.</span><span class="sxs-lookup"><span data-stu-id="929a4-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="929a4-218">Экспорт данных из набора обзоров.</span><span class="sxs-lookup"><span data-stu-id="929a4-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="929a4-219">Импорт не Office 365 данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="929a4-220"><strong>Расширенный аудит</strong> (поддерживается только в E5)</span><span class="sxs-lookup"><span data-stu-id="929a4-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="929a4-221">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="929a4-222">Включение усовершенствования аудита.</span><span class="sxs-lookup"><span data-stu-id="929a4-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="929a4-223">Выполнение пользовательского интерфейса журнала аудита поиска и основных команд powerShell аудита.</span><span class="sxs-lookup"><span data-stu-id="929a4-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="929a4-224">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="929a4-225">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="929a4-226">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="929a4-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="929a4-227">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="929a4-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="929a4-228">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="929a4-229">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="929a4-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="929a4-230">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="929a4-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="929a4-231">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="929a4-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="929a4-232">Настраиваемый сценарий или кодирование.</span><span class="sxs-lookup"><span data-stu-id="929a4-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="929a4-233">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="929a4-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="929a4-234">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="929a4-235">Границы соответствия требованиям и фильтры безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="929a4-236">Исследования данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="929a4-237">Запросы субъекта данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="929a4-238">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="929a4-239">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="929a4-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="929a4-240">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="929a4-241">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="929a4-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="929a4-242"><strong>Управление рисками на инсайдерской стороне</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="929a4-243">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="929a4-244">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="929a4-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="929a4-245">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="929a4-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="929a4-246">Создание дел.</span><span class="sxs-lookup"><span data-stu-id="929a4-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="929a4-247">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="929a4-248">Руководство по созданию соединиттеля кадровых ресурсов (HR).</span><span class="sxs-lookup"><span data-stu-id="929a4-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="929a4-249">

<strong> Соответствие требованиям связи </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="929a4-250">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="929a4-251">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="929a4-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="929a4-252">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="929a4-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="929a4-253">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="929a4-254">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="929a4-255">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="929a4-256">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="929a4-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="929a4-257">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="929a4-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="929a4-258">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="929a4-259">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="929a4-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="929a4-260">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="929a4-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="929a4-261">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="929a4-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="929a4-262">Создание и управление Power Automate потоками.</span><span class="sxs-lookup"><span data-stu-id="929a4-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="929a4-263">Соединители данных (за пределами соединитетеля управления персоналом).</span><span class="sxs-lookup"><span data-stu-id="929a4-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="929a4-264">Настраиваемые конфигурации регулярного выражения (RegEx).</span><span class="sxs-lookup"><span data-stu-id="929a4-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="929a4-265">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="929a4-266">Информационные барьеры.</span><span class="sxs-lookup"><span data-stu-id="929a4-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="929a4-267">Управление привилегированным доступом.</span><span class="sxs-lookup"><span data-stu-id="929a4-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="929a4-268">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="929a4-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="929a4-269">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="929a4-270">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="929a4-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="929a4-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="929a4-272">Microsoft 365 Defender — это единый пакет защиты предприятия до и после нарушения, который в основном координирует обнаружение, предотвращение, расследование и ответные действия между конечными точками, удостоверениями, электронной почтой и приложениями для обеспечения комплексной защиты от сложных атак.</span><span class="sxs-lookup"><span data-stu-id="929a4-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="929a4-273">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="929a4-274">Предоставление обзора центра Microsoft 365 безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="929a4-275">Анализ инцидентов с перекрестным продуктом, в том числе сосредоточение внимания на критически важных задачах, обеспечивая полную область атаки, влияние на активы и автоматизированные действия по исправлению, которые сгруппировали вместе.</span><span class="sxs-lookup"><span data-stu-id="929a4-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="929a4-276">Демонстрация того Microsoft 365 Defender как можно организовать исследование активов, пользователей, устройств и почтовых ящиков, которые могли быть скомпрометированы с помощью автоматического самовосстановления.</span><span class="sxs-lookup"><span data-stu-id="929a4-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="929a4-277">Объяснение и предоставление примеров того, как клиенты могут активно охотиться за попытками вторжения и действиями взлома, влияющими на вашу электронную почту, данные, устройства и учетные записи в нескольких наборах данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="929a4-278">Показывая клиентам, как они могут целостно пересматривать и улучшать свою осанку безопасности с помощью Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="929a4-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="929a4-279"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="929a4-280">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="929a4-281">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="929a4-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="929a4-282">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="929a4-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="929a4-283">Исправление или интерпретация различных типов оповещений и отслеживаемой активности.</span><span class="sxs-lookup"><span data-stu-id="929a4-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="929a4-284">Изучение пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="929a4-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="929a4-285">Настраиваемая охота на угрозы.</span><span class="sxs-lookup"><span data-stu-id="929a4-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="929a4-286">Поддержка <a href=" /fasttrack/us-gov-appendix-overview">GCC-High или GCC-DoD (Office 365 правительства США).</a></span><span class="sxs-lookup"><span data-stu-id="929a4-286">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="929a4-287">Сведения о безопасности и управление событиями (SIEM) или интеграция API.</span><span class="sxs-lookup"><span data-stu-id="929a4-287">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-288"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-288"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="929a4-289">Microsoft Cloud App Security является брокером по безопасности облачного доступа (CASB), который обеспечивает богатую видимость, контроль над перемещениями данных и сложную аналитику для выявления и борьбы с киберугрозами во всех облачных службах Майкрософт и сторонних поставщиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-289">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="929a4-290">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-290">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-291">Настройка портала, в том числе:</span><span class="sxs-lookup"><span data-stu-id="929a4-291">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="929a4-292">Импорт групп пользователей.</span><span class="sxs-lookup"><span data-stu-id="929a4-292">Importing user groups.</span></span></li>
<li> <span data-ttu-id="929a4-293">Управление доступом и настройками администратора.</span><span class="sxs-lookup"><span data-stu-id="929a4-293">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="929a4-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span><span class="sxs-lookup"><span data-stu-id="929a4-294">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="929a4-295">Настройка ip-диапазонов и тегов.</span><span class="sxs-lookup"><span data-stu-id="929a4-295">How to set up IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="929a4-296">Персонализация интерфейса для конечных пользователей с помощью логотипа и настраиваемого обмена сообщениями.</span><span class="sxs-lookup"><span data-stu-id="929a4-296">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-297">Интеграция первопартийных служб, в том числе:</span><span class="sxs-lookup"><span data-stu-id="929a4-297">Integrating first-party services including:</span></span>
<ul>
<li> <span data-ttu-id="929a4-298">Microsoft Defender для конечной точки.</span><span class="sxs-lookup"><span data-stu-id="929a4-298">Microsoft Defender for Endpoint.</span></span></li>
<li> <span data-ttu-id="929a4-299">Microsoft Defender для удостоверений</span><span class="sxs-lookup"><span data-stu-id="929a4-299">Microsoft Defender for Identity.</span></span></li>
<li> <span data-ttu-id="929a4-300">Защита идентификации Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-300">Azure AD Identity Protection.</span></span></li>
<li> <span data-ttu-id="929a4-301">Защита информации Azure.</span><span class="sxs-lookup"><span data-stu-id="929a4-301">Azure Information Protection.</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-302">Настройка обнаружения облака с помощью:</span><span class="sxs-lookup"><span data-stu-id="929a4-302">Setting up cloud discovery using:</span></span></li>
<ul>
<li> <span data-ttu-id="929a4-303">Microsoft Defender для конечных точек.</span><span class="sxs-lookup"><span data-stu-id="929a4-303">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="929a4-304">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="929a4-304">Zscaler.</span></span></li>
<li> <span data-ttu-id="929a4-305">iboss.</span><span class="sxs-lookup"><span data-stu-id="929a4-305">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-306">Создание тегов и категорий приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-306">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="929a4-307">Настройка оценки рисков приложений в зависимости от приоритетов организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-307">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="929a4-308">Санкции и несанкционные приложения.</span><span class="sxs-lookup"><span data-stu-id="929a4-308">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="929a4-309">Обзор панелей безопасности облачных приложений и облачных открытий.</span><span class="sxs-lookup"><span data-stu-id="929a4-309">Reviewing the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="929a4-310">Подключение <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> рекомендуемых приложений с</a> помощью соединители приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-310">Connecting <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="929a4-311">Защита приложений с условным управлением приложениями доступа в условном доступе на порталах безопасности Azure AD и Cloud App.</span><span class="sxs-lookup"><span data-stu-id="929a4-311">Protecting apps with Conditional Access App Control in the Conditional Access within Azure AD and Cloud App Security portals.</span></span></li>
<li> <span data-ttu-id="929a4-312">Развертывание элементов управления приложениями условного доступа для рекомендуемых приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-312">Deploying Conditional Access App Control for featured apps.</span></span></li>
<li> <span data-ttu-id="929a4-313">Использование журналов действий и файлов.</span><span class="sxs-lookup"><span data-stu-id="929a4-313">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="929a4-314">Управление приложениями OAuth.</span><span class="sxs-lookup"><span data-stu-id="929a4-314">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="929a4-315">Проверка и настройка шаблонов политики.</span><span class="sxs-lookup"><span data-stu-id="929a4-315">Reviewing and configuring policy templates.</span></span></li>
<li> <span data-ttu-id="929a4-316">Предоставление помощи в настройке в <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> лучших случаях использования casBs (включая создание или обновление до шести политик) за исключением:</span><span class="sxs-lookup"><span data-stu-id="929a4-316">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="929a4-317">Аудит конфигурации среды интернета как среды службы (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="929a4-317">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="929a4-318">Мониторинг действий пользователей для защиты от угроз в средах IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="929a4-318">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-319">Понимание корреляции инцидентов на портале Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="929a4-319">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="929a4-320"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-320"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="929a4-321">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-321">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="929a4-322">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="929a4-322">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="929a4-323">Обсуждения, сравнивающие безопасность облачных приложений с другими предложениями CASB.</span><span class="sxs-lookup"><span data-stu-id="929a4-323">Discussions comparing Cloud App Security to other CASB offerings.</span></span></li>
<li> <span data-ttu-id="929a4-324">Настройка безопасности облачных приложений для соответствия определенным требованиям или нормативным требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-324">Configuring Cloud App Security to meet specific compliance or regulatory requirements.</span></span></li>
<li> <span data-ttu-id="929a4-325">Развертывание службы в непробной производственной среде.</span><span class="sxs-lookup"><span data-stu-id="929a4-325">Deploying the service to a non-test production environment.</span></span></li>
<li> <span data-ttu-id="929a4-326">Развертывание обнаружения облачных приложений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="929a4-326">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
<li> <span data-ttu-id="929a4-327">Поддержка <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High или GCC-DoD (Office 365 правительство США)</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-327">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="929a4-328">Настройка инфраструктуры, установки или развертывания автоматических загрузок журналов для непрерывных отчетов с помощью Docker или сборщика журналов.</span><span class="sxs-lookup"><span data-stu-id="929a4-328">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> </li>
<li> <span data-ttu-id="929a4-329">Создание отчета об обнаружении облачных данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-329">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="929a4-330">Блокировка использования приложений с помощью скриптов блоков.</span><span class="sxs-lookup"><span data-stu-id="929a4-330">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="929a4-331">Подключение настраиваемой программы.</span><span class="sxs-lookup"><span data-stu-id="929a4-331">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="929a4-332">Развертывание и развертывание элементов управления приложениями условного доступа для неимехационных приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-332">Onboarding and deploying Conditional Access App Control for non-featured apps.</span></span></li>
<li> <span data-ttu-id="929a4-333">Интеграция с сторонними поставщиками удостоверений (isPs) и поставщиками защиты от потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="929a4-333">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="929a4-334">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="929a4-334">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="929a4-335">Автоматическое исследование и исправление, включая книги Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="929a4-335">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="929a4-336">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="929a4-336">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>

</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="929a4-337"><strong>Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-337"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="929a4-338">Microsoft Defender for Endpoint — это платформа, призванная помочь корпоративным сетям предотвращать, обнаруживать, исследовать и реагировать на расширенные угрозы.</span><span class="sxs-lookup"><span data-stu-id="929a4-338">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="929a4-339">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-339">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-340">Развертывание технологий для защиты конечных точек.</span><span class="sxs-lookup"><span data-stu-id="929a4-340">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="929a4-341">Настройка профилей защиты конечной точки и ограничений устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-341">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="929a4-342">Оценка управления версиями ОС и устройствами (включая Intune, Microsoft Endpoint Configuration Manager, Объекты групповой политики (GPOs) и сторонние конфигурации), а также состояние служб av Защитник Windows или другого программного обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="929a4-342">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="929a4-343">Оценка состояния служб av Windows или другого программного обеспечения безопасности конечной точки.</span><span class="sxs-lookup"><span data-stu-id="929a4-343">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="929a4-344">Оценка прокси и брандмауэров, ограничивающих сетевой трафик.</span><span class="sxs-lookup"><span data-stu-id="929a4-344">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="929a4-345">Включение службы Microsoft Defender для конечных точек, объясняя, как развернуть профиль агента Defender для конечной точки с помощью конечной точки на борту.</span><span class="sxs-lookup"><span data-stu-id="929a4-345">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="929a4-346">Рекомендации по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="929a4-346">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-347">Управление угрозами и уязвимостями.</span><span class="sxs-lookup"><span data-stu-id="929a4-347">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-348">Сокращение направлений атак.</span><span class="sxs-lookup"><span data-stu-id="929a4-348">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-349">Защита нового поколения.</span><span class="sxs-lookup"><span data-stu-id="929a4-349">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-350">Выявление конечных точек и реагирование на них.</span><span class="sxs-lookup"><span data-stu-id="929a4-350">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-351">Автоматическое исследование и защита.</span><span class="sxs-lookup"><span data-stu-id="929a4-351">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-352">Безопасная оценка для устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-352">Secure score for devices.</span></span>  
  </li>
<li> <span data-ttu-id="929a4-353">Конфигурация Microsoft Defender SmartScreen с помощью Microsoft Endpoint Manager.</span><span class="sxs-lookup"><span data-stu-id="929a4-353">Microsoft Defender SmartScreen configuration using Microsoft Endpoint Manager.</span></span></li>

</ul></li>
<li>  <span data-ttu-id="929a4-354">Просмотр имитаций и учебных пособий (например, сценариев практики, поддельных вредоносных программ и автоматических расследований).</span><span class="sxs-lookup"><span data-stu-id="929a4-354">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="929a4-355">Общие сведения о функциях создания отчетов и аналитики угроз.</span><span class="sxs-lookup"><span data-stu-id="929a4-355">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="929a4-356">Интеграция Microsoft Defender для Office 365 с Microsoft Defender для конечной точки.</span><span class="sxs-lookup"><span data-stu-id="929a4-356">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="929a4-357">Пошаговые руководства по поведению на портале Центра безопасности в Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="929a4-357">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="929a4-358">Следующие операционные системы:</span><span class="sxs-lookup"><span data-stu-id="929a4-358">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-359">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-359">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-360">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="929a4-360">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-361">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="929a4-361">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-362">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="929a4-362">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-363">Windows Server Semi-Annual (SAC) версии 1803.</span><span class="sxs-lookup"><span data-stu-id="929a4-363">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-364">версии macOS 10.13, 10.14 и 10.15.</span><span class="sxs-lookup"><span data-stu-id="929a4-364">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="929a4-365">
<strong>Примечание:</strong> Все версии Windows Server должны управляться последней версией System Center Configuration Manager 2012 (версии 1012 R2, 1511 или 1602) или Microsoft Endpoint Configuration Manager (версии 2002 или более).</span><span class="sxs-lookup"><span data-stu-id="929a4-365">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="929a4-366"></li>
</ul>

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-366"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="929a4-367">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-367">Project management of the customer's remediation activities.</span></span>  </li>
<li> <span data-ttu-id="929a4-368">Поддержка <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High или GCC-DoD (Office 365 правительство США)</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-368">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li>  <span data-ttu-id="929a4-369">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="929a4-369">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="929a4-370">Текущее управление и реагирование на угрозы.</span><span class="sxs-lookup"><span data-stu-id="929a4-370">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="929a4-371">Учет или конфигурация для следующих агентов Microsoft Defender для конечных точек:</span><span class="sxs-lookup"><span data-stu-id="929a4-371">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-372">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="929a4-372">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-373">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="929a4-373">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-374">Linux.</span><span class="sxs-lookup"><span data-stu-id="929a4-374">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-375">Мобильные устройства (Android и iOS).</span><span class="sxs-lookup"><span data-stu-id="929a4-375">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="929a4-376">Виртуальная инфраструктура настольных компьютеров (VDI) (сохраняемая или нестойка).</span><span class="sxs-lookup"><span data-stu-id="929a4-376">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-377">Бортовая и конфигурация сервера:</span><span class="sxs-lookup"><span data-stu-id="929a4-377">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-378">Настройка прокси-сервера для автономной связи.</span><span class="sxs-lookup"><span data-stu-id="929a4-378">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-379">Настройка пакетов развертывания Configuration Manager на экземплярах и версиях диспетчера конфигурации на уровне.</span><span class="sxs-lookup"><span data-stu-id="929a4-379">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-380">На борту серверов в Центр безопасности Azure.</span><span class="sxs-lookup"><span data-stu-id="929a4-380">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-381">Серверы, не управляемые диспетчером конфигурации.</span><span class="sxs-lookup"><span data-stu-id="929a4-381">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-382">бортовая и конфигурация macOS:</span><span class="sxs-lookup"><span data-stu-id="929a4-382">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-383">Развертывание на основе ручного intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-383">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-384">Развертывание на основе JAMF.</span><span class="sxs-lookup"><span data-stu-id="929a4-384">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="929a4-385">Другое развертывание на основе продуктов для управления мобильными устройствами (MDM).</span><span class="sxs-lookup"><span data-stu-id="929a4-385">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-386">Ручное развертывание.</span><span class="sxs-lookup"><span data-stu-id="929a4-386">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-387">Конфигурация следующих возможностей сокращения направлений атак:</span><span class="sxs-lookup"><span data-stu-id="929a4-387">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-388">Аппаратная изоляция.</span><span class="sxs-lookup"><span data-stu-id="929a4-388">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-389">Управление приложениями.</span><span class="sxs-lookup"><span data-stu-id="929a4-389">App control.</span></span>  
  </li>
<li> <span data-ttu-id="929a4-390">Управление устройствами.</span><span class="sxs-lookup"><span data-stu-id="929a4-390">Device control.</span></span></li>
<li>  
  <span data-ttu-id="929a4-391">Защита от эксплойтов.</span><span class="sxs-lookup"><span data-stu-id="929a4-391">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-392">Сетевой брандмауэр.</span><span class="sxs-lookup"><span data-stu-id="929a4-392">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="929a4-393">Конфигурация или управление функциями защиты учетных записей, например:</span><span class="sxs-lookup"><span data-stu-id="929a4-393">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="929a4-394">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="929a4-394">Windows Hello</span></span></li>
<li> <span data-ttu-id="929a4-395">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="929a4-395">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-396">Конфигурация или управление BitLocker.</span><span class="sxs-lookup"><span data-stu-id="929a4-396">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="929a4-397">Развертывание или конфигурация экспертов Майкрософт по угрозам.</span><span class="sxs-lookup"><span data-stu-id="929a4-397">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="929a4-398">Настройка или обучение, просмотр API или сведений о безопасности и подключений к управлению событиями (SIEM).</span><span class="sxs-lookup"><span data-stu-id="929a4-398">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="929a4-399">Регистрация или конфигурация Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="929a4-399">Enrollment or configuration of Microsoft 365 Defender.</span></span>  </li>
<li>  <span data-ttu-id="929a4-400">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="929a4-400">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="929a4-401">Учебные материалы или руководства по использованию или созданию запросов Kusto.</span><span class="sxs-lookup"><span data-stu-id="929a4-401">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
<li> <span data-ttu-id="929a4-402">Обучение или руководство, охватывающие конфигурацию Defender SmartScreen с использованием объектов групповой политики (GPOs), Безопасность Windows или Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="929a4-402">Training or guidance covering Defender SmartScreen configuration using Group Policy Objects (GPOs), Windows Security, or Microsoft Edge.</span></span></li>
</li>
</ul>
<span data-ttu-id="929a4-403">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="929a4-403">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="929a4-404"><strong>Защитник Майкрософт для удостоверения </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-404"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="929a4-405">Microsoft Defender для удостоверений — это облачное решение для обеспечения безопасности, использующее ваши локальные сигналы Active Directory для выявления, обнаружения и исследования расширенных угроз, скомпрометированных удостоверений и вредоносных внутренних действий, направленных против вашей организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-405">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="929a4-406">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-406">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-407">Запуск средства размеров для планирования емкости ресурсов.</span><span class="sxs-lookup"><span data-stu-id="929a4-407">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>   <span data-ttu-id="929a4-408">Создание экземпляра Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="929a4-408">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="929a4-409">Подключение защитника удостоверений к Active Directory.</span><span class="sxs-lookup"><span data-stu-id="929a4-409">Connecting Defender for Identity to Active Directory.</span></span> </li>

<li>  <span data-ttu-id="929a4-410">Развертывание датчика для захвата и размыва сетевого трафика и Windows событий непосредственно из контроллеров домена, в том числе:</span><span class="sxs-lookup"><span data-stu-id="929a4-410">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="929a4-411">Загрузка пакета датчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-411">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="929a4-412">Настройка датчика.</span><span class="sxs-lookup"><span data-stu-id="929a4-412">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="929a4-413">Установка датчика на контроллере домена безмолвно.</span><span class="sxs-lookup"><span data-stu-id="929a4-413">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="929a4-414">Развертывание датчика в многолесной среде.</span><span class="sxs-lookup"><span data-stu-id="929a4-414">Deploying the sensor to your multi-forest environment.</span></span> </li>
<li> <span data-ttu-id="929a4-415">Настройка Windows событий.</span><span class="sxs-lookup"><span data-stu-id="929a4-415">Configuring the Windows Event Collector.</span></span></li>
</ul>
<li>  <span data-ttu-id="929a4-416">Настройка портала, в том числе:</span><span class="sxs-lookup"><span data-stu-id="929a4-416">Configuring the portal, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="929a4-417">Интеграция defender for Identity с Microsoft Cloud App Security (Cloud App Security лицензирование не требуется).</span><span class="sxs-lookup"><span data-stu-id="929a4-417">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li> <span data-ttu-id="929a4-418">Настройка тегов сущности.</span><span class="sxs-lookup"><span data-stu-id="929a4-418">Configuring entity tags.</span></span></li>
<li> <span data-ttu-id="929a4-419">Пометка конфиденциальных учетных записей.</span><span class="sxs-lookup"><span data-stu-id="929a4-419">Tagging sensitive accounts.</span></span> </li>
<li> <span data-ttu-id="929a4-420">Получение уведомлений электронной почты о проблемах со здоровьем и оповещениях о безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-420">Receiving email notifications for health issues and security alerts.</span></span> </li>
<li> <span data-ttu-id="929a4-421">Настройка исключений оповещений.</span><span class="sxs-lookup"><span data-stu-id="929a4-421">Configuring alert exclusions.</span></span>  </li>
</ul>
<li> <span data-ttu-id="929a4-422">Предоставление рекомендаций по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="929a4-422">Providing deployment guidance, configuration assistance, and education on:</span></span></li>
<ul>
<li> <span data-ttu-id="929a4-423">Понимание отчета об оценке осанки безопасности удостоверений.</span><span class="sxs-lookup"><span data-stu-id="929a4-423">Understanding the Identity Security Posture Assessment report.</span></span></li>
<li> <span data-ttu-id="929a4-424">Понимание отчета о рейтинге приоритетов в расследовании пользователей и рейтинге пользователей.</span><span class="sxs-lookup"><span data-stu-id="929a4-424">Understanding the User Investigation Priority Score and User Investigation ranking report.</span></span></li>
<li> <span data-ttu-id="929a4-425">Понимание неактивного отчета пользователя.</span><span class="sxs-lookup"><span data-stu-id="929a4-425">Understanding the inactive user report.</span></span></li>
<li> <span data-ttu-id="929a4-426">Разъяснение параметров восстановления в скомпрометированной учетной записи.</span><span class="sxs-lookup"><span data-stu-id="929a4-426">Explanation of the remediation options on a compromised account.</span></span></li>
</ul>
<li>  <span data-ttu-id="929a4-427">Упрощение переноса из Advanced Threat Analytics (ATA) в Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="929a4-427">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="929a4-428"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-428"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="929a4-429">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-429">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="929a4-430">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="929a4-430">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="929a4-431">Развертывание Defender для удостоверений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="929a4-431">Deploying Defender for Identity as a proof of concept.</span></span></li>
<li> <span data-ttu-id="929a4-432">Поддержка <a href=" /fasttrack/us-gov-appendix-overview">GCC-High или GCC-DoD (Office 365 правительства США).</a></span><span class="sxs-lookup"><span data-stu-id="929a4-432">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="929a4-433">Развертывание или выполнение следующих действий датчика "Защитник для удостоверения":</span><span class="sxs-lookup"><span data-stu-id="929a4-433">Deploying or performing the following Defender for Identity sensor activities:</span></span> </li>
<ul>
<li> <span data-ttu-id="929a4-434">Ручное планирование емкости.</span><span class="sxs-lookup"><span data-stu-id="929a4-434">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="929a4-435">Запуск средства аудита.</span><span class="sxs-lookup"><span data-stu-id="929a4-435">Running the Auditing tool.</span></span> </li>
<li> <span data-ttu-id="929a4-436">Развертывание автономных датчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-436">Deploying the standalone sensor.</span></span> </li>
<li> <span data-ttu-id="929a4-437">Развертывание на серверах служб Федерации Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="929a4-437">Deploying to Active Directory Federation Services (AD FS) servers.</span></span>
<li> <span data-ttu-id="929a4-438">Развертывание датчика с помощью адаптора сетевого интерфейса (NIC).</span><span class="sxs-lookup"><span data-stu-id="929a4-438">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="929a4-439">Развертывание датчика через сторонний инструмент.</span><span class="sxs-lookup"><span data-stu-id="929a4-439">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="929a4-440">Подключение к облачной службе Defender for Identity с помощью подключения веб-прокси.</span><span class="sxs-lookup"><span data-stu-id="929a4-440">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="929a4-441">Настройка учетной записи Майкрософт (MSA) в Active Directory.</span><span class="sxs-lookup"><span data-stu-id="929a4-441">Configuring the Microsoft account (MSA) in Active Directory.</span></span>
<li> <span data-ttu-id="929a4-442">Создание и управление медоносами.</span><span class="sxs-lookup"><span data-stu-id="929a4-442">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="929a4-443">Включение разрешения сетевых имен (NNR).</span><span class="sxs-lookup"><span data-stu-id="929a4-443">Enabling Network Name Resolution (NNR).</span></span> </li>
<li> <span data-ttu-id="929a4-444">Конфигурация контейнера удаленных объектов.</span><span class="sxs-lookup"><span data-stu-id="929a4-444">Configuration of Deleted Objects container.</span></span></li>
<li> <span data-ttu-id="929a4-445">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="929a4-445">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="929a4-446">Исправление или интерпретация различных типов оповещений и отслеживаемой деятельности.</span><span class="sxs-lookup"><span data-stu-id="929a4-446">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="929a4-447">Исследование пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="929a4-447">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="929a4-448">Угроза или продвинутая охота.</span><span class="sxs-lookup"><span data-stu-id="929a4-448">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="929a4-449">Реагирование на инцидент.</span><span class="sxs-lookup"><span data-stu-id="929a4-449">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="929a4-450">Предоставление лабораторного руководства по оповещению о безопасности для Defender для identity.</span><span class="sxs-lookup"><span data-stu-id="929a4-450">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="929a4-451">Предоставление уведомлений, когда Defender for Identity обнаруживает подозрительные действия, отправляя оповещения безопасности на сервер syslog с помощью назначенного датчика.</span><span class="sxs-lookup"><span data-stu-id="929a4-451">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="929a4-452">Настройка defender for Identity для выполнения запросов с помощью удаленного протокола диспетчера безопасности (SAMR) для идентификации локальных администраторов на определенных машинах.</span><span class="sxs-lookup"><span data-stu-id="929a4-452">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="929a4-453">Настройка VPN-решений для добавления сведений из VPN-подключения на страницу профиля пользователя.</span><span class="sxs-lookup"><span data-stu-id="929a4-453">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="929a4-454">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="929a4-454">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="929a4-455">Согласовано с <a href="/defender-for-identity/prerequisites">условиями Microsoft Defender для удостоверений.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-455">Aligned with <a href="/defender-for-identity/prerequisites"> Microsoft Defender for Identity prerequisites</a>.</span></span> </li>
<li>  <span data-ttu-id="929a4-456">Развернут Active Directory.</span><span class="sxs-lookup"><span data-stu-id="929a4-456">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="929a4-457">Контроллеры домена, которые вы собираетесь установить датчики Defender для удостоверений, подключены к облачной службе Defender для удостоверений.</span><span class="sxs-lookup"><span data-stu-id="929a4-457">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="929a4-458">Брандмауэр и прокси должны быть открыты для связи с облачной службой Defender for Identity (\*.atp.azure.com порт 443 должен быть открыт).</span><span class="sxs-lookup"><span data-stu-id="929a4-458">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-459">Контроллеры домена, работающие на одном из следующих:</span><span class="sxs-lookup"><span data-stu-id="929a4-459">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="929a4-460">Windows Сервер 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="929a4-460">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="929a4-461">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="929a4-461">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="929a4-462">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="929a4-462">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="929a4-463">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="929a4-463">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="929a4-464">Windows Server 2019 с KB4487044 (сборка ОС 17763.316 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="929a4-464">Windows Server 2019 with KB4487044 (OS Build 17763.316 or later).</span></span></li>
</ul>
<li> <span data-ttu-id="929a4-465">Microsoft платформа .NET Framework 4.7 или более поздней.</span><span class="sxs-lookup"><span data-stu-id="929a4-465">Microsoft .NET Framework 4.7 or later.</span></span></li>
<li> <span data-ttu-id="929a4-466">Требуется не менее пяти (5) ГБ дискового пространства и рекомендуется использовать 10 ГБ.</span><span class="sxs-lookup"><span data-stu-id="929a4-466">A minimum of five (5) GB of disk space is required and 10 GB is recommended.</span></span></li>
<li> <span data-ttu-id="929a4-467">Два (2) ядра и шесть (6) ГБ оперативной памяти, установленные на контроллере домена.</span><span class="sxs-lookup"><span data-stu-id="929a4-467">Two (2) cores and six (6) GB of RAM installed on the domain controller.</span></span></li>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="929a4-468"><strong>Microsoft Defender для Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-468"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="929a4-p114">Microsoft Defender для Office 365 защищает организацию от злонамеренных угроз, связанных с сообщениями электронной почты, ссылками (URL-адресами) и средствами для совместной работы. Defender для Office 365 включает:</span><span class="sxs-lookup"><span data-stu-id="929a4-p114">Microsoft Defender for Office 365 safeguards your organization against malicious threats posed by email messages, links (URLs), and collaboration tools. Defender for Office 365 includes: </span></span><ul>
<li> <span data-ttu-id="929a4-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Политики защиты от угроз.</a>Определите политики защиты от угроз, чтобы установить соответствующий уровень защиты для вашей организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-471"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> Threat protection policies</a>: Define threat-protection policies to set the appropriate level of protection for your organization.</span></span></li>
<li> <span data-ttu-id="929a4-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Отчеты.</a>Просмотр отчетов в режиме реального времени для мониторинга производительности Defender Office 365 в организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-472"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">Reports</a>: View real-time reports to monitor Defender for Office 365 performance in your organization.</span></span></li>
<li> <span data-ttu-id="929a4-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Анализ угроз и реагирование на них</a>. Используйте передовые инструменты для анализа, изучения, моделирования и предотвращения угроз.</span><span class="sxs-lookup"><span data-stu-id="929a4-473"><a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">Threat investigation and response capabilities</a>: Use leading-edge tools to investigate, understand, simulate, and prevent threats.</span></span></li>
<li> <span data-ttu-id="929a4-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Автоматизированный анализ угроз и реагирование на них</a>. Экономьте время и усилия при анализе и устранении угроз.</span><span class="sxs-lookup"><span data-stu-id="929a4-474"><a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">Automated investigation and response capabilities</a>: Save time and effort investigating and mitigating threats.</span></span></li>
</ul>

<span data-ttu-id="929a4-475">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-475">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-476">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="929a4-476">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="929a4-477">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="929a4-477">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="929a4-478">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="929a4-478">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="929a4-479">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="929a4-479">Reporting and threat analytics.</span></span>  </li>
<li>  <span data-ttu-id="929a4-480">Понимание корреляции инцидентов на Microsoft 365 Defender портале.</span><span class="sxs-lookup"><span data-stu-id="929a4-480">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
</ul>
<p><span data-ttu-id="929a4-481"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-481"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="929a4-482">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="929a4-482">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="929a4-483">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="929a4-483">Ongoing management, threat response, and remediation.</span></span></li>
<li> <span data-ttu-id="929a4-484">Поддержка <a href=" /fasttrack/us-gov-appendix-overview">GCC-High или GCC-DoD (Office 365 правительства США).</a></span><span class="sxs-lookup"><span data-stu-id="929a4-484">Supporting <a href=" /fasttrack/us-gov-appendix-overview"> GCC-High or GCC-DoD (Office 365 US Government)</a>.</span></span></li>
<li> <span data-ttu-id="929a4-485">Обсуждения, сравнивающие Defender для Office 365 с другими предложениями по безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-485">Discussions comparing Defender for Office 365 to other security offerings.</span></span></li>
<li> <span data-ttu-id="929a4-486">Развертывание Defender для Office 365 в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="929a4-486">Deploying Defender for Office 365 as a proof of concept.</span></span></li>
<li> <span data-ttu-id="929a4-487">Подключение настраиваемой программы.</span><span class="sxs-lookup"><span data-stu-id="929a4-487">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="929a4-488">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="929a4-488">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="929a4-489">Автоматическое расследование и исправление, включая Power Automate книги.</span><span class="sxs-lookup"><span data-stu-id="929a4-489">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="929a4-490">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="929a4-490">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
</ul>
</td>
<td><span data-ttu-id="929a4-491">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="929a4-491">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="929a4-492"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-492"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="929a4-493">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-493">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-494">Создание и публикация меток и политик хранения (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-494">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="929a4-495">Управление записями (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-495">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="929a4-496">Проверка создания плана файлов.</span><span class="sxs-lookup"><span data-stu-id="929a4-496">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="929a4-497">Создание и управление записями (включая записи на основе событий).</span><span class="sxs-lookup"><span data-stu-id="929a4-497">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="929a4-498">Просмотр диспозиции.</span><span class="sxs-lookup"><span data-stu-id="929a4-498">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="929a4-499">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-499">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="929a4-500">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-500">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="929a4-501">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="929a4-501">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="929a4-502">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="929a4-502">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="929a4-503">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-503">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="929a4-504">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="929a4-504">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="929a4-505">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="929a4-505">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="929a4-506">

  <strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-506">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="929a4-507">Разработка плана файлов управления записями.</span><span class="sxs-lookup"><span data-stu-id="929a4-507">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="929a4-508">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="929a4-508">Data connectors.</span></span></li>
<li> <span data-ttu-id="929a4-509">Разработка информационной архитектуры в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="929a4-509">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="929a4-510">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="929a4-510">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="929a4-511">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-511">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="929a4-512">Поддержка E3.</span><span class="sxs-lookup"><span data-stu-id="929a4-512">Support for E3.</span></span></li>
<li> <span data-ttu-id="929a4-513">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="929a4-513">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="929a4-514">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-514">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="929a4-515">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="929a4-515">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-516"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-516"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="929a4-517">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-517">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-518">Классификация данных (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-518">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-519">Типы конфиденциальной информации (поддерживаемые в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-519">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-520">Создание меток конфиденциальности (поддерживаемых в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-520">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-521">Применение меток чувствительности (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-521">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-522">Классификаторы, которые можно обучить (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-522">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-523">Знание данных с помощью обозревателя контента и проводника действий (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-523">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-524">Публикация меток с использованием политик (ручная и автоматическая) (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-524">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-525">Создание политик предотвращения потери данных конечной точки (DLP) для устройств Windows 10 (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="929a4-525">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="929a4-526">Создание политик DLP для чатов и каналов Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="929a4-526">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="929a4-527">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-527">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="929a4-528">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-528">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="929a4-529">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="929a4-529">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="929a4-530">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="929a4-530">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="929a4-531">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-531">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="929a4-532">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="929a4-532">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="929a4-533">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="929a4-533">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="929a4-534">

<strong> Защита информации Azure</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-534">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="929a4-535">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-535">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-536">Активация и настройка клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-536">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="929a4-537">Создание и настройка меток и политик (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="929a4-537">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="929a4-538">Применение защиты информации к документам (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="929a4-538">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="929a4-539">Автоматическое классификация и маркировка сведений в приложениях Office (например, Word, PowerPoint, Excel и Outlook), работающих в Windows и использующих клиент Azure Information Protection (поддерживается в P2).</span><span class="sxs-lookup"><span data-stu-id="929a4-539">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="929a4-540">Обнаружение и маркировка файлов в покое с помощью сканера защиты информации Azure (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="929a4-540">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="929a4-541">Отслеживание сообщений электронной почты в пути с помощью правил потока обработки почты Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-541">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="929a4-542">Мы также предоставляем рекомендации, если вы хотите применить защиту с помощью служб управления правами Microsoft Azure (Azure RMS), шифрования сообщений Office 365 (OME) и предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="929a4-542">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="929a4-543"><strong>Ниже приводится неосякаемая область </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-543"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="929a4-544">Ключ клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-544">Customer key.</span></span></li>
<li><span data-ttu-id="929a4-545">Настраиваемая разработка регулярных выражений (RegEx) для типов конфиденциальной информации.</span><span class="sxs-lookup"><span data-stu-id="929a4-545">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="929a4-546">Создание или изменение словарей ключевых слов.</span><span class="sxs-lookup"><span data-stu-id="929a4-546">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="929a4-547">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="929a4-547">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="929a4-548">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="929a4-548">Azure Purview.</span></span></li>
<li> <span data-ttu-id="929a4-549">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="929a4-549">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="929a4-550">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="929a4-550">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="929a4-551">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-551">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="929a4-552">Помимо основной <strong></strong> части в <a href="#general">целом,</a>минимальные требования к системе, за исключением Azure Information Protection, не существуют.</span><span class="sxs-lookup"><span data-stu-id="929a4-552">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="929a4-553"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-553"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="929a4-554">Обязанности, необходимые для клиента, включают:</span><span class="sxs-lookup"><span data-stu-id="929a4-554">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-555">Список местоположений для совместной работы с файлами, которые необходимо отсканировать.</span><span class="sxs-lookup"><span data-stu-id="929a4-555">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="929a4-556">Утвержденная таксономия классификации.</span><span class="sxs-lookup"><span data-stu-id="929a4-556">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="929a4-557">Понимание любых нормативных ограничений или требований в отношении управления ключами.</span><span class="sxs-lookup"><span data-stu-id="929a4-557">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="929a4-558">Учетная запись службы, созданная для локального Active Directory, синхронизированного с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-558">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="929a4-559">Метки, настроенные для классификации и защиты.</span><span class="sxs-lookup"><span data-stu-id="929a4-559">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="929a4-560">Все необходимые условия для сканера защиты информации Azure на месте.</span><span class="sxs-lookup"><span data-stu-id="929a4-560">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="929a4-561">Дополнительные сведения см. в дополнительных сведениях, необходимых для установки и развертывания сканера единой маркировки <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-561">For more information, see <a href="/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="929a4-562">Убедитесь, что на устройствах пользователей запущена поддерживаемая операционная система и установлены необходимые условия.</span><span class="sxs-lookup"><span data-stu-id="929a4-562">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="929a4-563">Дополнительные сведения см. в следующих сведениях.</span><span class="sxs-lookup"><span data-stu-id="929a4-563">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="929a4-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Руководство по администрированию: Установите клиент единой маркировки Azure Information Protection для пользователей</a>   </span><span class="sxs-lookup"><span data-stu-id="929a4-564"><a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="929a4-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">Что такое приложение Azure Information Protection для iOS или Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="929a4-565"><a href="/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="929a4-566">Установка и конфигурация соединителя Azure RMS и серверов, включая соединителя Active Directory RMS (AD RMS) для гибридной поддержки.</span><span class="sxs-lookup"><span data-stu-id="929a4-566">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="929a4-567">Настройка и конфигурация Bring Your Own Key (BYOK), Double Key Encryption (DKE) (только для клиента единой маркировки) или Hold Your Own Key (HYOK) (только для классического клиента) если вам потребуется один из этих вариантов развертывания.</span><span class="sxs-lookup"><span data-stu-id="929a4-567">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-568"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-568"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="929a4-569">Мы предоставляем удаленные рекомендации по готовности использовать Intune в качестве облачного поставщика управления мобильными устройствами (MDM) и поставщика управления мобильными приложениями (MAM) для ваших приложений и устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-569">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="929a4-570">Конкретные действия зависят от исходной среды и основаны на мобильном устройстве и требованиях к управлению мобильными приложениями.</span><span class="sxs-lookup"><span data-stu-id="929a4-570">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="929a4-571">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="929a4-571">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-572">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="929a4-572">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="929a4-573">Настройка удостоверений, которые будут использоваться Intune, используя локальное active Directory или облачные идентификаторы (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="929a4-573">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="929a4-574">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-574">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="929a4-575">Настройка полномочий MDM на основе потребностей управления, в том числе:</span><span class="sxs-lookup"><span data-stu-id="929a4-575">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-576">Настройка Intune в качестве центра MDM, когда Intune является единственным решением MDM.</span><span class="sxs-lookup"><span data-stu-id="929a4-576">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-577">Предоставление рекомендаций по MDM для следующих действий:</span><span class="sxs-lookup"><span data-stu-id="929a4-577">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-578">Настройка тестовых групп, используемых для проверки политик управления MDM.</span><span class="sxs-lookup"><span data-stu-id="929a4-578">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-579">Настройка политик управления MDM и таких служб, как:</span><span class="sxs-lookup"><span data-stu-id="929a4-579">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-580">Развертывание приложений для каждой поддерживаемой платформы с помощью веб-ссылок или глубоких ссылок.</span><span class="sxs-lookup"><span data-stu-id="929a4-580">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="929a4-581">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="929a4-581">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-582">Развертывание профилей электронной почты, беспроводных сетей и VPN, если у вас есть существующие полномочия сертификата, беспроводная сеть или инфраструктура VPN в организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-582">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="929a4-583">Подключение к складу данных Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-583">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="929a4-584">Интеграция Intune со следующими компонентами:</span><span class="sxs-lookup"><span data-stu-id="929a4-584">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-585">Просмотр группы для удаленной помощи (требуется подписка на просмотр группы).</span><span class="sxs-lookup"><span data-stu-id="929a4-585">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="929a4-586">Решения партнеров Mobile Threat Defense (MTD) (требуется подписка на MTD).</span><span class="sxs-lookup"><span data-stu-id="929a4-586">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="929a4-587">Решение по управлению расходами телекома (требуется подписка на решение по управлению расходами на телеком).</span><span class="sxs-lookup"><span data-stu-id="929a4-587">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="929a4-588">Регистрация устройств всех поддерживаемых платформ в Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-588">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="929a4-589">Предоставление рекомендаций по защите приложений по:</span><span class="sxs-lookup"><span data-stu-id="929a4-589">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-590">Настройка политик защиты приложений для каждой поддерживаемой платформы.</span><span class="sxs-lookup"><span data-stu-id="929a4-590">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="929a4-591">Настройка политик условного доступа для управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-591">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="929a4-592">Ориентация соответствующих групп пользователей с помощью ранее упомянутых политик MAM.</span><span class="sxs-lookup"><span data-stu-id="929a4-592">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-593">Использование отчетов об использовании управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-593">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-594">Предоставление руководства по миграции из устаревшего управления ПК в intune MDM.</span><span class="sxs-lookup"><span data-stu-id="929a4-594">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="929a4-595">
 
</li>
</ul>
  
<strong>Подключение к облаку</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-595">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="929a4-596">Мы повествуем о готовности к подключению к существующим средам Configuration Manager с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-596">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="929a4-597">Конкретные действия зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="929a4-597">The exact steps depend on your source environment.</span></span> <span data-ttu-id="929a4-598">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="929a4-598">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-599">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="929a4-599">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="929a4-600">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory и облачных удостоверений.</span><span class="sxs-lookup"><span data-stu-id="929a4-600">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="929a4-601">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-601">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="929a4-602">Предоставление рекомендаций по настройке гибридного присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="929a4-602">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="929a4-603">Предоставление рекомендаций по настройке автоматической регистрации Azure AD для автозарегистрации MDM.</span><span class="sxs-lookup"><span data-stu-id="929a4-603">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="929a4-604">Предоставление рекомендаций по настройкам шлюза управления облачными ресурсами при их совместном управлении удаленным управлением устройствами в Интернете.</span><span class="sxs-lookup"><span data-stu-id="929a4-604">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="929a4-605">Настройка поддерживаемых рабочих нагрузок, которые нужно перевести в Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-605">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="929a4-606">Установка клиента диспетчера конфигураций на устройствах, зарегистрированных в Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-606">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="929a4-607"><strong>Безопасно развертывание мобильных устройств Outlook для iOS и Android</strong> Мы можем предоставить рекомендации по безопасному развертыванию мобильных устройств Outlook для iOS и Android в организации, чтобы убедиться, что у пользователей установлены все необходимые приложения.</span><span class="sxs-lookup"><span data-stu-id="929a4-607"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="929a4-608">Действия по безопасному развертыванию мобильных устройств Outlook для iOS и Android с помощью Intune зависят от исходных сред.</span><span class="sxs-lookup"><span data-stu-id="929a4-608">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="929a4-609">Он может включать в себя:</span><span class="sxs-lookup"><span data-stu-id="929a4-609">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-610">Загрузка приложений Outlook для iOS и Android, Microsoft Authenticator и Портала компании Intune через Магазин приложений Apple или Магазин Google Play.</span><span class="sxs-lookup"><span data-stu-id="929a4-610">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="929a4-611">Предоставление рекомендаций по настройке:</span><span class="sxs-lookup"><span data-stu-id="929a4-611">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-612">Развертывание приложений Outlook для iOS и Android, Microsoft Authenticator и портала компании Intune с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-612">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="929a4-613">Политики защиты приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-613">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-614">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="929a4-614">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="929a4-615">Политики конфигурации приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-615">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="929a4-616">ИТ-администраторы должны иметь существующие инфраструктуры сертификатов, беспроводной сети и VPN, которые уже работают в рабочей среде при планировании развертывания профилей беспроводной сети и VPN с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-616">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="929a4-617"><strong>Примечание.</strong>Преимущество службы FastTrack не включает помощь в настройке или настройке органов сертификации, беспроводных сетей, инфраструктур VPN или push-сертификатов Apple MDM для Intune.</span><span class="sxs-lookup"><span data-stu-id="929a4-617"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="929a4-618"><strong>Примечание</strong>. Преимущество службы FastTrack не включает помощь по настройке или обновлению сервера сайта диспетчера конфигураций или клиента диспетчера конфигураций до минимальных требований, необходимых для поддержки подключения к облаку.</span><span class="sxs-lookup"><span data-stu-id="929a4-618"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="929a4-619">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="929a4-619">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="929a4-620"><strong>Intune, интегрированный с Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-620"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="929a4-621"><strong>Примечание.</strong>Мы предоставляем помощь в интеграции Intune с Microsoft Defender для конечной точки и создании политик соответствия требованиям устройств на основе оценки уровня риска Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-621"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="929a4-622">Мы не предоставляем помощь в приобретении, лицензировании или активации.</span><span class="sxs-lookup"><span data-stu-id="929a4-622">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="929a4-623">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="929a4-623">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="929a4-624"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-624"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="929a4-625">ИТ-администраторы отвечают за регистрацию устройств в организации путем отправки поставщиком оборудования идентификаторов оборудования от имени администраторов или с помощью самостоятельной их отправки в службу Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="929a4-625">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="929a4-626">Office 365</span><span class="sxs-lookup"><span data-stu-id="929a4-626">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-627"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-627"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-628"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-628"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-629"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-629"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="929a4-630"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-630"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="929a4-631">Для Exchange Online мы повеяем процесс, чтобы ваша организация была готова к использованию электронной почты.</span><span class="sxs-lookup"><span data-stu-id="929a4-631">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="929a4-632">Точные действия зависят от исходных сред и планов миграции электронной почты.</span><span class="sxs-lookup"><span data-stu-id="929a4-632">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="929a4-633">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-634">Настройка функций Exchange Online Protection (EOP) для всех доменов, поддерживающих почту и проверенных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-634">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-635">Указать записи обмена почтой (MX) в Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-635">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-636">Настройка функции Microsoft Defender для Office 365, если она является частью службы подписки.</span><span class="sxs-lookup"><span data-stu-id="929a4-636">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="929a4-637">Дополнительные сведения см. в <strong>этой таблице в microsoft Defender for Office 365.</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-637">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="929a4-p126">Настройка функции защиты от потери данных (DLP) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-p126">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="929a4-p127">Настройка шифрования сообщений Office 365 (OME) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-p127">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="929a4-642">
  <strong>Примечание:</strong> Служба репликации почтовых ящиков (MRS) пытается перенести электронные письма управляемых прав на информацию (IRM) из локального почтового ящика в соответствующий почтовый ящик Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-642">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="929a4-643">Возможность чтения защищенных данных после переноса зависит от сопоставления клиентом шаблонов службы Active Directory Rights Managed Services (AD RMS) и их копирования в службу Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="929a4-643">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-644">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="929a4-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="929a4-645">Настройка DNS, включая необходимые рамки политики автообнаружения, политик отправитель (SPF), DomainKeys Identified Mail (DKIM), проверку подлинности сообщений на основе домена, отчетность и соответствие (DMARC) и записи MX (по мере необходимости).</span><span class="sxs-lookup"><span data-stu-id="929a4-645">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="929a4-646">Настройка потока обработки почты между исходной средой обмена сообщениями и Exchange Online (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="929a4-646">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="929a4-647">Перенос почты из исходной среды обмена сообщениями в Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-647">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-648">Настройка почтовых клиентов (Outlook для Windows, Outlook в Интернете, Outlook для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="929a4-648">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="929a4-649">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="929a4-649">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="929a4-650">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-650">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="929a4-651">В исходных средах должен быть один из следующих минимальных уровней:</span><span class="sxs-lookup"><span data-stu-id="929a4-651">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-652">Одна или несколько организаций Exchange с Exchange Server 2003 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="929a4-652">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="929a4-653">Одна почтовая среда, поддерживающая протокол IMAP.</span><span class="sxs-lookup"><span data-stu-id="929a4-653">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="929a4-654">Одна среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="929a4-654">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="929a4-655">Сведения о возможностях multi-Geo см. в <a href="https://go.microsoft.com/fwlink/?linkid=872776">сайте Multi-Geo Capabilities in Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-655">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="929a4-656">Клиентские программы в Интернете, такие как Project for Office 365, Outlook for Windows, Outlook для iOS и Android, клиент синхронизации OneDrive для бизнеса, Power BI Desktop и Skype для бизнеса должны быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-656">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="929a4-657"><strong>Microsoft Defender для Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-657"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="929a4-658">Дополнительные сведения см. <strong>в веб-сайте Microsoft Defender для Office 365</strong> в <a href="/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-658">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="929a4-659"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-659"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="929a4-660">Дополнительные сведения см. в <strong>сайте Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-660">For more information, see <strong> Microsoft Information Governance</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-661"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-661"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="929a4-662">Дополнительные сведения см. <strong>в веб-сайте Microsoft Information Protection</strong> in Security and <a href="/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-662">For more information, see <strong>Microsoft Information Protection </strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-663"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-663"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="929a4-664">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-665">Подтверждение минимальных требований в Exchange Online, SharePoint Online, Office 365 Groups и Azure AD для поддержки Teams.</span><span class="sxs-lookup"><span data-stu-id="929a4-665">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="929a4-666">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="929a4-666">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="929a4-667">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="929a4-667">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="929a4-668">Подтверждение того, что рабочее пространство Teams включено в клиенте Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-668">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="929a4-669">Включение или отключение пользовательских лицензий.</span><span class="sxs-lookup"><span data-stu-id="929a4-669">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="929a4-670">Оценка сети для Teams:</span><span class="sxs-lookup"><span data-stu-id="929a4-670">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-671">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="929a4-671">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="929a4-672">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="929a4-672">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="929a4-673">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="929a4-673">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="929a4-674">Настройка политики приложений Teams (веб-приложение Teams, приложение Teams Desktop и Teams для приложений для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="929a4-674">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="929a4-675">Если применимо, мы также предоставляем рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-675">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-676">Устройства комнат Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="929a4-676">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="929a4-677">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств телефонной и конференц-связи. Устройства перечислены в <a href="https://go.microsoft.com/fwlink/?linkid=2066478">каталоге устройств Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-677">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="929a4-678">Удаленная помощь с конфигурацией на стороне служб сертифицированных устройств Microsoft Teams Rooms.</span><span class="sxs-lookup"><span data-stu-id="929a4-678">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="929a4-679">Включение Аудиоконференций:</span><span class="sxs-lookup"><span data-stu-id="929a4-679">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="929a4-680">Настройка организации с использованием параметров по умолчанию для схемы конференции.</span><span class="sxs-lookup"><span data-stu-id="929a4-680">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="929a4-681">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="929a4-681">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="929a4-682">Телефонная система:</span><span class="sxs-lookup"><span data-stu-id="929a4-682">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-683">Настройка облачных голосовых функций для организации.</span><span class="sxs-lookup"><span data-stu-id="929a4-683">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="929a4-684">Руководство по планам вызова<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(доступные рынки):</a></span><span class="sxs-lookup"><span data-stu-id="929a4-684">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="929a4-685">Назначение номеров лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="929a4-685">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="929a4-686">Рекомендации по портированию локальных номеров до 999 в пользовательском интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="929a4-686">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="929a4-687">Поддержка запросов на обслуживание для портирования локальных номеров выше 999.</span><span class="sxs-lookup"><span data-stu-id="929a4-687">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="929a4-688">Руководство по прямой маршрутике:</span><span class="sxs-lookup"><span data-stu-id="929a4-688">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-689">Руководство по настройке организации для разработки сценариев с размещением партнеров или сценариев, развернутых клиентами, для 10 сайтов.</span><span class="sxs-lookup"><span data-stu-id="929a4-689">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="929a4-690">Обзор конфигурации пограничного контроллера сеанса (SBC).</span><span class="sxs-lookup"><span data-stu-id="929a4-690">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="929a4-691">Удаленная помощь с конфигурацией плана набора номеров.</span><span class="sxs-lookup"><span data-stu-id="929a4-691">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="929a4-692">Конфигурация голосового маршрута.</span><span class="sxs-lookup"><span data-stu-id="929a4-692">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="929a4-693">Обход мультимедиа и оптимизация локальных средств массовой информации.</span><span class="sxs-lookup"><span data-stu-id="929a4-693">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="929a4-694">Включение прямых трансляций Teams.</span><span class="sxs-lookup"><span data-stu-id="929a4-694">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="929a4-695">Настройка организации и интеграция в Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="929a4-695">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="929a4-696">Руководство по переходу Skype для бизнеса на teams.</span><span class="sxs-lookup"><span data-stu-id="929a4-696">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="929a4-697">Удостоверения, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-697">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-698">Пользователи, для которых включен SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-698">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="929a4-699">Почтовые ящики Exchange присутствуют (онлайн и локально в гибридной конфигурации Exchange).</span><span class="sxs-lookup"><span data-stu-id="929a4-699">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="929a4-700">Включено для групп Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-700">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="929a4-701">
  <strong>Примечание:</strong> Если пользователям не назначены и не включены лицензии SharePoint Online, у них не будет хранилища OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-701">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="929a4-702">Общий доступ к файлам продолжает работать в Channels, но пользователи не могут обмениваться файлами в чатах без хранения OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-702">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="929a4-703">Команды не поддерживают локальное участие в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="929a4-703">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="929a4-704">
  <strong>Примечание:</strong> Идеальное состояние для всех пользователей, чтобы их почтовые ящики были дома в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-704">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="929a4-705">Пользователи с почтовыми ящиками, в которые есть локальное помещение, должны синхронизировать свои удостоверения с каталогом Office 365 через Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="929a4-705">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="929a4-706">Для этих гибридных клиентов Exchange, если почтовый ящик пользователя является локальной, пользователь не может добавлять или настраивать соединители.</span><span class="sxs-lookup"><span data-stu-id="929a4-706">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="929a4-707">Установщики клиентов Microsoft Teams для настольных компьютеров Windows и Mac можно скачать на странице <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-707">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="929a4-708"><strong>Outlook для iOS и Android</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-708"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="929a4-709">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-709">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-710">Скачивание Outlook для iOS и Android через Apple App Store или Google Play.</span><span class="sxs-lookup"><span data-stu-id="929a4-710">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="929a4-711">Настройка учетных записей и оценка почтового ящика Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-711">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="929a4-712">Защита Outlook мобильных устройств (дополнительные сведения см. в Outlook для iOS и <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Android Exchange Online).</a></span><span class="sxs-lookup"><span data-stu-id="929a4-712">Securing Outlook mobile (see <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="929a4-713">Идентификаторы, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-713">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-714">Выполнена настройка Exchange Online, назначены соответствующие лицензии.</span><span class="sxs-lookup"><span data-stu-id="929a4-714">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-715"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-715"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="929a4-716">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-716">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-717">Назначение лицензий на Power BI.</span><span class="sxs-lookup"><span data-stu-id="929a4-717">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="929a4-718">Развертывание приложения Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="929a4-718">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="929a4-719">Программное обеспечение клиента в Power BI Desktop должно быть на минимальном уровне, как это определено в требованиях системы для Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">и Office</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-719">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-720"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-720"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="929a4-721">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-721">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-722">Проверка основных функций SharePoint, необходимых для работы Project Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-722">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="929a4-723">Добавление службы Project Online в клиент (в том числе добавление подписок для пользователей).</span><span class="sxs-lookup"><span data-stu-id="929a4-723">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="929a4-724">Настройка пула корпоративных ресурсов (ERP).</span><span class="sxs-lookup"><span data-stu-id="929a4-724">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="929a4-725">Создание первого проекта.</span><span class="sxs-lookup"><span data-stu-id="929a4-725">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="929a4-726">Программное обеспечение клиента в Project для Office 365 должно быть на минимальном уровне, определенном в требованиях системы для Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">и Office.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-726">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="929a4-727"><strong>Project Online профессиональный и Premium</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-727"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="929a4-728">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-728">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-729">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="929a4-729">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="929a4-730">Назначение пользователям лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="929a4-730">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="929a4-731">Установка клиента Project Online для настольных ПК с использованием портала Office 365 и технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="929a4-731">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="929a4-732">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-732">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="929a4-733">Настройка одного внутреннего сервера распространения для клиента Project Online для настольных ПК, в том числе помощь по созданию файла configuration.xml для его последующего использования в средстве развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-733">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="929a4-734">Подключение клиента Project Online для настольных ПК к Project Online профессиональный или Project Online расширенный.</span><span class="sxs-lookup"><span data-stu-id="929a4-734">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="929a4-735">Программное обеспечение клиента в Project для Office 365 должно быть на минимальном уровне, определенном в требованиях системы для Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">и Office.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-735">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-736"><strong>SharePoint Online и OneDrive для бизнеса</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-736"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="929a4-737">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-737">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-738">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="929a4-738">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="929a4-739">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="929a4-739">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="929a4-740">Подготовка пользователей и лицензий.</span><span class="sxs-lookup"><span data-stu-id="929a4-740">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="929a4-741">Создание сайтов для администратора SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-741">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="929a4-742">Планирование семейств веб-сайтов.</span><span class="sxs-lookup"><span data-stu-id="929a4-742">Planning site collections.</span></span></li>
<li><span data-ttu-id="929a4-743">Защита контента и управление разрешениями.</span><span class="sxs-lookup"><span data-stu-id="929a4-743">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="929a4-744">Настройка функций SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-744">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="929a4-745">Настройка функций гибридной среды SharePoint, таких как гибридный поиск, гибридные сайты, гибридная таксономия, типы контента, гибридная функция самостоятельного создания сайтов (только для SharePoint Server 2013), расширенное средство запуска приложений, гибридная служба OneDrive для бизнеса и сайты экстрасети.</span><span class="sxs-lookup"><span data-stu-id="929a4-745">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="929a4-746">Подход к миграции.</span><span class="sxs-lookup"><span data-stu-id="929a4-746">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="929a4-747">Дополнительные рекомендации предоставляются для OneDrive для бизнеса в зависимости от SharePoint версии, например:</span><span class="sxs-lookup"><span data-stu-id="929a4-747">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-748">Определение параметров интеграции и проверка локальной и сетевой инфраструктуры и пропускной способности сети.</span><span class="sxs-lookup"><span data-stu-id="929a4-748">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="929a4-749">Установка SharePoint 2013 SP1 (если применимо), планирование и реализация требований синхронизации и удостоверений, а также определение OneDrive для бизнеса синхронизации клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-749">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="929a4-750">Планирование и реализация единого внедрения для всех пользователей (или поэтапного внедрения).</span><span class="sxs-lookup"><span data-stu-id="929a4-750">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="929a4-751">Назначение лицензий, перенаправление моих сайтов и библиотек личных документов в Office 365 (применимо к SharePoint Online 2013), настройка аудиторий для управления доступом к OneDrive (применимо к SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="929a4-751">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="929a4-752">Перенаправление или перемещение известных папок в OneDrive.</span><span class="sxs-lookup"><span data-stu-id="929a4-752">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="929a4-753">Развертывание синхронизации OneDrive для бизнеса клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-753">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="929a4-754">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="929a4-754">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="929a4-755">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-755">For information on using the FastTrack benefit for data migration to Office 365, see <a href="/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="929a4-756"><strong>Для SharePoint гибрида:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-756"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="929a4-757">SharePoint гибридная конфигурация включает настройку гибридного поиска, сайтов, таксономии, типов контента, OneDrive для бизнеса, расширенной пусковой системы приложений, сайтов экстрасетей и создания сайтов самообслуживаемых, подключенных из локальной среды SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="929a4-757">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="929a4-758">
  <strong>Примечание:</strong> Создание сайтов самообслуживки не имеет возможности для локального сервера, запущенного SharePoint 2013 г.</span><span class="sxs-lookup"><span data-stu-id="929a4-758">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="929a4-759">Чтобы включить SharePoint гибрид, необходимо иметь одну из следующих сред SharePoint Server: 2013, 2016 или 2019.</span><span class="sxs-lookup"><span data-stu-id="929a4-759">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="929a4-760">
  <strong>Примечание:</strong> Обновление локальной среды SharePoint до SharePoint Server не является областью действия.</span><span class="sxs-lookup"><span data-stu-id="929a4-760">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="929a4-761">Обратитесь за <a href="https://go.microsoft.com/fwlink/?linkid=2080150">помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="929a4-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="929a4-762">Дополнительные сведения см. в сведениях о минимальных уровнях общедоступных обновлений <a href="https://go.microsoft.com/fwlink/?linkid=853548">для SharePoint гибридных функций.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="929a4-762">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="929a4-763">
  <strong>Примечание:</strong> Сведения о возможностях multi-Geo см. в OneDrive и <a href="https://go.microsoft.com/fwlink/?linkid=831056">SharePoint Online в Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="929a4-763">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-764"><strong>Yammer корпоративный</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-764"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="929a4-765">Мы предоставляем удаленные указания для включения Yammer корпоративный службы.</span><span class="sxs-lookup"><span data-stu-id="929a4-765">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="929a4-766">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, определенном в требованиях системы для Microsoft 365 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">и Office.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-766">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="929a4-767">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="929a4-767">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-768"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-768"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-769"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-769"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-770"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-770"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="929a4-771"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-771"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="929a4-772">Дополнительные сведения см. <strong>в Azure Active Directory Azure AD</strong> и Azure AD Premium в области безопасности <a href="/fasttrack/products-and-capabilities#security-and-compliance">и соответствия требованиям.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-772">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd"><span data-ttu-id="929a4-773">#обеспечение безопасности и соответствия требованиям</span><span class="sxs-lookup"><span data-stu-id="929a4-773">#security-and-compliance</span></span>
<td><span data-ttu-id="929a4-774"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="929a4-774"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="929a4-775">Дополнительные сведения о azure Information Protection <strong>см.</strong> в Microsoft Information Protection <a href="/fasttrack/products-and-capabilities#security-and-compliance">в области безопасности и соответствия требованиям.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-775">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="929a4-776"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-776"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="929a4-777">Дополнительные сведения см. <strong>в Microsoft Intune</strong> в области безопасности <a href="/fasttrack/products-and-capabilities#security-and-compliance">и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-777">For more information, see <strong> Microsoft Intune</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="929a4-778">Windows 10</span><span class="sxs-lookup"><span data-stu-id="929a4-778">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-779"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-779"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-780"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-780"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-781"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-781"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="929a4-782"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-782"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="929a4-783">Мы предоставляем рекомендации по обновлению с Windows 7 Профессиональная и Windows 8.1 Professional до Windows 10 Корпоративная.</span><span class="sxs-lookup"><span data-stu-id="929a4-783">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="929a4-784">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-784">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-785">Понимание Windows 10 намерения.</span><span class="sxs-lookup"><span data-stu-id="929a4-785">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="929a4-786">Оценка исходных сред и требований (убедитесь, что Microsoft Endpoint Configuration Manager будет повышена до необходимого уровня для поддержки Windows 10 развертывания).</span><span class="sxs-lookup"><span data-stu-id="929a4-786">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="929a4-787">Развертывание Windows 10 Корпоративная и Приложения Microsoft 365 с Microsoft Endpoint Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-787">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="929a4-788">Рекомендации по оценке Windows 10 приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-788">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="929a4-789">Включение использования desktop Analytics и руководства путем создания плана развертывания Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="929a4-789">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="929a4-790">Приложения Microsoft 365 оценку совместимости с помощью панели мониторинга Office 365 готовности в Configuration Manager или с автономным набор средств для Office плюс развертывание Приложения Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-790">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="929a4-791">Создание контрольного списка исправлений для того, что необходимо сделать, чтобы привести исходные среды к минимальным требованиям для успешного развертывания.</span><span class="sxs-lookup"><span data-stu-id="929a4-791">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="929a4-792">Предоставление рекомендаций по обновлению для существующих устройств Windows 10 Корпоративная, если они соответствуют необходимым требованиям к оборудованию устройств.</span><span class="sxs-lookup"><span data-stu-id="929a4-792">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="929a4-793">Предоставление рекомендаций по обновлению для поддержки существующего развертывания.</span><span class="sxs-lookup"><span data-stu-id="929a4-793">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="929a4-794">FastTrack предоставляет рекомендации и инструкции по обновлению до Windows 10 на месте.</span><span class="sxs-lookup"><span data-stu-id="929a4-794">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="929a4-795">Кроме того, предоставляются инструкции по установке чистых образов Windows и для сценариев развертывания Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="929a4-795">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="929a4-796">Развертывание Приложения Microsoft 365 с помощью диспетчера конфигурации в Windows 10 развертывания.</span><span class="sxs-lookup"><span data-stu-id="929a4-796">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="929a4-797">Предоставление рекомендаций, которые помогут организации оставаться в курсе Windows 10 Корпоративная и Приложения Microsoft 365 с помощью существующей среды Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-797">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="929a4-798">
  
<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-798">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="929a4-799">Обновление Configuration Manager до Current Branch.</span><span class="sxs-lookup"><span data-stu-id="929a4-799">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="929a4-800">Создание настраиваемых образов для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-800">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="929a4-801">Создание и поддержка сценариев для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-801">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="929a4-802">Переход с BIOS на UEFI в системах с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-802">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="929a4-803">Включение функций безопасности Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-803">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="929a4-804">Настройка служб развертывания Windows (WDS) для загрузки с помощью протокола удаленной загрузки (PXE).</span><span class="sxs-lookup"><span data-stu-id="929a4-804">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="929a4-805">Запись и развертывание образов Windows 10 с помощью набора средств Microsoft Deployment Toolkit (MDT).</span><span class="sxs-lookup"><span data-stu-id="929a4-805">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="929a4-806">Использование средства миграции пользовательской среды (USMT).</span><span class="sxs-lookup"><span data-stu-id="929a4-806">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="929a4-807">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="929a4-807">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="929a4-808">Для обновления ПК должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="929a4-808">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-809">Ос-код источника: Windows 7 Корпоративная или Professional, Windows 8.1 Корпоративная или Professional.</span><span class="sxs-lookup"><span data-stu-id="929a4-809">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="929a4-810">Устройства: рабочий стол, записная книжка или форм-фактор планшета.</span><span class="sxs-lookup"><span data-stu-id="929a4-810">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="929a4-811">Целевая ОС: окно 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="929a4-811">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="929a4-812">Для обновления инфраструктуры должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="929a4-812">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-813">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="929a4-813">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="929a4-814">Версия Configuration Manager должна поддерживаться целевой Windows 10.</span><span class="sxs-lookup"><span data-stu-id="929a4-814">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="929a4-815">Дополнительные сведения см. в таблице поддержки Configuration Manager в статье <a href="/sccm/core/plan-design/configs/support-for-windows-10">Поддержка Windows 10 в Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-815">For more information, see the Configuration Manager support table at <a href="/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="929a4-816"><strong>Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-816"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="929a4-817">Дополнительные сведения см. в <strong> веб-сайте Microsoft Defender для конечной точки</strong> в <a href="/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="929a4-817">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="929a4-818">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="929a4-818">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-819"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-819"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-820"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-820"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-821"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-821"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="929a4-822"><strong>Виртуальный рабочий стол Windows</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-822"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="929a4-823">Мы предоставляем рекомендации по развертыванию для onboarding Windows Virtual Desktop (служба виртуализации настольных компьютеров и приложений).</span><span class="sxs-lookup"><span data-stu-id="929a4-823">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="929a4-824">Windows Виртуальный настольный компьютер Windows 10 много сеансов и оптимизирован для Приложения Microsoft 365 для Enterprise с интегрированной безопасностью и управлением для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-824">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="929a4-825">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="929a4-825">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="929a4-826">Развертывание Windows 10 Корпоративная сеансов и Приложения Microsoft 365 для Enterprise с помощью следующих ниже.</span><span class="sxs-lookup"><span data-stu-id="929a4-826">Deploying Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="929a4-827">Azure Marketplace Image.</span><span class="sxs-lookup"><span data-stu-id="929a4-827">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="929a4-828">Общий образ.</span><span class="sxs-lookup"><span data-stu-id="929a4-828">Shared image.</span></span></li>
<li><span data-ttu-id="929a4-829">Office Развертывание набор средств (ODT).</span><span class="sxs-lookup"><span data-stu-id="929a4-829">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="929a4-830">Настройка Приложения Microsoft 365 для FSLogix в родной Windows виртуальный рабочий стол.</span><span class="sxs-lookup"><span data-stu-id="929a4-830">Configuring Microsoft 365 Apps for FSLogix in a native Windows Virtual Desktop.</span></span> <span data-ttu-id="929a4-831">Для FSLogix:</span><span class="sxs-lookup"><span data-stu-id="929a4-831">For FSLogix:</span></span>
<ul>
<li><span data-ttu-id="929a4-832">Развертывание агента.</span><span class="sxs-lookup"><span data-stu-id="929a4-832">Deploying the Agent.</span></span></li>
<li><span data-ttu-id="929a4-833">Настройка профилей и Office контейнеров.</span><span class="sxs-lookup"><span data-stu-id="929a4-833">Configuring Profile and Office containers.</span></span></li>
<li><span data-ttu-id="929a4-834">Настройка исключений контента и перенаправлений папок для Приложения Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-834">Configuring content exclusions and folder redirections for Microsoft 365 Apps.</span></span></li>
</ul></li>
<li><span data-ttu-id="929a4-835">Развертывание Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="929a4-835">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="929a4-836">Развертывание Microsoft Teams с оптимизацией.</span><span class="sxs-lookup"><span data-stu-id="929a4-836">Deploying Microsoft Teams with optimization.</span></span></li>
</ul><span data-ttu-id="929a4-837">

<strong>Ниже приводится неосякаемая область</strong>
</span><span class="sxs-lookup"><span data-stu-id="929a4-837">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="929a4-838">Project управления развертыванием Windows виртуальной настольной инфраструктуры клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-838">Project management of the customer's Windows Virtual Desktop infrastructure deployment.</span></span></li>
<li><span data-ttu-id="929a4-839">Виртуализация и развертывание сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-839">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="929a4-840">Создание пользовательских изображений для Windows desktop.</span><span class="sxs-lookup"><span data-stu-id="929a4-840">Creation of custom images for Windows Virtual Desktop.</span></span></li>
<li><span data-ttu-id="929a4-841">Миграции и сценарии с участием VMware и Citrix.</span><span class="sxs-lookup"><span data-stu-id="929a4-841">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="929a4-842">Сценарии Linux.</span><span class="sxs-lookup"><span data-stu-id="929a4-842">Linux scenarios.</span></span></li>
<li><span data-ttu-id="929a4-843">Преобразование или миграция профилей пользователей.</span><span class="sxs-lookup"><span data-stu-id="929a4-843">Conversion or migrations of user profiles.</span></span></li>
<li><span data-ttu-id="929a4-844">Microsoft Endpoint Configuration Manager и Microsoft Endpoint Manager для виртуального рабочего стола Windows (включая исправление и управление).</span><span class="sxs-lookup"><span data-stu-id="929a4-844">Microsoft Endpoint Configuration Manager and Microsoft Endpoint Manager configuration for Windows Virtual Desktop (including patching and management).</span></span> </li>
<li><span data-ttu-id="929a4-845">Microsoft 365 Defender с Windows 10 нескольких сеансов.</span><span class="sxs-lookup"><span data-stu-id="929a4-845">Microsoft 365 Defender with Windows 10 multi-session.</span></span></li>
</ul>
<span data-ttu-id="929a4-846">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="929a4-846">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="929a4-847">У вас уже должно быть следующее:</span><span class="sxs-lookup"><span data-stu-id="929a4-847">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="929a4-848">Windows требования к лицензированию виртуальных <a href="/azure/virtual-desktop/overview#requirements">настольных компьютеров.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-848"><a href="/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li> <span data-ttu-id="929a4-849">Необходимая <a href="/azure/virtual-desktop/overview">инфраструктура для поддержки Windows deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-849">The <a href="/azure/virtual-desktop/overview"> required infrastructure to support Windows Virtual Deskstop</a>.</span></span> </li>
<ul>
<li><span data-ttu-id="929a4-850"><a href="/azure/virtual-desktop/store-fslogix-profile">служба хранилища для контейнеров профилей FSLogix в Windows Deskstop</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-850"><a href="/azure/virtual-desktop/store-fslogix-profile"> Storage for FSLogix profile containers in Windows Virtual Deskstop</a>.</span></span> </li>
</ul>
<li><span data-ttu-id="929a4-851">Сеть Azure:</span><span class="sxs-lookup"><span data-stu-id="929a4-851">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="929a4-852">Создание и подсети виртуальной сети (VNET).</span><span class="sxs-lookup"><span data-stu-id="929a4-852">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="929a4-853">Брандмауэр и группы сетевой безопасности.</span><span class="sxs-lookup"><span data-stu-id="929a4-853">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="929a4-854">VPN и ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="929a4-854">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="929a4-855">Маршрутная маршрутивка в Azure из локального помещения.</span><span class="sxs-lookup"><span data-stu-id="929a4-855">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="929a4-856">Правила брандмауэра, позволяющие подключаться к Windows рабочего стола.</span><span class="sxs-lookup"><span data-stu-id="929a4-856">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="929a4-857">Дополнительные сведения см. в <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">веб-версии Поддерживаемые клиенты удаленного рабочего стола.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-857">For more information, see <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="929a4-858">Общая настройка Azure AD:</span><span class="sxs-lookup"><span data-stu-id="929a4-858">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="929a4-859">Стратегия <i>удостоверения (можно использовать только один из следующих трех вариантов):</i>
</span><span class="sxs-lookup"><span data-stu-id="929a4-859">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="929a4-860">Active Directory с azure AD Подключение Azure.</span><span class="sxs-lookup"><span data-stu-id="929a4-860">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="929a4-861">Active Directory с Azure AD Подключение локально через VPN или ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="929a4-861">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="929a4-862">Службы домена Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="929a4-862">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="929a4-863">App Assure</span><span class="sxs-lookup"><span data-stu-id="929a4-863">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-864"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-864"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-865"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-865"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-866"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-866"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="929a4-867"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-867"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="929a4-868">App Assure — это служба, предназначенная для решения проблем с Windows 10 и Приложения Microsoft 365 совместимостью приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-868">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="929a4-869">При запросе службы App Assure мы работаем с вами для решения проблем с допустимым приложением без каких-либо дополнительных затрат для вас с помощью доступной подписки.</span><span class="sxs-lookup"><span data-stu-id="929a4-869">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="929a4-870">Мы также предоставляем рекомендации для клиентов, сталкивающихся с вопросами совместимости при развертывании Windows и Microsoft Edge и прилоя все разумные усилия для решения проблем совместимости.</span><span class="sxs-lookup"><span data-stu-id="929a4-870">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="929a4-871">Мы предоставляем помощь в исправлении приложений, развернутых в следующих продуктах Майкрософт:</span><span class="sxs-lookup"><span data-stu-id="929a4-871">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="929a4-872"><strong>Windows 10</strong> (включая устройства ARM64)</span><span class="sxs-lookup"><span data-stu-id="929a4-872"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="929a4-873"><strong>Приложения Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="929a4-873"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="929a4-874"><strong>Microsoft Edge -</strong> Руководство по развертыванию см. в <a href="/DeployEdge/microsoft-edge-channels">обзоре Microsoft Edge каналов.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-874"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="929a4-875"><strong>Windows виртуальный рабочий стол</strong> - Дополнительные сведения см. в <a href="/azure/virtual-desktop/overview">Windows виртуальный</a> рабочий стол? и <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Корпоративная много сеансов.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-875"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="929a4-876">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-876">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="929a4-p137">Изучение и тестирование приложения с целью определения того, какие функции поддерживаются и не поддерживаются в Windows 10 и приложениях Microsoft 365. Дополнительные руководства по этому процессу см. на странице <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Центр развертывания компьютеров</a>. Если вас интересует глубокая оценка готовности к обновлению, заполните форму <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Запрос клиента на оценку современных компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-p137">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="929a4-880">Анализ приложений независимых поставщиков программного обеспечения (ISV) на совместимость с Windows 10 и сведений о поддержке.</span><span class="sxs-lookup"><span data-stu-id="929a4-880">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="929a4-881">Дополнительные сведения см. в разделе <a href="/sccm/desktop-analytics/overview">Аналитика компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="929a4-881">For more information, see <a href="/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="929a4-882">Услуги по упаковке приложений.</span><span class="sxs-lookup"><span data-stu-id="929a4-882">App packaging-only services.</span></span> <span data-ttu-id="929a4-883">Команда App Assure упаковывает приложения, исправленные для Windows 10, чтобы обеспечить возможность их развертывания в среде клиента.</span><span class="sxs-lookup"><span data-stu-id="929a4-883">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="929a4-884">

<strong>Обязанности клиента включают в себя</strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-884">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="929a4-885">Создание ведомости приложения</span><span class="sxs-lookup"><span data-stu-id="929a4-885">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="929a4-886">Проверки работы данных приложений в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-886">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="929a4-887">
<strong>Примечание:</strong>  Корпорация Майкрософт не может вносить изменения в исходный код.</span><span class="sxs-lookup"><span data-stu-id="929a4-887">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="929a4-888">Однако команда App Assure предоставляет руководство для разработчиков приложений, если для приложений доступен исходный код.</span><span class="sxs-lookup"><span data-stu-id="929a4-888">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="929a4-889">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="929a4-889">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="929a4-890"><strong>Windows 10 и Приложения Microsoft 365</strong>
</span><span class="sxs-lookup"><span data-stu-id="929a4-890"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-891">Приложения, работающие в Windows 7, Windows 8,1, Office 2010 и Office 2013, также работают в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="929a4-891">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="929a4-892">
<strong>Windows 10 на ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="929a4-892">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="929a4-893">Приложения, которые работали Windows 7, Office 2010 или более поздних версиях, также работают Windows 10 и Приложения Microsoft 365 на устройствах ARM64.</span><span class="sxs-lookup"><span data-stu-id="929a4-893">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="929a4-894">
  <strong>Примечание:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="929a4-894">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="929a4-895">Эмуляция x64 (64-bit) доступна в предварительном режиме для клиентов, участвующих <a href="https://insider.windows.com/">в программе Windows insider.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-895">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="929a4-896">Для не Windows пользователей insider на Windows 10 версии 2004 (или более поздней версии), PHOTOSHOP ARM64 поддерживается с помощью <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">пакета совместимости OpenCL</a>и OpenGL .</span><span class="sxs-lookup"><span data-stu-id="929a4-896">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="929a4-897">Пользователи программы Windows могут скачать внутреннюю версию пакета совместимости OpenCL и OpenGL для использования с дополнительными приложениями.</span><span class="sxs-lookup"><span data-stu-id="929a4-897">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="929a4-898">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="929a4-898">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-899">Если веб-приложения или сайты работают в Internet Explorer 11, поддерживаемых версиях Google Chrome или любой версии Microsoft Edge, они также будут работать с Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="929a4-899">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-900">Так как <a href="/microsoft-edge/web-platform/site-impacting-changes">веб-сайт</a>постоянно развивается, обязательно просмотрите опубликованный список известных изменений совместимости сайтов для Microsoft Edge .</span><span class="sxs-lookup"><span data-stu-id="929a4-900">As the web is constantly evolving, be sure to review this published list of known <a href="/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="929a4-901">
  <strong>Windows Виртуальный рабочий стол</strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-901">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="929a4-902">Виртуализованные приложения, работающие на узле сеансов удаленных рабочих столов в Windows Server, также работают в Windows 10 Корпоративная с поддержкой нескольких сеансов в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="929a4-902">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-903">Приложения, работающие Windows 7 или Windows 10 среде виртуальной инфраструктуры настольных компьютеров (VDI), также работают на Windows 7 Корпоративная и Windows 10 Корпоративная в Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="929a4-903">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-904">Приложения, работающие на клиентских устройствах Windows 7 или Windows 10, также работают в Windows 7 Корпоративная и Windows 10 Корпоративная в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="929a4-904">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="929a4-905">
  <strong>Примечание.</strong> Windows 10 Корпоративная много сеансов исключений и ограничений совместимости с несколькими сеансами:</span><span class="sxs-lookup"><span data-stu-id="929a4-905">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="929a4-906">Ограниченное перенаправление оборудования.</span><span class="sxs-lookup"><span data-stu-id="929a4-906">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-907">Приложения с интенсивным использованием A/V могут работать с уменьшенной производительностью.</span><span class="sxs-lookup"><span data-stu-id="929a4-907">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="929a4-908">16-разрядные приложения не поддерживаются в 64-разрядных виртуальных рабочих столах Windows.</span><span class="sxs-lookup"><span data-stu-id="929a4-908">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="929a4-909">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="929a4-909">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="929a4-910"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-910"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="929a4-911"><strong>FastTrack руководства</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-911"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="929a4-912"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="929a4-912"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="929a4-913"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="929a4-913"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="929a4-914">Мы предоставляем рекомендации по удаленному развертыванию и принятию и совместимости для:</span><span class="sxs-lookup"><span data-stu-id="929a4-914">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="929a4-915">Развертывание Microsoft Edge на Windows 10 с Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager или Intune).</span><span class="sxs-lookup"><span data-stu-id="929a4-915">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="929a4-916">Настройка Microsoft Edge (с помощью групповых политик или конфигурации приложений и политик приложений Intune).</span><span class="sxs-lookup"><span data-stu-id="929a4-916">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="929a4-917">Инвентаризация списка сайтов, которые могут потребовать использования в режиме Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="929a4-917">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="929a4-918">Включение режима Internet Explorer с существующим списком Enterprise сайта.</span><span class="sxs-lookup"><span data-stu-id="929a4-918">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="929a4-919">Дополнительные сведения см. в <a href="/fasttrack/process-and-expectations#engaging-fasttrack">FastTrack.</a></span><span class="sxs-lookup"><span data-stu-id="929a4-919">(For more information, see <a href="/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>.</span></span> <span data-ttu-id="929a4-920">Кроме того, если у вас есть веб-приложение или сайт, который работает с Internet Explorer или Google Chrome и вы испытываете проблемы с совместимостью, мы предоставляем рекомендации по устранению проблемы без дополнительных затрат.</span><span class="sxs-lookup"><span data-stu-id="929a4-920">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="929a4-921">Чтобы запросить поддержку совместимости для App Assure, вопишитесь на <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack,</a> чтобы начать взаимодействие.</span><span class="sxs-lookup"><span data-stu-id="929a4-921">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="929a4-922">Руководство по планированию принятия и конфигурации edge для Поиск (Майкрософт) закладки.</span><span class="sxs-lookup"><span data-stu-id="929a4-922">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="929a4-923">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="929a4-923">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="929a4-924">Управление проектами по развертыванию Microsoft Edge для клиентов.</span><span class="sxs-lookup"><span data-stu-id="929a4-924">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="929a4-925">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="929a4-925">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
