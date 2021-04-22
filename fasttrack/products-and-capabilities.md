---
title: Продукты и возможности
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и ожиданиях исходных сред, необходимых перед началом работы. На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.
ms.openlocfilehash: 70e279268f33591884c6bebb8625688ca724480d
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927037"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="a2023-104">Продукты и возможности</span><span class="sxs-lookup"><span data-stu-id="a2023-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="a2023-105">Службы и сценарии, поддерживаемые FastTrack</span><span class="sxs-lookup"><span data-stu-id="a2023-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="a2023-106">В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и ожиданиях исходных сред, необходимых перед началом работы.</span><span class="sxs-lookup"><span data-stu-id="a2023-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="a2023-107">На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.</span><span class="sxs-lookup"><span data-stu-id="a2023-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="a2023-108">FastTrack предоставляет рекомендации, которые помогут вам сначала с основными возможностями (общими для всех Microsoft Online Services), а затем с помощью вовсю каждой подходящих служб:</span><span class="sxs-lookup"><span data-stu-id="a2023-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="a2023-109">Общие</span><span class="sxs-lookup"><span data-stu-id="a2023-109">General</span></span>](#general)
  - [<span data-ttu-id="a2023-110">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="a2023-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="a2023-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="a2023-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="a2023-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="a2023-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="a2023-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="a2023-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="a2023-114">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="a2023-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="a2023-115">Служба Assure для приложений</span><span class="sxs-lookup"><span data-stu-id="a2023-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="a2023-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="a2023-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="a2023-117">Сведения о требованиях к исходной среде для Office 365 для государственных организаций США см. в статье [Требования к исходной среде для Office 365 для государственных организаций США](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="a2023-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="a2023-118">Общие</span><span class="sxs-lookup"><span data-stu-id="a2023-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-119"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-120"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-121"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a2023-122"><strong>Базовое подключение</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="a2023-123">Мы предоставляем удаленные рекомендации по основной интеграции, которая включает в себя подготовка службы, клиент и интеграцию удостоверений.</span><span class="sxs-lookup"><span data-stu-id="a2023-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="a2023-124">Она также включает шаги по обеспечению основы для бортовых служб, таких как Exchange Online, SharePoint Online и Microsoft Teams, включая обсуждение вопросов <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">безопасности,</a>подключения к сети и соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="a2023-125">Подключение одной или нескольких поддерживаемых служб можно начать после завершения базового подключения.</span><span class="sxs-lookup"><span data-stu-id="a2023-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="a2023-126"></li>
</ul>  

<strong> Интеграция удостоверений </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="a2023-127">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="a2023-128">Подготовка локального удостоверения Active Directory для синхронизации с Azure Active Directory (Azure AD), включая установку и настройку Azure AD Connect (одно- или нескольких лесов) и лицензирование (включая лицензирование на основе групп).</span><span class="sxs-lookup"><span data-stu-id="a2023-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="a2023-129">Создание облачных удостоверений, включая массовый импорт и лицензирование, включая использование группового лицензирования.</span><span class="sxs-lookup"><span data-stu-id="a2023-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="a2023-130">Выбор и включение правильного метода проверки подлинности для облачного путешествия, синхронизация хеш-паролей, сквозная проверка подлинности или службы Федерации Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="a2023-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="a2023-131">Выбор и включение более удобного опыта проверки подлинности для пользователей с помощью проверки подлинности без паролей (Fast Identity Online (FIDO)2 или Microsoft Authenticator App).</span><span class="sxs-lookup"><span data-stu-id="a2023-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="a2023-132">Включение AD FS для клиентов с одним лесом Active Directory и удостоверениями, синхронизированными с средством Подключения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="a2023-133">Для этого требуется Windows Server 2012 R2 Active Directory Federation Services 2.0 или более.</span><span class="sxs-lookup"><span data-stu-id="a2023-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="a2023-134">Перенос проверки подлинности из AD FS в Azure AD с помощью синхронизации с использованием хаширования паролей или сквозной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="a2023-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="a2023-135">Перенос предварительно интегрированных приложений (например, приложений azure AD gallery software-as-a-service (SaaS) из AD FS в Azure AD для единого входного (SSO).</span><span class="sxs-lookup"><span data-stu-id="a2023-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="a2023-136">Включение интеграции приложений SaaS с SSO из галереи Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="a2023-137">Включение автоматической подготовки пользователей для предварительно интегрированных приложений <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"></a> SaaS, указанных в списке учебников по интеграции приложений (ограниченных приложениями SaaS-галереи Azure AD и только исходящие подготовки).</span><span class="sxs-lookup"><span data-stu-id="a2023-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="a2023-138"><strong>Включить сеть </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="a2023-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="a2023-139">В рамках преимущества FastTrack мы советуем вам рекомендации по подключению к облачным службам для обеспечения максимальной производительности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="a2023-140"><strong>Леса Active Directory</strong> Они имеют функциональный лесной уровень, установленный для Windows Server 2003 и далее, с следующей конфигурацией леса:</span><span class="sxs-lookup"><span data-stu-id="a2023-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-141">Один лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a2023-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="a2023-142">Топологии с одним лесом учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="a2023-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-143">Топологии с несколькими лесами учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="a2023-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-144">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory, включающим Exchange и/или Lync 2010, Lync 2013 или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a2023-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="a2023-145">Несколько лесов учетных записей Active Directory, каждый из которых включает свою организацию Exchange.</span><span class="sxs-lookup"><span data-stu-id="a2023-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="a2023-146">Задачи, необходимые для конфигурации клиента и интеграции с Azure Active Directory, если это необходимо.</span><span class="sxs-lookup"><span data-stu-id="a2023-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="a2023-147">
  <strong>Важно</strong>  </span><span class="sxs-lookup"><span data-stu-id="a2023-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="a2023-148">Для многолесных сценариев Active Directory, если развернуты Lync 2010, Lync 2013 или Skype для бизнеса, его необходимо развернуть в том же лесу Active Directory, что и Exchange.</span><span class="sxs-lookup"><span data-stu-id="a2023-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="a2023-149">При реализации нескольких лесов Active Directory с несколькими организациями Exchange в гибридной конфигурации Exchange пространства имен общего имени пользователя (UPN) между исходными лесами не поддерживаются.</span><span class="sxs-lookup"><span data-stu-id="a2023-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="a2023-150">Основные пространства имен SMTP между организациями Exchange также должны быть отдельными.</span><span class="sxs-lookup"><span data-stu-id="a2023-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="a2023-151">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/?linkid=845444">гибридных развертываниях с несколькими лесами Active Directory.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="a2023-152">Для всех конфигураций нескольких лесов развертывание служб Федерации Active Directory (AD FS) выходит за рамки.</span><span class="sxs-lookup"><span data-stu-id="a2023-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="a2023-153">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="a2023-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-154"><strong>Приложения Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="a2023-155">Мы предоставляем рекомендации по удаленному развертыванию для:</span><span class="sxs-lookup"><span data-stu-id="a2023-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-156">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="a2023-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="a2023-157">Назначение пользователям и устройствам лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a2023-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="a2023-158">Установка приложений Microsoft 365 с портала Office 365 с помощью технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="a2023-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="a2023-159">Установка приложений Office Mobile (например, Outlook Mobile, Word Mobile, Excel Mobile и PowerPoint Mobile) на устройствах с iOS или Android.</span><span class="sxs-lookup"><span data-stu-id="a2023-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="a2023-160">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a2023-161">Выбор и настройка локальной или облачной установки.</span><span class="sxs-lookup"><span data-stu-id="a2023-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="a2023-162">Создание XML-файла конфигурации средства развертывания Office с помощью центра развертывания Office или встроенного XML-файла для настройки пакета развертывания.</span><span class="sxs-lookup"><span data-stu-id="a2023-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="a2023-163">Развертывание с помощью Microsoft Endpoint Configuration Manager, а также создание пакета Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a2023-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="a2023-164">Кроме того, если у вас есть макрос или надстройка, которая работала с предшествующими версиями Office и у вас проблемы с совместимостью, мы предоставляем рекомендации по исправлению проблемы совместимости без дополнительных затрат с помощью программы App Assure.</span><span class="sxs-lookup"><span data-stu-id="a2023-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="a2023-165">Дополнительные сведения см. в части App <strong>Assure</strong> в <a href="#windows-10">Windows 10.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a2023-166">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, как это определено в требованиях системы <a href="https://go.microsoft.com/fwlink/?LinkID=723597">для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-167"><strong>Сетевое здоровье</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="a2023-168">Мы предоставляем удаленные рекомендации по получению и интерпретации данных подключения к ключевым сетям из среды, показывающие соответствие сайтов организации принципам сетевого подключения Корпорации <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Майкрософт.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="a2023-169">Это подчеркивает оценку сети, которая напрямую влияет на скорость миграции, пользовательский опыт, производительность службы и надежность.</span><span class="sxs-lookup"><span data-stu-id="a2023-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="a2023-170">Мы также поможем вам с помощью любых действий по исправлению последствий, которые будут выделены в этих данных, чтобы помочь вам улучшить оценку сети.</span><span class="sxs-lookup"><span data-stu-id="a2023-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="a2023-171">Доступ к Центру администрирования Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="a2023-172">Требуются новые версии приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="a2023-173">Службы расположения, включенные в качестве рекомендаций по производительности Сети в Центре администрирования <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (предварительный просмотр).</a></span><span class="sxs-lookup"><span data-stu-id="a2023-173">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="a2023-174">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="a2023-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-175"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-176"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-177"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="a2023-178"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="a2023-179">Мы предоставляем удаленные рекомендации по обеспечению безопасности облачных удостоверений для следующих сценариев.</span><span class="sxs-lookup"><span data-stu-id="a2023-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="a2023-180">

<strong>Безопасная инфраструктура фундамента</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="a2023-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="a2023-181">Настройка и включение сильной проверки подлинности для удостоверений, включая защиту с помощью многофакторной проверки подлинности Azure (только в облаке), приложения Microsoft Authenticator и комбинированной регистрации для azure MFA и сброса паролей самообслуживаемых (SSPR).</span><span class="sxs-lookup"><span data-stu-id="a2023-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="a2023-182">Развертывание приложения FIDO2 или Microsoft Authenticator.</span><span class="sxs-lookup"><span data-stu-id="a2023-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="a2023-183">Для клиентов, не использующих Azure AD Premium, предоставляются рекомендации по обеспечению безопасности удостоверений с помощью по умолчанию безопасности.</span><span class="sxs-lookup"><span data-stu-id="a2023-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="a2023-184">Для премиум-клиентов Azure AD предоставляются рекомендации по обеспечению безопасности удостоверений с помощью условного доступа.</span><span class="sxs-lookup"><span data-stu-id="a2023-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="a2023-185">Обнаружение и блокировка использования слабых паролей с помощью Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="a2023-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="a2023-186">Обеспечение удаленного доступа к локальному веб-приложениям с помощью прокси-сервера Приложения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="a2023-187">Включение обнаружения и устранения рисков с помощью Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="a2023-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="a2023-188">Включение настраиваемого экрана регистрации, включая логотип, текст и изображения с настраиваемым брендингом.</span><span class="sxs-lookup"><span data-stu-id="a2023-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="a2023-189">Безопасное совместное использование приложений и служб с гостевых пользователей с помощью Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="a2023-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="a2023-190">Управление доступом для администраторов Office 365 с помощью встроенных административных ролей управления доступом на основе ролей и уменьшение числа привилегированных учетных записей администратора.</span><span class="sxs-lookup"><span data-stu-id="a2023-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="a2023-191">Настройка гибридного присоединиться Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="a2023-192">Настройка присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="a2023-193">
  
<strong>Мониторинг и отчетность</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-194">Включение удаленного мониторинга для AD FS, Azure AD Connect и контроллеров домена с помощью Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="a2023-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="a2023-195">
  
<strong>Управление</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-196">Управление удостоверением Azure AD и доступ к жизненному циклу в масштабе с помощью управления правами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="a2023-197">Управление членством в группах Azure AD, доступом к корпоративным приложениям и назначениями ролей с помощью обзоров доступа к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-198">Просмотр терминов использования Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-199">Управление и управление доступом к привилегированным учетным записям администратора с помощью Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="a2023-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="a2023-200">
  
<strong>Автоматизация и эффективность </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-201">Включение SSPR Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="a2023-202">Позволяет пользователям создавать и управлять собственными группами облачной безопасности или Office 365 с помощью управления группами самообслуживки Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="a2023-203">Управление делегированием доступа к корпоративным приложениям с помощью делегирования группы Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="a2023-204">Включение динамических групп Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="a2023-205">Организация приложений на портале Мои приложения с помощью коллекций.</span><span class="sxs-lookup"><span data-stu-id="a2023-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a2023-206">Локальное active Directory и его среда были подготовлены для Azure AD Premium, включая устранение выявленных проблем, препятствуя интеграции с функциями Azure AD и Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="a2023-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-207"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="a2023-208">Дополнительные сведения о azure Information Protection см. в этой <strong>таблице.</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="a2023-209"><strong>Откройте для себя & Respond</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="a2023-210"><strong>Advanced eDiscovery</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="a2023-211">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="a2023-212">Создание нового случая.</span><span class="sxs-lookup"><span data-stu-id="a2023-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="a2023-213">Удержание хранителей.</span><span class="sxs-lookup"><span data-stu-id="a2023-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="a2023-214">Выполнение поиска.</span><span class="sxs-lookup"><span data-stu-id="a2023-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="a2023-215">Добавление результатов поиска в набор отзывов.</span><span class="sxs-lookup"><span data-stu-id="a2023-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="a2023-216">Запуск аналитики в наборе обзоров.</span><span class="sxs-lookup"><span data-stu-id="a2023-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="a2023-217">Проверка и пометка документов.</span><span class="sxs-lookup"><span data-stu-id="a2023-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="a2023-218">Экспорт данных из набора обзоров.</span><span class="sxs-lookup"><span data-stu-id="a2023-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="a2023-219">Импорт данных без Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="a2023-220"><strong>Расширенный аудит</strong> (поддерживается только в E5)</span><span class="sxs-lookup"><span data-stu-id="a2023-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="a2023-221">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="a2023-222">Включение усовершенствования аудита.</span><span class="sxs-lookup"><span data-stu-id="a2023-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="a2023-223">Выполнение пользовательского интерфейса журнала аудита поиска и основных команд powerShell аудита.</span><span class="sxs-lookup"><span data-stu-id="a2023-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="a2023-224">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a2023-225">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a2023-226">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="a2023-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a2023-227">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="a2023-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a2023-228">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a2023-229">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="a2023-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a2023-230">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="a2023-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a2023-231">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="a2023-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="a2023-232">Настраиваемый сценарий или кодирование.</span><span class="sxs-lookup"><span data-stu-id="a2023-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="a2023-233">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="a2023-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="a2023-234">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="a2023-235">Границы соответствия требованиям и фильтры безопасности.</span><span class="sxs-lookup"><span data-stu-id="a2023-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="a2023-236">Исследования данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="a2023-237">Запросы субъекта данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="a2023-238">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a2023-239">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="a2023-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a2023-240">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="a2023-241">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="a2023-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="a2023-242"><strong>Управление рисками на инсайдерской стороне</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="a2023-243">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="a2023-244">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="a2023-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="a2023-245">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="a2023-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="a2023-246">Создание дел.</span><span class="sxs-lookup"><span data-stu-id="a2023-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="a2023-247">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="a2023-248">Руководство по созданию соединиттеля кадровых ресурсов (HR).</span><span class="sxs-lookup"><span data-stu-id="a2023-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="a2023-249">

<strong> Соответствие требованиям связи </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="a2023-250">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="a2023-251">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="a2023-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="a2023-252">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="a2023-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="a2023-253">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="a2023-254">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a2023-255">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a2023-256">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="a2023-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a2023-257">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="a2023-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a2023-258">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a2023-259">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="a2023-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a2023-260">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="a2023-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a2023-261">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="a2023-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="a2023-262">Создание и управление потоками Power Automate.</span><span class="sxs-lookup"><span data-stu-id="a2023-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="a2023-263">Соединители данных (за пределами соединитетеля управления персоналом).</span><span class="sxs-lookup"><span data-stu-id="a2023-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="a2023-264">Настраиваемые конфигурации регулярного выражения (RegEx).</span><span class="sxs-lookup"><span data-stu-id="a2023-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="a2023-265">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a2023-266">Информационные барьеры.</span><span class="sxs-lookup"><span data-stu-id="a2023-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="a2023-267">Управление привилегированным доступом.</span><span class="sxs-lookup"><span data-stu-id="a2023-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="a2023-268">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="a2023-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a2023-269">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="a2023-270">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="a2023-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="a2023-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="a2023-272">Microsoft 365 Defender — это единый пакет защиты предприятия до и после нарушения, который полностью координирует обнаружение, предотвращение, расследование и реагирование между конечными точками, удостоверениями, электронной почтой и приложениями для обеспечения комплексной защиты от сложных атак.</span><span class="sxs-lookup"><span data-stu-id="a2023-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="a2023-273">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="a2023-274">Предоставление обзора центра безопасности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="a2023-275">Анализ инцидентов с перекрестным продуктом, в том числе сосредоточение внимания на критически важных задачах, обеспечивая полную область атаки, влияние на активы и автоматизированные действия по исправлению, которые сгруппировали вместе.</span><span class="sxs-lookup"><span data-stu-id="a2023-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="a2023-276">Демонстрация того, как Microsoft 365 Defender может организовать исследование активов, пользователей, устройств и почтовых ящиков, которые могли быть скомпрометированы с помощью автоматического самовосстановления.</span><span class="sxs-lookup"><span data-stu-id="a2023-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="a2023-277">Объяснение и предоставление примеров того, как клиенты могут активно охотиться за попытками вторжения и действиями взлома, влияющими на вашу электронную почту, данные, устройства и учетные записи в нескольких наборах данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="a2023-278">Показывая клиентам, как они могут целостно пересматривать и улучшать свою осанку безопасности с помощью Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="a2023-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="a2023-279"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="a2023-280">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="a2023-281">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="a2023-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="a2023-282">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="a2023-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="a2023-283">Исправление или интерпретация различных типов оповещений и отслеживаемой активности.</span><span class="sxs-lookup"><span data-stu-id="a2023-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="a2023-284">Изучение пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="a2023-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="a2023-285">Настраиваемая охота на угрозы.</span><span class="sxs-lookup"><span data-stu-id="a2023-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="a2023-286">Сведения о безопасности и управление событиями (SIEM) или интеграция API.</span><span class="sxs-lookup"><span data-stu-id="a2023-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="a2023-288">Microsoft Cloud App Security — это брокер облачной безопасности доступа (CASB), который обеспечивает богатую видимость, контроль над перемещениями данных и сложную аналитику для выявления и борьбы с киберугрозами во всех облачных службах Майкрософт и сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="a2023-289">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-290">Настройка портала, в том числе:</span><span class="sxs-lookup"><span data-stu-id="a2023-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="a2023-291">Импорт групп пользователей.</span><span class="sxs-lookup"><span data-stu-id="a2023-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="a2023-292">Управление доступом и настройками администратора.</span><span class="sxs-lookup"><span data-stu-id="a2023-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="a2023-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span><span class="sxs-lookup"><span data-stu-id="a2023-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="a2023-294">Настройка ip-диапазонов и тегов.</span><span class="sxs-lookup"><span data-stu-id="a2023-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="a2023-295">Персонализация интерфейса для конечных пользователей с помощью логотипа и настраиваемого обмена сообщениями.</span><span class="sxs-lookup"><span data-stu-id="a2023-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="a2023-296">Настройка облачных открытий для предоставления теневых ИТ-данных с помощью:</span><span class="sxs-lookup"><span data-stu-id="a2023-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="a2023-297">Microsoft Defender для конечных точек.</span><span class="sxs-lookup"><span data-stu-id="a2023-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="a2023-298">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="a2023-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="a2023-299">iboss.</span><span class="sxs-lookup"><span data-stu-id="a2023-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="a2023-300">Подключение <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">рекомендуемых приложений с</a> помощью соединители приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-300">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="a2023-301">Настройка управления приложениями условного доступа на порталах безопасности условного доступа и облачных приложений для применения элементов управления сеансами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="a2023-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="a2023-302">Развертывание панелей безопасности облачных приложений и облачных открытий.</span><span class="sxs-lookup"><span data-stu-id="a2023-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="a2023-303">Настройка оценки рисков приложений в зависимости от приоритетов организации.</span><span class="sxs-lookup"><span data-stu-id="a2023-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="a2023-304">Создание тегов и категорий приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="a2023-305">Санкции и несанкционные приложения.</span><span class="sxs-lookup"><span data-stu-id="a2023-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="a2023-306">Использование журналов действий и файлов.</span><span class="sxs-lookup"><span data-stu-id="a2023-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="a2023-307">Управление приложениями OAuth.</span><span class="sxs-lookup"><span data-stu-id="a2023-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="a2023-308">Понимание корреляции инцидентов на портале Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="a2023-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="a2023-309">Предоставление помощи в настройке в <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> лучших случаях использования casBs (включая создание или обновление до шести политик) за исключением:</span><span class="sxs-lookup"><span data-stu-id="a2023-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="a2023-310">Аудит конфигурации среды интернета как среды службы (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="a2023-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="a2023-311">Мониторинг действий пользователей для защиты от угроз в средах IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="a2023-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="a2023-312"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="a2023-313">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="a2023-314">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="a2023-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="a2023-315">Настройка инфраструктуры, установки или развертывания автоматических загрузок журналов для непрерывных отчетов с помощью Docker или сборщика журналов.</span><span class="sxs-lookup"><span data-stu-id="a2023-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="a2023-316">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">топ-20 случаев использования casBs.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="a2023-317">Создание отчета об обнаружении облачных данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="a2023-318">Блокировка использования приложений с помощью скриптов блоков.</span><span class="sxs-lookup"><span data-stu-id="a2023-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="a2023-319">Подключение настраиваемой программы.</span><span class="sxs-lookup"><span data-stu-id="a2023-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="a2023-320">Интеграция с сторонними поставщиками удостоверений (isPs) и поставщиками защиты от потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="a2023-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="a2023-321">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="a2023-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="a2023-322">Автоматическое исследование и исправление, включая книги Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="a2023-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="a2023-323">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="a2023-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="a2023-324">Развертывание обнаружения облачных приложений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="a2023-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="a2023-325"><strong>Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="a2023-326">Microsoft Defender for Endpoint — это платформа, призванная помочь корпоративным сетям предотвращать, обнаруживать, исследовать и реагировать на расширенные угрозы.</span><span class="sxs-lookup"><span data-stu-id="a2023-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="a2023-327">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-328">Развертывание технологий для защиты конечных точек.</span><span class="sxs-lookup"><span data-stu-id="a2023-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="a2023-329">Настройка профилей защиты конечной точки и ограничений устройств.</span><span class="sxs-lookup"><span data-stu-id="a2023-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="a2023-330">Оценка управления версиями ОС и устройствами (включая Intune, Microsoft Endpoint Configuration Manager, Объекты групповой политики (GPOs) и сторонние конфигурации), а также состояние служб av Защитник Windows или другого программного обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="a2023-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="a2023-331">Оценка состояния служб av Windows или другого программного обеспечения безопасности конечной точки.</span><span class="sxs-lookup"><span data-stu-id="a2023-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="a2023-332">Оценка прокси и брандмауэров, ограничивающих сетевой трафик.</span><span class="sxs-lookup"><span data-stu-id="a2023-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="a2023-333">Включение службы Microsoft Defender для конечных точек, объясняя, как развернуть профиль агента Defender для конечной точки с помощью конечной точки на борту.</span><span class="sxs-lookup"><span data-stu-id="a2023-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="a2023-334">Рекомендации по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="a2023-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-335">Управление угрозами и уязвимостями.</span><span class="sxs-lookup"><span data-stu-id="a2023-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-336">Сокращение направлений атак.</span><span class="sxs-lookup"><span data-stu-id="a2023-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-337">Защита нового поколения.</span><span class="sxs-lookup"><span data-stu-id="a2023-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-338">Выявление конечных точек и реагирование на них.</span><span class="sxs-lookup"><span data-stu-id="a2023-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-339">Автоматическое исследование и защита.</span><span class="sxs-lookup"><span data-stu-id="a2023-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-340">Оценка безопасности</span><span class="sxs-lookup"><span data-stu-id="a2023-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-341">Просмотр имитаций и учебных пособий (например, сценариев практики, поддельных вредоносных программ и автоматических расследований).</span><span class="sxs-lookup"><span data-stu-id="a2023-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="a2023-342">Общие сведения о функциях создания отчетов и аналитики угроз.</span><span class="sxs-lookup"><span data-stu-id="a2023-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="a2023-343">Интеграция Microsoft Defender для Office 365 с Microsoft Defender для конечной точки.</span><span class="sxs-lookup"><span data-stu-id="a2023-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="a2023-344">Пошаговые руководства по поведению на портале Центра безопасности в Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="a2023-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="a2023-345">Следующие операционные системы:</span><span class="sxs-lookup"><span data-stu-id="a2023-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-346">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-347">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="a2023-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-348">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="a2023-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-349">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="a2023-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-350">Windows Server Semi-Annual (SAC) версии 1803.</span><span class="sxs-lookup"><span data-stu-id="a2023-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-351">версии macOS 10.13, 10.14 и 10.15.</span><span class="sxs-lookup"><span data-stu-id="a2023-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="a2023-352">
<strong>Примечание:</strong> Все версии Windows Server должны управляться последней версией System Center Configuration Manager 2012 (версии 1012 R2, 1511 или 1602) или Microsoft Endpoint Configuration Manager (версии 2002 или более).</span><span class="sxs-lookup"><span data-stu-id="a2023-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="a2023-353"></li>
</ul>

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a2023-354">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="a2023-355">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="a2023-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="a2023-356">Текущее управление и реагирование на угрозы.</span><span class="sxs-lookup"><span data-stu-id="a2023-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="a2023-357">Учет или конфигурация для следующих агентов Microsoft Defender для конечных точек:</span><span class="sxs-lookup"><span data-stu-id="a2023-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-358">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="a2023-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-359">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="a2023-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-360">Linux.</span><span class="sxs-lookup"><span data-stu-id="a2023-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-361">Мобильные устройства (Android и iOS).</span><span class="sxs-lookup"><span data-stu-id="a2023-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="a2023-362">Виртуальная инфраструктура настольных компьютеров (VDI) (сохраняемая или нестойка).</span><span class="sxs-lookup"><span data-stu-id="a2023-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-363">Бортовая и конфигурация сервера:</span><span class="sxs-lookup"><span data-stu-id="a2023-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-364">Настройка прокси-сервера для автономной связи.</span><span class="sxs-lookup"><span data-stu-id="a2023-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-365">Настройка пакетов развертывания Configuration Manager на экземплярах и версиях диспетчера конфигурации на уровне.</span><span class="sxs-lookup"><span data-stu-id="a2023-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-366">На борту серверов в Центр безопасности Azure.</span><span class="sxs-lookup"><span data-stu-id="a2023-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-367">Серверы, не управляемые диспетчером конфигурации.</span><span class="sxs-lookup"><span data-stu-id="a2023-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-368">бортовая и конфигурация macOS:</span><span class="sxs-lookup"><span data-stu-id="a2023-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-369">Развертывание на основе ручного intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-370">Развертывание на основе JAMF.</span><span class="sxs-lookup"><span data-stu-id="a2023-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="a2023-371">Другое развертывание на основе продуктов для управления мобильными устройствами (MDM).</span><span class="sxs-lookup"><span data-stu-id="a2023-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-372">Ручное развертывание.</span><span class="sxs-lookup"><span data-stu-id="a2023-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-373">Конфигурация следующих возможностей сокращения направлений атак:</span><span class="sxs-lookup"><span data-stu-id="a2023-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-374">Аппаратная изоляция.</span><span class="sxs-lookup"><span data-stu-id="a2023-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-375">Управление приложениями.</span><span class="sxs-lookup"><span data-stu-id="a2023-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="a2023-376">Управление устройствами.</span><span class="sxs-lookup"><span data-stu-id="a2023-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="a2023-377">Защита от эксплойтов.</span><span class="sxs-lookup"><span data-stu-id="a2023-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-378">Сетевой брандмауэр.</span><span class="sxs-lookup"><span data-stu-id="a2023-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="a2023-379">Конфигурация или управление функциями защиты учетных записей, например:</span><span class="sxs-lookup"><span data-stu-id="a2023-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="a2023-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="a2023-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="a2023-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="a2023-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="a2023-382">Конфигурация или управление BitLocker.</span><span class="sxs-lookup"><span data-stu-id="a2023-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="a2023-383">Развертывание или конфигурация экспертов Майкрософт по угрозам.</span><span class="sxs-lookup"><span data-stu-id="a2023-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="a2023-384">Настройка или обучение, просмотр API или сведений о безопасности и подключений к управлению событиями (SIEM).</span><span class="sxs-lookup"><span data-stu-id="a2023-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="a2023-385">Развертывание или конфигурация защиты от угроз (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="a2023-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="a2023-386">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="a2023-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="a2023-387">Учебные материалы или руководства по использованию или созданию запросов Kusto.</span><span class="sxs-lookup"><span data-stu-id="a2023-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="a2023-388">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="a2023-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="a2023-389"><strong>Защитник Майкрософт для удостоверения </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="a2023-390">Microsoft Defender для удостоверений — это облачное решение для обеспечения безопасности, использующее ваши локальные сигналы Active Directory для выявления, обнаружения и исследования расширенных угроз, скомпрометированных удостоверений и вредоносных внутренних действий, направленных против вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a2023-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="a2023-391">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="a2023-392">Создание экземпляра Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a2023-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="a2023-393">Подключение защитника удостоверений к Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a2023-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="a2023-394">Оценка готовности среды к развертыванию датчика Defender для удостоверений на контроллерах домена, в том числе:</span><span class="sxs-lookup"><span data-stu-id="a2023-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="a2023-395">Запуск средства размеров для планирования емкости ресурсов.</span><span class="sxs-lookup"><span data-stu-id="a2023-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="a2023-396">Запуск средства аудита для оценки совместимости контроллеров домена с датчиком.</span><span class="sxs-lookup"><span data-stu-id="a2023-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="a2023-397">Развертывание датчика для захвата и размыва сетевого трафика и событий Windows непосредственно из контроллеров домена, в том числе:</span><span class="sxs-lookup"><span data-stu-id="a2023-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="a2023-398">Загрузка пакета датчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="a2023-399">Настройка датчика.</span><span class="sxs-lookup"><span data-stu-id="a2023-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="a2023-400">Установка датчика на контроллере домена безмолвно.</span><span class="sxs-lookup"><span data-stu-id="a2023-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="a2023-401">Развертывание датчика в многолесной среде.</span><span class="sxs-lookup"><span data-stu-id="a2023-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="a2023-402">Интеграция defender for Identity с безопасностью облачных приложений Microsoft (лицензирование безопасности облачных приложений не требуется).</span><span class="sxs-lookup"><span data-stu-id="a2023-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="a2023-403">Предоставление рекомендаций по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="a2023-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="a2023-404">Настройка среды для уменьшения "шума".</span><span class="sxs-lookup"><span data-stu-id="a2023-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="a2023-405">Понимание отчета об оценке состояния безопасности удостоверений.</span><span class="sxs-lookup"><span data-stu-id="a2023-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="a2023-406">Понимание оценки приоритетов для исследования пользователей и отчета о рейтинге исследования пользователей.</span><span class="sxs-lookup"><span data-stu-id="a2023-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="a2023-407">Понимание неактивного отчета пользователя.</span><span class="sxs-lookup"><span data-stu-id="a2023-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="a2023-408">Предоставление параметров исправлений на скомпрометированную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="a2023-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="a2023-409">Упрощение переноса из Advanced Threat Analytics (ATA) в Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="a2023-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="a2023-410"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="a2023-411">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="a2023-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="a2023-412">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="a2023-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="a2023-413">Развертывание датчика Defender для удостоверений, в том числе:</span><span class="sxs-lookup"><span data-stu-id="a2023-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="a2023-414">Ручное планирование емкости.</span><span class="sxs-lookup"><span data-stu-id="a2023-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="a2023-415">Развертывание датчика в автономных емкостях.</span><span class="sxs-lookup"><span data-stu-id="a2023-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="a2023-416">Развертывание датчика с помощью адаптора сетевого интерфейса (NIC).</span><span class="sxs-lookup"><span data-stu-id="a2023-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="a2023-417">Развертывание датчика через сторонний инструмент.</span><span class="sxs-lookup"><span data-stu-id="a2023-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="a2023-418">Подключение к облачной службе Defender for Identity с помощью подключения веб-прокси.</span><span class="sxs-lookup"><span data-stu-id="a2023-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="a2023-419">Создание и управление медоносами.</span><span class="sxs-lookup"><span data-stu-id="a2023-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="a2023-420">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="a2023-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="a2023-421">Исправление или интерпретация различных типов оповещений и отслеживаемой деятельности.</span><span class="sxs-lookup"><span data-stu-id="a2023-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="a2023-422">Исследование пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="a2023-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="a2023-423">Угроза или продвинутая охота.</span><span class="sxs-lookup"><span data-stu-id="a2023-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="a2023-424">Реагирование на инцидент.</span><span class="sxs-lookup"><span data-stu-id="a2023-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="a2023-425">Предоставление лабораторного руководства по оповещению о безопасности для Defender для identity.</span><span class="sxs-lookup"><span data-stu-id="a2023-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="a2023-426">Предоставление уведомлений, когда Defender for Identity обнаруживает подозрительные действия, отправляя оповещения безопасности на сервер syslog с помощью назначенного датчика.</span><span class="sxs-lookup"><span data-stu-id="a2023-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="a2023-427">Настройка defender for Identity для выполнения запросов с помощью удаленного протокола диспетчера безопасности (SAMR) для идентификации локальных администраторов на определенных машинах.</span><span class="sxs-lookup"><span data-stu-id="a2023-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="a2023-428">Настройка VPN-решений для добавления сведений из VPN-подключения на страницу профиля пользователя.</span><span class="sxs-lookup"><span data-stu-id="a2023-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="a2023-429">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="a2023-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="a2023-430">Развертывание датчиков Defender для удостоверений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="a2023-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a2023-431">Развернут Active Directory.</span><span class="sxs-lookup"><span data-stu-id="a2023-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="a2023-432">Контроллеры домена, которые вы собираетесь установить датчики Defender для удостоверений, подключены к облачной службе Defender для удостоверений.</span><span class="sxs-lookup"><span data-stu-id="a2023-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="a2023-433">Брандмауэр и прокси должны быть открыты для связи с облачной службой Defender for Identity (\*.atp.azure.com порт 443 должен быть открыт).</span><span class="sxs-lookup"><span data-stu-id="a2023-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="a2023-434">Контроллеры домена, работающие на одном из следующих:</span><span class="sxs-lookup"><span data-stu-id="a2023-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="a2023-435">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="a2023-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="a2023-436">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="a2023-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="a2023-437">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="a2023-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="a2023-438">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="a2023-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="a2023-439">Windows Server 2019 с KB4487044 (сборка ОС 17763.316).</span><span class="sxs-lookup"><span data-stu-id="a2023-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="a2023-440"><strong>Microsoft Defender для Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="a2023-441">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-442">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="a2023-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="a2023-443">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="a2023-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="a2023-444">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="a2023-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="a2023-445">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="a2023-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a2023-446">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="a2023-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="a2023-447"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="a2023-448">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-449">Создание и публикация меток и политик хранения (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="a2023-450">Управление записями (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="a2023-451">Проверка создания плана файлов.</span><span class="sxs-lookup"><span data-stu-id="a2023-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="a2023-452">Создание и управление записями (включая записи на основе событий).</span><span class="sxs-lookup"><span data-stu-id="a2023-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="a2023-453">Просмотр диспозиции.</span><span class="sxs-lookup"><span data-stu-id="a2023-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="a2023-454">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a2023-455">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a2023-456">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="a2023-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a2023-457">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="a2023-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a2023-458">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a2023-459">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="a2023-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a2023-460">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="a2023-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a2023-461">

  <strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="a2023-462">Разработка плана файлов управления записями.</span><span class="sxs-lookup"><span data-stu-id="a2023-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="a2023-463">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="a2023-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="a2023-464">Разработка информационной архитектуры в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a2023-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="a2023-465">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="a2023-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="a2023-466">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a2023-467">Поддержка E3.</span><span class="sxs-lookup"><span data-stu-id="a2023-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="a2023-468">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="a2023-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a2023-469">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="a2023-470">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="a2023-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-471"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="a2023-472">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-473">Классификация данных (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-474">Типы конфиденциальной информации (поддерживаемые в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-475">Создание меток конфиденциальности (поддерживаемых в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-476">Применение меток чувствительности (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-477">Классификаторы, которые можно обучить (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-478">Знание данных с помощью обозревателя контента и проводника действий (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-479">Публикация меток с использованием политик (ручная и автоматическая) (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-480">Создание политик предотвращения потери данных конечной точки (DLP) для устройств Windows 10 (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="a2023-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="a2023-481">Создание политик DLP для чатов и каналов Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="a2023-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="a2023-482">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="a2023-483">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="a2023-484">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="a2023-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="a2023-485">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="a2023-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="a2023-486">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="a2023-487">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="a2023-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="a2023-488">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="a2023-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="a2023-489">

<strong> Защита информации Azure</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="a2023-490">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="a2023-491">Активация и настройка клиента.</span><span class="sxs-lookup"><span data-stu-id="a2023-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="a2023-492">Создание и настройка меток и политик (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="a2023-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a2023-493">Применение защиты информации к документам (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="a2023-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a2023-494">Автоматическое классификация и маркировка сведений в приложениях Office (например, Word, PowerPoint, Excel и Outlook), работающих в Windows и использующих клиент Azure Information Protection (поддерживается в P2).</span><span class="sxs-lookup"><span data-stu-id="a2023-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="a2023-495">Обнаружение и маркировка файлов в покое с помощью сканера защиты информации Azure (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="a2023-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="a2023-496">Отслеживание сообщений электронной почты в пути с помощью правил потока обработки почты Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="a2023-497">Мы также предоставляем рекомендации, если вы хотите применить защиту с помощью служб управления правами Microsoft Azure (Azure RMS), шифрования сообщений Office 365 (OME) и предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="a2023-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="a2023-498"><strong>Ниже приводится неосякаемая область </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="a2023-499">Ключ клиента.</span><span class="sxs-lookup"><span data-stu-id="a2023-499">Customer key.</span></span></li>
<li><span data-ttu-id="a2023-500">Настраиваемая разработка регулярных выражений (RegEx) для типов конфиденциальной информации.</span><span class="sxs-lookup"><span data-stu-id="a2023-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="a2023-501">Создание или изменение словарей ключевых слов.</span><span class="sxs-lookup"><span data-stu-id="a2023-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="a2023-502">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="a2023-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="a2023-503">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="a2023-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="a2023-504">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="a2023-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="a2023-505">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="a2023-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="a2023-506">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="a2023-507">Помимо основной <strong></strong> части в <a href="#general">целом,</a>минимальные требования к системе, за исключением Azure Information Protection, не существуют.</span><span class="sxs-lookup"><span data-stu-id="a2023-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="a2023-508"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="a2023-509">Обязанности, необходимые для клиента, включают:</span><span class="sxs-lookup"><span data-stu-id="a2023-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="a2023-510">Список местоположений для совместной работы с файлами, которые необходимо отсканировать.</span><span class="sxs-lookup"><span data-stu-id="a2023-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="a2023-511">Утвержденная таксономия классификации.</span><span class="sxs-lookup"><span data-stu-id="a2023-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="a2023-512">Понимание любых нормативных ограничений или требований в отношении управления ключами.</span><span class="sxs-lookup"><span data-stu-id="a2023-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="a2023-513">Учетная запись службы, созданная для локального Active Directory, синхронизированного с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="a2023-514">Метки, настроенные для классификации и защиты.</span><span class="sxs-lookup"><span data-stu-id="a2023-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="a2023-515">Все необходимые условия для сканера защиты информации Azure на месте.</span><span class="sxs-lookup"><span data-stu-id="a2023-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="a2023-516">Дополнительные сведения см. в дополнительных сведениях, необходимых для установки и развертывания сканера единой маркировки <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-516">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="a2023-517">Убедитесь, что на устройствах пользователей запущена поддерживаемая операционная система и установлены необходимые условия.</span><span class="sxs-lookup"><span data-stu-id="a2023-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="a2023-518">Дополнительные сведения см. в следующих сведениях.</span><span class="sxs-lookup"><span data-stu-id="a2023-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="a2023-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Руководство по администрированию: Установите клиент единой маркировки Azure Information Protection для пользователей</a>   </span><span class="sxs-lookup"><span data-stu-id="a2023-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="a2023-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Что такое приложение Azure Information Protection для iOS или Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="a2023-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="a2023-521">Установка и конфигурация соединителя Azure RMS и серверов, включая соединителя Active Directory RMS (AD RMS) для гибридной поддержки.</span><span class="sxs-lookup"><span data-stu-id="a2023-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="a2023-522">Настройка и конфигурация Bring Your Own Key (BYOK), Double Key Encryption (DKE) (только для клиента единой маркировки) или Hold Your Own Key (HYOK) (только для классического клиента) если вам потребуется один из этих вариантов развертывания.</span><span class="sxs-lookup"><span data-stu-id="a2023-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="a2023-524">Мы предоставляем удаленные рекомендации по готовности использовать Intune в качестве облачного поставщика управления мобильными устройствами (MDM) и поставщика управления мобильными приложениями (MAM) для ваших приложений и устройств.</span><span class="sxs-lookup"><span data-stu-id="a2023-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="a2023-525">Конкретные действия зависят от исходной среды и основаны на мобильном устройстве и требованиях к управлению мобильными приложениями.</span><span class="sxs-lookup"><span data-stu-id="a2023-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="a2023-526">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="a2023-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-527">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="a2023-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="a2023-528">Настройка удостоверений, которые будут использоваться Intune, используя локальное active Directory или облачные идентификаторы (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="a2023-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="a2023-529">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="a2023-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="a2023-530">Настройка полномочий MDM на основе потребностей управления, в том числе:</span><span class="sxs-lookup"><span data-stu-id="a2023-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-531">Настройка Intune в качестве центра MDM, когда Intune является единственным решением MDM.</span><span class="sxs-lookup"><span data-stu-id="a2023-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-532">Предоставление рекомендаций по MDM для следующих действий:</span><span class="sxs-lookup"><span data-stu-id="a2023-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-533">Настройка тестовых групп, используемых для проверки политик управления MDM.</span><span class="sxs-lookup"><span data-stu-id="a2023-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-534">Настройка политик управления MDM и таких служб, как:</span><span class="sxs-lookup"><span data-stu-id="a2023-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-535">Развертывание приложений для каждой поддерживаемой платформы с помощью веб-ссылок или глубоких ссылок.</span><span class="sxs-lookup"><span data-stu-id="a2023-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="a2023-536">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="a2023-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-537">Развертывание профилей электронной почты, беспроводных сетей и VPN, если у вас есть существующие полномочия сертификата, беспроводная сеть или инфраструктура VPN в организации.</span><span class="sxs-lookup"><span data-stu-id="a2023-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="a2023-538">Подключение к складу данных Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="a2023-539">Интеграция Intune со следующими компонентами:</span><span class="sxs-lookup"><span data-stu-id="a2023-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-540">Просмотр группы для удаленной помощи (требуется подписка на просмотр группы).</span><span class="sxs-lookup"><span data-stu-id="a2023-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="a2023-541">Решения партнеров Mobile Threat Defense (MTD) (требуется подписка на MTD).</span><span class="sxs-lookup"><span data-stu-id="a2023-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="a2023-542">Решение по управлению расходами телекома (требуется подписка на решение по управлению расходами на телеком).</span><span class="sxs-lookup"><span data-stu-id="a2023-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="a2023-543">Регистрация устройств всех поддерживаемых платформ в Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="a2023-544">Предоставление рекомендаций по защите приложений по:</span><span class="sxs-lookup"><span data-stu-id="a2023-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-545">Настройка политик защиты приложений для каждой поддерживаемой платформы.</span><span class="sxs-lookup"><span data-stu-id="a2023-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="a2023-546">Настройка политик условного доступа для управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="a2023-547">Ориентация соответствующих групп пользователей с помощью ранее упомянутых политик MAM.</span><span class="sxs-lookup"><span data-stu-id="a2023-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-548">Использование отчетов об использовании управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-549">Предоставление руководства по миграции из устаревшего управления ПК в intune MDM.</span><span class="sxs-lookup"><span data-stu-id="a2023-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="a2023-550">
 
</li>
</ul>
  
<strong>Подключение к облаку</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="a2023-551">Мы повествуем о готовности к подключению к существующим средам Configuration Manager с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="a2023-552">Конкретные действия зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="a2023-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="a2023-553">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="a2023-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="a2023-554">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="a2023-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="a2023-555">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory и облачных удостоверений.</span><span class="sxs-lookup"><span data-stu-id="a2023-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="a2023-556">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="a2023-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="a2023-557">Предоставление рекомендаций по настройке гибридного присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a2023-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="a2023-558">Предоставление рекомендаций по настройке автоматической регистрации Azure AD для автозарегистрации MDM.</span><span class="sxs-lookup"><span data-stu-id="a2023-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="a2023-559">Предоставление рекомендаций по настройкам шлюза управления облачными ресурсами при их совместном управлении удаленным управлением устройствами в Интернете.</span><span class="sxs-lookup"><span data-stu-id="a2023-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="a2023-560">Настройка поддерживаемых рабочих нагрузок, которые нужно перевести в Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="a2023-561">Установка клиента диспетчера конфигураций на устройствах, зарегистрированных в Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="a2023-562"><strong>Безопасно развертывание мобильных устройств Outlook для iOS и Android</strong> Мы можем предоставить рекомендации по безопасному развертыванию мобильных устройств Outlook для iOS и Android в организации, чтобы убедиться, что у пользователей установлены все необходимые приложения.</span><span class="sxs-lookup"><span data-stu-id="a2023-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="a2023-563">Действия по безопасному развертыванию мобильных устройств Outlook для iOS и Android с помощью Intune зависят от исходных сред.</span><span class="sxs-lookup"><span data-stu-id="a2023-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="a2023-564">Он может включать в себя:</span><span class="sxs-lookup"><span data-stu-id="a2023-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-565">Загрузка приложений Outlook для iOS и Android, Microsoft Authenticator и Портала компании Intune через Магазин приложений Apple или Магазин Google Play.</span><span class="sxs-lookup"><span data-stu-id="a2023-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="a2023-566">Предоставление рекомендаций по настройке:</span><span class="sxs-lookup"><span data-stu-id="a2023-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-567">Развертывание приложений Outlook для iOS и Android, Microsoft Authenticator и портала компании Intune с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="a2023-568">Политики защиты приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-569">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="a2023-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="a2023-570">Политики конфигурации приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="a2023-571">ИТ-администраторы должны иметь существующие инфраструктуры сертификатов, беспроводной сети и VPN, которые уже работают в рабочей среде при планировании развертывания профилей беспроводной сети и VPN с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="a2023-572"><strong>Примечание.</strong>Преимущество службы FastTrack не включает помощь в настройке или настройке органов сертификации, беспроводных сетей, инфраструктур VPN или push-сертификатов Apple MDM для Intune.</span><span class="sxs-lookup"><span data-stu-id="a2023-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="a2023-573"><strong>Примечание</strong>. Преимущество службы FastTrack не включает помощь по настройке или обновлению сервера сайта диспетчера конфигураций или клиента диспетчера конфигураций до минимальных требований, необходимых для поддержки подключения к облаку.</span><span class="sxs-lookup"><span data-stu-id="a2023-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="a2023-574">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="a2023-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="a2023-575"><strong>Intune, интегрированный с Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="a2023-576"><strong>Примечание.</strong>Мы предоставляем помощь в интеграции Intune с Microsoft Defender для конечной точки и создании политик соответствия требованиям устройств на основе оценки уровня риска Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="a2023-577">Мы не предоставляем помощь в приобретении, лицензировании или активации.</span><span class="sxs-lookup"><span data-stu-id="a2023-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="a2023-578">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="a2023-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="a2023-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="a2023-580">ИТ-администраторы отвечают за регистрацию устройств в организации путем отправки поставщиком оборудования идентификаторов оборудования от имени администраторов или с помощью самостоятельной их отправки в службу Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="a2023-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="a2023-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="a2023-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-582"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-583"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-584"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a2023-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="a2023-586">Для Exchange Online мы повеяем процесс, чтобы ваша организация была готова к использованию электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a2023-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="a2023-587">Точные действия зависят от исходных сред и планов миграции электронной почты.</span><span class="sxs-lookup"><span data-stu-id="a2023-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="a2023-588">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-589">Настройка функций Exchange Online Protection (EOP) для всех доменов, поддерживающих почту и проверенных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-590">Указать записи обмена почтой (MX) в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-591">Настройка функции Microsoft Defender для Office 365, если она является частью службы подписки.</span><span class="sxs-lookup"><span data-stu-id="a2023-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="a2023-592">Дополнительные сведения см. в <strong>этой таблице в microsoft Defender for Office 365.</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="a2023-p127">Настройка функции защиты от потери данных (DLP) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="a2023-p128">Настройка шифрования сообщений Office 365 (OME) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="a2023-597">
  <strong>Примечание:</strong> Служба репликации почтовых ящиков (MRS) пытается перенести электронные письма управляемых прав на информацию (IRM) из локального почтового ящика в соответствующий почтовый ящик Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="a2023-598">Возможность чтения защищенных данных после переноса зависит от сопоставления клиентом шаблонов службы Active Directory Rights Managed Services (AD RMS) и их копирования в службу Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="a2023-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="a2023-599">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="a2023-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a2023-600">Настройка DNS, включая необходимые рамки политики автообнаружения, политик отправитель (SPF), DomainKeys Identified Mail (DKIM), проверку подлинности сообщений на основе домена, отчетность и соответствие (DMARC) и записи MX (по мере необходимости).</span><span class="sxs-lookup"><span data-stu-id="a2023-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="a2023-601">Настройка потока обработки почты между исходной средой обмена сообщениями и Exchange Online (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="a2023-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="a2023-602">Перенос почты из исходной среды обмена сообщениями в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-603">Настройка почтовых клиентов (Outlook для Windows, Outlook в Интернете, Outlook для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="a2023-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="a2023-604">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="a2023-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="a2023-605">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="https://docs.microsoft.com/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="a2023-606">В исходных средах должен быть один из следующих минимальных уровней:</span><span class="sxs-lookup"><span data-stu-id="a2023-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-607">Одна или несколько организаций Exchange с Exchange Server 2003 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="a2023-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="a2023-608">Одна почтовая среда, поддерживающая протокол IMAP.</span><span class="sxs-lookup"><span data-stu-id="a2023-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="a2023-609">Одна среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="a2023-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="a2023-610">Сведения о возможностях multi-Geo см. в <a href="https://go.microsoft.com/fwlink/?linkid=872776">сайте Multi-Geo Capabilities in Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="a2023-611">Клиентские программы в Интернете, такие как Project for Office 365, Outlook for Windows, Outlook для iOS и Android, клиент синхронизации OneDrive для бизнеса, Power BI Desktop и Skype для бизнеса должны быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="a2023-612"><strong>Microsoft Defender для Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="a2023-613">Дополнительные сведения см. <strong>в веб-сайте Microsoft Defender для Office 365</strong> в <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="a2023-614"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="a2023-615">Дополнительные сведения см. в <strong>сайте Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-616"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="a2023-617">Дополнительные сведения см. <strong>в веб-сайте Microsoft Information Protection</strong> in Security and <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Compliance.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="a2023-619">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-620">Подтверждение минимальных требований в Exchange Online, SharePoint Online, Office 365 Groups и Azure AD для поддержки Teams.</span><span class="sxs-lookup"><span data-stu-id="a2023-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="a2023-621">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="a2023-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a2023-622">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="a2023-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="a2023-623">Подтверждение того, что рабочее пространство Teams включено в клиенте Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="a2023-624">Включение или отключение пользовательских лицензий.</span><span class="sxs-lookup"><span data-stu-id="a2023-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="a2023-625">Оценка сети для Teams:</span><span class="sxs-lookup"><span data-stu-id="a2023-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-626">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="a2023-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="a2023-627">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="a2023-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="a2023-628">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="a2023-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="a2023-629">Настройка политики приложений Teams (веб-приложение Teams, приложение Teams Desktop и Teams для приложений для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="a2023-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="a2023-630">Если применимо, мы также предоставляем рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-631">Устройства комнат Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="a2023-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="a2023-632">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств телефонной и конференц-связи. Устройства перечислены в <a href="https://go.microsoft.com/fwlink/?linkid=2066478">каталоге устройств Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="a2023-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="a2023-633">Удаленная помощь с конфигурацией на стороне служб сертифицированных устройств Microsoft Teams Rooms.</span><span class="sxs-lookup"><span data-stu-id="a2023-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="a2023-634">Включение Аудиоконференций:</span><span class="sxs-lookup"><span data-stu-id="a2023-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="a2023-635">Настройка организации с использованием параметров по умолчанию для схемы конференции.</span><span class="sxs-lookup"><span data-stu-id="a2023-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="a2023-636">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="a2023-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="a2023-637">Телефонная система:</span><span class="sxs-lookup"><span data-stu-id="a2023-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-638">Настройка облачных голосовых функций для организации.</span><span class="sxs-lookup"><span data-stu-id="a2023-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="a2023-639">Руководство по планам вызова<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(доступные рынки):</a></span><span class="sxs-lookup"><span data-stu-id="a2023-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="a2023-640">Назначение номеров лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="a2023-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="a2023-641">Рекомендации по портированию локальных номеров до 999 в пользовательском интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="a2023-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="a2023-642">Поддержка запросов на обслуживание для портирования локальных номеров выше 999.</span><span class="sxs-lookup"><span data-stu-id="a2023-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="a2023-643">Руководство по прямой маршрутике:</span><span class="sxs-lookup"><span data-stu-id="a2023-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-644">Руководство по настройке организации для разработки сценариев с размещением партнеров или сценариев, развернутых клиентами, для 10 сайтов.</span><span class="sxs-lookup"><span data-stu-id="a2023-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="a2023-645">Обзор конфигурации пограничного контроллера сеанса (SBC).</span><span class="sxs-lookup"><span data-stu-id="a2023-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="a2023-646">Удаленная помощь с конфигурацией плана набора номеров.</span><span class="sxs-lookup"><span data-stu-id="a2023-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="a2023-647">Конфигурация голосового маршрута.</span><span class="sxs-lookup"><span data-stu-id="a2023-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="a2023-648">Обход мультимедиа и оптимизация локальных средств массовой информации.</span><span class="sxs-lookup"><span data-stu-id="a2023-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="a2023-649">Включение прямых трансляций Teams.</span><span class="sxs-lookup"><span data-stu-id="a2023-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="a2023-650">Настройка организации и интеграция в Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="a2023-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="a2023-651">Руководство по переходу Skype для бизнеса на teams.</span><span class="sxs-lookup"><span data-stu-id="a2023-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a2023-652">Удостоверения, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-653">Пользователи, для которых включен SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="a2023-654">Почтовые ящики Exchange присутствуют (онлайн и локально в гибридной конфигурации Exchange).</span><span class="sxs-lookup"><span data-stu-id="a2023-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="a2023-655">Включено для групп Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="a2023-656">
  <strong>Примечание:</strong> Если пользователям не назначены и не включены лицензии SharePoint Online, у них не будет хранилища OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="a2023-657">Общий доступ к файлам продолжает работать в Channels, но пользователи не могут обмениваться файлами в чатах без хранения OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="a2023-658">Команды не поддерживают локальное участие в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a2023-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="a2023-659">
  <strong>Примечание:</strong> Идеальное состояние для всех пользователей, чтобы их почтовые ящики были дома в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="a2023-660">Пользователи с почтовыми ящиками, в которые есть локальное помещение, должны синхронизировать свои удостоверения с каталогом Office 365 через Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="a2023-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="a2023-661">Для этих гибридных клиентов Exchange, если почтовый ящик пользователя является локальной, пользователь не может добавлять или настраивать соединители.</span><span class="sxs-lookup"><span data-stu-id="a2023-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="a2023-662">Установщики клиентов Microsoft Teams для настольных компьютеров Windows и Mac можно скачать на странице <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="a2023-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="a2023-663"><strong>Outlook для iOS и Android</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="a2023-664">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-665">Скачивание Outlook для iOS и Android через Apple App Store или Google Play.</span><span class="sxs-lookup"><span data-stu-id="a2023-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="a2023-666">Настройка учетных записей и оценка почтового ящика Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="a2023-667">Защита мобильных устройств Outlook (дополнительные сведения см. <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">в рублях Securing Outlook для iOS</a> и Android в Exchange Online).</span><span class="sxs-lookup"><span data-stu-id="a2023-667">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="a2023-668">Удостоверения, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-669">Выполнена настройка Exchange Online, назначены соответствующие лицензии.</span><span class="sxs-lookup"><span data-stu-id="a2023-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="a2023-671">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-672">Назначение лицензий на Power BI.</span><span class="sxs-lookup"><span data-stu-id="a2023-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="a2023-673">Развертывание приложения Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="a2023-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a2023-674">Программное обеспечение клиента в Интернете, например Power BI Desktop, должно быть на минимальном уровне, определенном в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="a2023-676">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-677">Проверка основных функций SharePoint, необходимых для работы Project Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="a2023-678">Добавление службы Project Online в клиент (в том числе добавление подписок для пользователей).</span><span class="sxs-lookup"><span data-stu-id="a2023-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="a2023-679">Настройка пула корпоративных ресурсов (ERP).</span><span class="sxs-lookup"><span data-stu-id="a2023-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="a2023-680">Создание первого проекта.</span><span class="sxs-lookup"><span data-stu-id="a2023-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a2023-681">Программное обеспечение клиента в Интернете, например Project for Office 365, должно быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-682"><strong>Project Online Professional и Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="a2023-683">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-684">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="a2023-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="a2023-685">Назначение пользователям лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a2023-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="a2023-686">Установка клиента Project Online для настольных ПК с использованием портала Office 365 и технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="a2023-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="a2023-687">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a2023-688">Настройка одного внутреннего сервера распространения для клиента Project Online для настольных ПК, в том числе помощь по созданию файла configuration.xml для его последующего использования в средстве развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="a2023-689">Подключение клиента Project Online для настольных ПК к Project Online профессиональный или Project Online расширенный.</span><span class="sxs-lookup"><span data-stu-id="a2023-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="a2023-690">Программное обеспечение клиента в Интернете, например Project for Office 365, должно быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-691"><strong>SharePoint Online и OneDrive для бизнеса</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="a2023-692">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-693">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="a2023-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="a2023-694">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="a2023-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="a2023-695">Подготовка пользователей и лицензий.</span><span class="sxs-lookup"><span data-stu-id="a2023-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="a2023-696">Создание сайтов для администратора SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="a2023-697">Планирование семейств веб-сайтов.</span><span class="sxs-lookup"><span data-stu-id="a2023-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="a2023-698">Защита контента и управление разрешениями.</span><span class="sxs-lookup"><span data-stu-id="a2023-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="a2023-699">Настройка функций SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="a2023-700">Настройка функций гибридной среды SharePoint, таких как гибридный поиск, гибридные сайты, гибридная таксономия, типы контента, гибридная функция самостоятельного создания сайтов (только для SharePoint Server 2013), расширенное средство запуска приложений, гибридная служба OneDrive для бизнеса и сайты экстрасети.</span><span class="sxs-lookup"><span data-stu-id="a2023-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="a2023-701">Подход к миграции.</span><span class="sxs-lookup"><span data-stu-id="a2023-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="a2023-702">Дополнительные рекомендации предоставляются для OneDrive для бизнеса в зависимости от версии SharePoint, например:</span><span class="sxs-lookup"><span data-stu-id="a2023-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-703">Определение параметров интеграции и проверка локальной и сетевой инфраструктуры и пропускной способности сети.</span><span class="sxs-lookup"><span data-stu-id="a2023-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="a2023-704">Установка SharePoint Online 2013 SP1 (если применимо), планирование и реализация требований синхронизации и удостоверений, а также определение клиента синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a2023-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="a2023-705">Планирование и реализация единого внедрения для всех пользователей (или поэтапного внедрения).</span><span class="sxs-lookup"><span data-stu-id="a2023-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="a2023-706">Назначение лицензий, перенаправление сайтов и библиотек персональных документов в Office 365 (применимо к SharePoint Online 2013), настройка аудиторий для управления доступом к OneDrive (применимо к SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="a2023-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="a2023-707">Перенаправление или перемещение известных папок в OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a2023-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="a2023-708">Развертывание клиентской синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="a2023-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="a2023-709">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="a2023-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="a2023-710">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="https://docs.microsoft.com/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="a2023-711"><strong>Гибрид SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="a2023-712">Гибридная конфигурация SharePoint включает настройку гибридного поиска, сайтов, таксономии, типов контента, OneDrive для бизнеса, расширенной пусковой системы приложений, сайтов экстрасетей и создания сайтов самообслуживания, подключенных из локальной среды в единую целевую среду SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a2023-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="a2023-713">
  <strong>Примечание:</strong> Создание сайтов самообслуживания не имеет возможности для локального сервера под управлением SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="a2023-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="a2023-714">Чтобы включить гибрид SharePoint, необходимо иметь одну из следующих локальной сред SharePoint Server: 2013, 2016 или 2019.</span><span class="sxs-lookup"><span data-stu-id="a2023-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="a2023-715">
  <strong>Примечание:</strong> Обновление локальной среды SharePoint до SharePoint Server не является областью действия.</span><span class="sxs-lookup"><span data-stu-id="a2023-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="a2023-716">Обратитесь за <a href="https://go.microsoft.com/fwlink/?linkid=2080150">помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="a2023-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="a2023-717">Дополнительные сведения см. в раздел <a href="https://go.microsoft.com/fwlink/?linkid=853548">Минимальные уровни общедоступных обновлений для гибридных функций SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="a2023-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="a2023-718">
  <strong>Примечание:</strong> Сведения о возможностях multi-Geo см. в <a href="https://go.microsoft.com/fwlink/?linkid=831056">разделе Multi-Geo Capabilities in OneDrive и SharePoint Online в Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="a2023-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-719"><strong>Yammer корпоративный</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="a2023-720">Мы предоставляем удаленные рекомендации для включения службы Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="a2023-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="a2023-721">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, как это определено в требованиях системы <a href="https://go.microsoft.com/fwlink/?LinkID=723597">для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="a2023-722">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="a2023-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-723"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-724"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-725"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a2023-726"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="a2023-727">Дополнительные сведения см. в <strong>видеороликах Azure Active Directory (Azure AD)</strong> и Azure AD Premium в <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия требованиям.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a2023-728"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="a2023-728"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="a2023-729">Дополнительные сведения о защите информации Azure см. в <strong>веб-сайте Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Security and Compliance.</span><span class="sxs-lookup"><span data-stu-id="a2023-729">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="a2023-730"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-730"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="a2023-731">Дополнительные сведения см. <strong> в веб-сайте Microsoft Intune</strong> в <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-731">For more information, see <strong> Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="a2023-732">Windows 10</span><span class="sxs-lookup"><span data-stu-id="a2023-732">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-733"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-733"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-734"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-734"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-735"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-735"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a2023-736"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-736"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="a2023-737">Мы предоставляем рекомендации по обновлению с Windows 7 Профессиональная и Windows 8.1 Professional до Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="a2023-737">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="a2023-738">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-738">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-739">Понимание намерения Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-739">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="a2023-740">Оценка исходных сред и требований (убедитесь, что Microsoft Endpoint Configuration Manager обновляется до необходимого уровня для поддержки развертывания Windows 10).</span><span class="sxs-lookup"><span data-stu-id="a2023-740">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="a2023-741">Развертывание приложений Windows 10 Enterprise и Microsoft 365 с помощью Microsoft Endpoint Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-741">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="a2023-742">Рекомендации по оценке приложений с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-742">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="a2023-743">Включение использования desktop Analytics и руководства путем создания плана развертывания Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="a2023-743">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="a2023-744">Оценка совместимости Приложений Microsoft 365 с помощью панели мониторинга готовности Office 365 в Configuration Manager или с автономным набор средств для Office плюс помощь в развертывании приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-744">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="a2023-745">Создание контрольного списка исправлений для того, что необходимо сделать, чтобы привести исходные среды к минимальным требованиям для успешного развертывания.</span><span class="sxs-lookup"><span data-stu-id="a2023-745">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="a2023-746">Предоставление рекомендаций по обновлению существующих устройств в Windows 10 Enterprise, если они соответствуют необходимым требованиям оборудования устройств.</span><span class="sxs-lookup"><span data-stu-id="a2023-746">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="a2023-747">Предоставление рекомендаций по обновлению для поддержки существующего развертывания.</span><span class="sxs-lookup"><span data-stu-id="a2023-747">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="a2023-748">FastTrack предоставляет рекомендации и инструкции по обновлению до Windows 10 на месте.</span><span class="sxs-lookup"><span data-stu-id="a2023-748">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="a2023-749">Кроме того, предоставляются инструкции по установке чистых образов Windows и для сценариев развертывания Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="a2023-749">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="a2023-750">Развертывание приложений Microsoft 365 с помощью configuration Manager в рамках развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-750">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="a2023-751">Предоставление рекомендаций, которые помогут вашей организации оставаться в курсе windows 10 Enterprise и Microsoft 365 Apps с помощью существующей среды Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-751">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="a2023-752">
  
<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-752">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a2023-753">Обновление Configuration Manager до Current Branch.</span><span class="sxs-lookup"><span data-stu-id="a2023-753">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="a2023-754">Создание настраиваемых образов для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-754">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="a2023-755">Создание и поддержка сценариев для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-755">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="a2023-756">Переход с BIOS на UEFI в системах с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-756">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="a2023-757">Включение функций безопасности Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-757">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="a2023-758">Настройка служб развертывания Windows (WDS) для загрузки с помощью протокола удаленной загрузки (PXE).</span><span class="sxs-lookup"><span data-stu-id="a2023-758">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="a2023-759">Запись и развертывание образов Windows 10 с помощью набора средств Microsoft Deployment Toolkit (MDT).</span><span class="sxs-lookup"><span data-stu-id="a2023-759">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="a2023-760">Использование средства миграции пользовательской среды (USMT).</span><span class="sxs-lookup"><span data-stu-id="a2023-760">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="a2023-761">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="a2023-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="a2023-762">Для обновления ПК должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="a2023-762">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-763">Ос-код источника: Windows 7 Корпоративная или Профессиональный, Windows 8.1 Корпоративная или Профессиональная.</span><span class="sxs-lookup"><span data-stu-id="a2023-763">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="a2023-764">Устройства: рабочий стол, записная книжка или форм-фактор планшета.</span><span class="sxs-lookup"><span data-stu-id="a2023-764">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="a2023-765">Целевая ОС: Окно 10 Корпоративная.</span><span class="sxs-lookup"><span data-stu-id="a2023-765">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="a2023-766">Для обновления инфраструктуры должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="a2023-766">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-767">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="a2023-767">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="a2023-768">Версия Configuration Manager должна поддерживаться целевой версией Windows 10.</span><span class="sxs-lookup"><span data-stu-id="a2023-768">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="a2023-769">Дополнительные сведения см. в таблице поддержки Configuration Manager в статье <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Поддержка Windows 10 в Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="a2023-769">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="a2023-770"><strong>Microsoft Defender для конечной точки</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-770"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="a2023-771">Дополнительные сведения см. в <strong> веб-сайте Microsoft Defender для конечной точки</strong> в <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">области безопасности и соответствия</a>требованиям.</span><span class="sxs-lookup"><span data-stu-id="a2023-771">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="a2023-772">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="a2023-772">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-773"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-773"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-774"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-774"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-775"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-775"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a2023-776"><strong>Виртуальный рабочий стол Windows</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-776"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="a2023-777">Мы предоставляем рекомендации по развертыванию для внедрения в Windows Virtual Desktop (служба виртуализации настольных компьютеров и приложений).</span><span class="sxs-lookup"><span data-stu-id="a2023-777">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="a2023-778">Виртуальный рабочий стол Windows 10 с несколькими сеансами и оптимизирован для Microsoft 365 Apps для предприятия с интегрированной безопасностью и управлением для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-778">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="a2023-779">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="a2023-779">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="a2023-780">Развертывание среды виртуальных настольных компьютеров Windows с несколькими сеансами Windows 10 Корпоративный и Microsoft 365 Apps для предприятия с помощью следующих ниже.</span><span class="sxs-lookup"><span data-stu-id="a2023-780">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="a2023-781">Azure Marketplace Image.</span><span class="sxs-lookup"><span data-stu-id="a2023-781">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="a2023-782">Общий образ.</span><span class="sxs-lookup"><span data-stu-id="a2023-782">Shared image.</span></span></li>
<li><span data-ttu-id="a2023-783">Развертывание office набор средств (ODT).</span><span class="sxs-lookup"><span data-stu-id="a2023-783">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="a2023-784">Настройка FSLogix:</span><span class="sxs-lookup"><span data-stu-id="a2023-784">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="a2023-785">Развертывание агента FSLogix с контейнером профилей.</span><span class="sxs-lookup"><span data-stu-id="a2023-785">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="a2023-786">Развертывание агента FSLogix с контейнером Office.</span><span class="sxs-lookup"><span data-stu-id="a2023-786">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="a2023-787">Настройка папки FSLogix с исключениями контента.</span><span class="sxs-lookup"><span data-stu-id="a2023-787">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="a2023-788">Развертывание Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="a2023-788">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="a2023-789">Развертывание Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="a2023-789">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="a2023-790">Подключение с помощью клиентов Виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-790">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="a2023-791">

<strong>Ниже приводится неосякаемая область</strong>
</span><span class="sxs-lookup"><span data-stu-id="a2023-791">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="a2023-792">Управление проектами развертывания виртуального рабочего стола клиента с Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-792">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="a2023-793">Виртуализация и развертывание сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-793">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="a2023-794">Настраиваемые изображения.</span><span class="sxs-lookup"><span data-stu-id="a2023-794">Custom images.</span></span></li>
<li><span data-ttu-id="a2023-795">Миграции и сценарии с участием VMware и Citrix.</span><span class="sxs-lookup"><span data-stu-id="a2023-795">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="a2023-796">Сценарии Linux.</span><span class="sxs-lookup"><span data-stu-id="a2023-796">Linux scenarios.</span></span></li>
<li><span data-ttu-id="a2023-797">Преобразование или миграция профилей пользователей.</span><span class="sxs-lookup"><span data-stu-id="a2023-797">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="a2023-798">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="a2023-798">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="a2023-799">У вас уже должно быть следующее:</span><span class="sxs-lookup"><span data-stu-id="a2023-799">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="a2023-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Требования к лицензированию виртуальных настольных компьютеров</a>Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="a2023-801">Сеть Azure:</span><span class="sxs-lookup"><span data-stu-id="a2023-801">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="a2023-802">Создание и подсети виртуальной сети (VNET).</span><span class="sxs-lookup"><span data-stu-id="a2023-802">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="a2023-803">Брандмауэр и группы сетевой безопасности.</span><span class="sxs-lookup"><span data-stu-id="a2023-803">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="a2023-804">VPN и ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="a2023-804">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="a2023-805">Маршрутная маршрутивка в Azure из локального помещения.</span><span class="sxs-lookup"><span data-stu-id="a2023-805">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="a2023-806">Правила брандмауэра, позволяющие подключаться к Виртуальному рабочему столу Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-806">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="a2023-807">Дополнительные сведения см. в <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">веб-версии Поддерживаемые клиенты удаленного рабочего стола.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-807">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="a2023-808">Общая настройка Azure AD:</span><span class="sxs-lookup"><span data-stu-id="a2023-808">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="a2023-809">Стратегия <i>удостоверения (можно использовать только один из следующих трех вариантов):</i>
</span><span class="sxs-lookup"><span data-stu-id="a2023-809">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="a2023-810">Active Directory с Azure AD Connect в Azure.</span><span class="sxs-lookup"><span data-stu-id="a2023-810">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="a2023-811">Active Directory с локальной сетью Azure AD Connect через VPN или ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="a2023-811">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="a2023-812">Службы домена Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="a2023-812">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="a2023-813">App Assure</span><span class="sxs-lookup"><span data-stu-id="a2023-813">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-814"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-814"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-815"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-815"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-816"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-816"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a2023-817"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-817"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="a2023-818">App Assure — это служба, предназначенная для решения проблем с совместимостью приложений Windows 10 и Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="a2023-818">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="a2023-819">При запросе службы App Assure мы работаем с вами для решения проблем с допустимым приложением без каких-либо дополнительных затрат для вас с помощью доступной подписки.</span><span class="sxs-lookup"><span data-stu-id="a2023-819">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="a2023-820">Мы также предоставляем рекомендации для клиентов, сталкивающихся с вопросами совместимости при развертывании Windows Virtual Desktop и Microsoft Edge, и прилоя все разумные усилия для решения проблем совместимости.</span><span class="sxs-lookup"><span data-stu-id="a2023-820">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="a2023-821">Мы предоставляем помощь в исправлении приложений, развернутых в следующих продуктах Майкрософт:</span><span class="sxs-lookup"><span data-stu-id="a2023-821">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="a2023-822"><strong>Windows 10 </strong> (включая устройства ARM64)</span><span class="sxs-lookup"><span data-stu-id="a2023-822"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="a2023-823"><strong>Приложения Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="a2023-823"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="a2023-824"><strong>Microsoft Edge —</strong> Сведения о развертывании <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">см. в обзоре каналов Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-824"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="a2023-825"><strong>Виртуальный рабочий стол Windows</strong> - Дополнительные сведения см. в дополнительных сведениях о том, что такое <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">виртуальный настольный компьютер Windows?</a> и много сеансов <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">для Windows 10 Enterprise.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-825"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="a2023-826">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-826">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="a2023-p137">Изучение и тестирование приложения с целью определения того, какие функции поддерживаются и не поддерживаются в Windows 10 и приложениях Microsoft 365. Дополнительные руководства по этому процессу см. на странице <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Центр развертывания компьютеров</a>. Если вас интересует глубокая оценка готовности к обновлению, заполните форму <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Запрос клиента на оценку современных компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="a2023-p137">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="a2023-830">Анализ приложений независимых поставщиков программного обеспечения (ISV) на совместимость с Windows 10 и сведений о поддержке.</span><span class="sxs-lookup"><span data-stu-id="a2023-830">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="a2023-831">Дополнительные сведения см. в разделе <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Аналитика компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="a2023-831">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="a2023-832">Услуги по упаковке приложений.</span><span class="sxs-lookup"><span data-stu-id="a2023-832">App packaging-only services.</span></span> <span data-ttu-id="a2023-833">Команда App Assure упаковывает приложения, исправленные для Windows 10, чтобы обеспечить возможность их развертывания в среде клиента.</span><span class="sxs-lookup"><span data-stu-id="a2023-833">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="a2023-834">

<strong>Обязанности клиента включают в себя</strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-834">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="a2023-835">Создание ведомости приложения</span><span class="sxs-lookup"><span data-stu-id="a2023-835">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="a2023-836">Проверки работы данных приложений в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-836">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="a2023-837">
<strong>Примечание:</strong>  Корпорация Майкрософт не может вносить изменения в исходный код.</span><span class="sxs-lookup"><span data-stu-id="a2023-837">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="a2023-838">Однако команда App Assure предоставляет руководство для разработчиков приложений, если для приложений доступен исходный код.</span><span class="sxs-lookup"><span data-stu-id="a2023-838">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="a2023-839">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="a2023-839">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="a2023-840"><strong>Windows 10 и Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="a2023-840"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-841">Приложения, работающие в Windows 7, Windows 8,1, Office 2010 и Office 2013, также работают в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a2023-841">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="a2023-842">
<strong>Windows 10 на ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="a2023-842">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="a2023-843">Приложения, которые работали в Windows 7, Office 2010 или более поздних версиях, также работают на устройствах с Windows 10 и Microsoft 365 Apps на устройствах ARM64.</span><span class="sxs-lookup"><span data-stu-id="a2023-843">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="a2023-844">
  <strong>Примечание:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="a2023-844">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="a2023-845">Эмуляция x64 (64-bit) доступна в предварительном режиме для клиентов, участвующих в <a href="https://insider.windows.com/">программе предварительного просмотра Windows.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-845">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="a2023-846">Для пользователей, не использующих Windows Insider в Windows 10 версии 2004 (или более поздней версии), photoshop ARM64 поддерживается с помощью <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">пакета совместимости OpenCL и OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-846">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="a2023-847">Пользователи программы инсайдерской windows могут скачать внутреннюю версию пакета совместимости OpenCL и OpenGL для использования с дополнительными приложениями.</span><span class="sxs-lookup"><span data-stu-id="a2023-847">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="a2023-848">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="a2023-848">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-849">Если веб-приложения или сайты работают в Internet Explorer 11, поддерживаемых версиях Google Chrome или любой версии Microsoft Edge, они также будут работать с Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="a2023-849">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-850">Поскольку веб-сайт постоянно развивается, обязательно просмотрите опубликованный список известных изменений, которые влияют на совместимость <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">веб-сайтов для Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="a2023-850">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="a2023-851">
  <strong>Виртуальный рабочий стол Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-851">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="a2023-852">Виртуализованные приложения, работающие на узле сеансов удаленных рабочих столов в Windows Server, также работают в Windows 10 Корпоративная с поддержкой нескольких сеансов в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-852">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-853">Приложения, работающие в любой среде виртуальной инфраструктуры настольных компьютеров Windows 7 или Windows 10, также работают на Windows 7 Корпоративная и Windows 10 Enterprise в рамках Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="a2023-853">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-854">Приложения, работающие на клиентских устройствах Windows 7 или Windows 10, также работают в Windows 7 Корпоративная и Windows 10 Корпоративная в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-854">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="a2023-855">
  <strong>Примечание:</strong> Исключения и ограничения совместимости с несколькими сеансами Windows 10 Enterprise включают следующие:</span><span class="sxs-lookup"><span data-stu-id="a2023-855">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="a2023-856">Ограниченное перенаправление оборудования.</span><span class="sxs-lookup"><span data-stu-id="a2023-856">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-857">Приложения с интенсивным использованием A/V могут работать с уменьшенной производительностью.</span><span class="sxs-lookup"><span data-stu-id="a2023-857">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="a2023-858">16-разрядные приложения не поддерживаются в 64-разрядных виртуальных рабочих столах Windows.</span><span class="sxs-lookup"><span data-stu-id="a2023-858">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="a2023-859">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="a2023-859">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a2023-860"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-860"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="a2023-861"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-861"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="a2023-862"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="a2023-862"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="a2023-863"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="a2023-863"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="a2023-864">Мы предоставляем рекомендации по удаленному развертыванию и принятию и совместимости для:</span><span class="sxs-lookup"><span data-stu-id="a2023-864">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="a2023-865">Развертывание Microsoft Edge в Windows 10 с помощью Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager или Intune).</span><span class="sxs-lookup"><span data-stu-id="a2023-865">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="a2023-866">Настройка Microsoft Edge (с помощью групповых политик или конфигурации приложений Intune и политик приложений).</span><span class="sxs-lookup"><span data-stu-id="a2023-866">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="a2023-867">Инвентаризация списка сайтов, которые могут потребовать использования в режиме Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="a2023-867">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="a2023-868">Включение режима Internet Explorer в существующем списке корпоративных сайтов.</span><span class="sxs-lookup"><span data-stu-id="a2023-868">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="a2023-869">(Дополнительные сведения см. в <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">странице Engaging FastTrack).</a></span><span class="sxs-lookup"><span data-stu-id="a2023-869">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="a2023-870">Кроме того, если у вас есть веб-приложение или сайт, который работает с Internet Explorer или Google Chrome и вы испытываете проблемы с совместимостью, мы предоставляем рекомендации по устранению проблемы без дополнительных затрат.</span><span class="sxs-lookup"><span data-stu-id="a2023-870">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="a2023-871">Чтобы запросить поддержку совместимости для App Assure, вопишитесь на портал <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack,</a> чтобы начать взаимодействие.</span><span class="sxs-lookup"><span data-stu-id="a2023-871">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="a2023-872">Планирование руководства по внедрению edge и настройке закладки Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="a2023-872">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="a2023-873">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="a2023-873">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="a2023-874">Управление проектами по развертыванию Microsoft Edge для клиентов.</span><span class="sxs-lookup"><span data-stu-id="a2023-874">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="a2023-875">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="a2023-875">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
