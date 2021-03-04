---
title: Продукты и возможности
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и ожиданиях исходных сред, необходимых перед началом работы. На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.
ms.openlocfilehash: 05936adee3f21e6078933a686dfa8dc24c33d1be
ms.sourcegitcommit: cf630a48697177b9cce6c0fbc67a7e7a0b752167
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416568"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="e6590-104">Продукты и возможности</span><span class="sxs-lookup"><span data-stu-id="e6590-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="e6590-105">Службы и сценарии, поддерживаемые FastTrack</span><span class="sxs-lookup"><span data-stu-id="e6590-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="e6590-106">В этом разделе содержатся сведения о сценариях рабочей нагрузки, поддерживаемых FastTrack, и ожиданиях исходных сред, необходимых перед началом работы.</span><span class="sxs-lookup"><span data-stu-id="e6590-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="e6590-107">На основе текущей настройки мы работаем с вами над созданием плана восстановления, который соответствует минимальным требованиям для успешной работы с бортовой установкой.</span><span class="sxs-lookup"><span data-stu-id="e6590-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="e6590-108">FastTrack предоставляет рекомендации, которые помогут вам сначала с основными возможностями (общими для всех Microsoft Online Services), а затем с помощью вовсю каждой подходящих служб:</span><span class="sxs-lookup"><span data-stu-id="e6590-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="e6590-109">Общие</span><span class="sxs-lookup"><span data-stu-id="e6590-109">General</span></span>](#general)
  - [<span data-ttu-id="e6590-110">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="e6590-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="e6590-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="e6590-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="e6590-112">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="e6590-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="e6590-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="e6590-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="e6590-114">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="e6590-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="e6590-115">Служба Assure для приложений</span><span class="sxs-lookup"><span data-stu-id="e6590-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="e6590-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="e6590-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="e6590-117">Сведения о требованиях к исходной среде для Office 365 для государственных организаций США см. в статье [Требования к исходной среде для Office 365 для государственных организаций США](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span><span class="sxs-lookup"><span data-stu-id="e6590-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="e6590-118">Общие</span><span class="sxs-lookup"><span data-stu-id="e6590-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-119"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-120"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-121"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e6590-122"><strong>Базовое подключение</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="e6590-123">Мы предоставляем удаленные рекомендации по основной интеграции, которая включает в себя подготовка службы, клиент и интеграцию удостоверений.</span><span class="sxs-lookup"><span data-stu-id="e6590-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="e6590-124">Она также включает шаги по обеспечению основы для бортовых служб, таких как Exchange Online, SharePoint Online и Microsoft Teams, включая обсуждение вопросов <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">безопасности,</a>подключения к сети и соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="e6590-125">Подключение одной или нескольких поддерживаемых служб можно начать после завершения базового подключения.</span><span class="sxs-lookup"><span data-stu-id="e6590-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="e6590-126"></li>
</ul>  

<strong> Интеграция удостоверений </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="e6590-127">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="e6590-128">Подготовка локального удостоверения Active Directory для синхронизации с Azure Active Directory (Azure AD), включая установку и настройку Azure AD Connect (одно- или нескольких лесов) и лицензирование (включая лицензирование на основе групп).</span><span class="sxs-lookup"><span data-stu-id="e6590-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="e6590-129">Создание облачных удостоверений, включая массовый импорт и лицензирование, включая использование группового лицензирования.</span><span class="sxs-lookup"><span data-stu-id="e6590-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="e6590-130">Выбор и включение правильного метода проверки подлинности для облачного путешествия, синхронизация хеш-паролей, сквозная проверка подлинности или службы Федерации Active Directory (AD FS).</span><span class="sxs-lookup"><span data-stu-id="e6590-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="e6590-131">Включение AD FS для клиентов с одним лесом Active Directory и удостоверениями, синхронизированными с средством Подключения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="e6590-132">Для этого требуется Windows Server 2012 R2 Active Directory Federation Services 2.0 или более.</span><span class="sxs-lookup"><span data-stu-id="e6590-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="e6590-133">Перенос проверки подлинности из AD FS в Azure AD с помощью синхронизации с использованием хаширования паролей или сквозной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="e6590-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="e6590-134">Перенос предварительно интегрированных приложений (например, приложений azure AD gallery software-as-a-service (SaaS) из AD FS в Azure AD для единого входного (SSO).</span><span class="sxs-lookup"><span data-stu-id="e6590-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="e6590-135">Включение интеграции приложений SaaS с SSO из галереи Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="e6590-136">Включение автоматической подготовки пользователей для предварительно интегрированных приложений <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"></a> SaaS, указанных в списке учебников по интеграции приложений (ограниченных приложениями SaaS-галереи Azure AD и только исходящие подготовки).</span><span class="sxs-lookup"><span data-stu-id="e6590-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="e6590-137"><strong>Включить сеть </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="e6590-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="e6590-138">В рамках преимущества FastTrack мы советуем вам рекомендации по подключению к облачным службам для обеспечения максимальной производительности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="e6590-139"><strong>Леса Active Directory</strong> Они имеют функциональный лесной уровень, установленный для Windows Server 2003 и далее, с следующей конфигурацией леса:</span><span class="sxs-lookup"><span data-stu-id="e6590-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-140">Один лес Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e6590-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="e6590-141">Топологии с одним лесом учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="e6590-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-142">Топологии с несколькими лесами учетных записей Active Directory и лесом ресурсов (Exchange или Lync 2010, Lync 2013 или Skype для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="e6590-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-143">Несколько лесов учетных записей Active Directory, один из которых является централизованным лесом учетных записей Active Directory, включающим Exchange и/или Lync 2010, Lync 2013 или Skype для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="e6590-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="e6590-144">Несколько лесов учетных записей Active Directory, каждый из которых включает свою организацию Exchange.</span><span class="sxs-lookup"><span data-stu-id="e6590-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="e6590-145">Задачи, необходимые для конфигурации клиента и интеграции с Azure Active Directory, если это необходимо.</span><span class="sxs-lookup"><span data-stu-id="e6590-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="e6590-146">
  <strong>Важно</strong>  </span><span class="sxs-lookup"><span data-stu-id="e6590-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="e6590-147">Для многолесных сценариев Active Directory, если развернуты Lync 2010, Lync 2013 или Skype для бизнеса, его необходимо развернуть в том же лесу Active Directory, что и Exchange.</span><span class="sxs-lookup"><span data-stu-id="e6590-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="e6590-148">При реализации нескольких лесов Active Directory с несколькими организациями Exchange в гибридной конфигурации Exchange пространства имен общего имени пользователя (UPN) между исходными лесами не поддерживаются.</span><span class="sxs-lookup"><span data-stu-id="e6590-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="e6590-149">Основные пространства имен SMTP между организациями Exchange также должны быть отдельными.</span><span class="sxs-lookup"><span data-stu-id="e6590-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="e6590-150">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/?linkid=845444">гибридных развертываниях с несколькими лесами Active Directory.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="e6590-151">Для всех конфигураций нескольких лесов развертывание служб Федерации Active Directory (AD FS) выходит за рамки.</span><span class="sxs-lookup"><span data-stu-id="e6590-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="e6590-152">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-153"><strong>Приложения Microsoft 365</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="e6590-154">Мы предоставляем рекомендации по удаленному развертыванию для:</span><span class="sxs-lookup"><span data-stu-id="e6590-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-155">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="e6590-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="e6590-156">Назначение пользователям и устройствам лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="e6590-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="e6590-157">Установка приложений Microsoft 365 с портала Office 365 с помощью технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="e6590-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="e6590-158">Установка приложений Office Mobile (например, Outlook Mobile, Word Mobile, Excel Mobile и PowerPoint Mobile) на устройствах с iOS или Android.</span><span class="sxs-lookup"><span data-stu-id="e6590-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="e6590-159">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e6590-160">Выбор и настройка локальной или облачной установки.</span><span class="sxs-lookup"><span data-stu-id="e6590-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="e6590-161">Создание XML-файла конфигурации средства развертывания Office с помощью центра развертывания Office или встроенного XML-файла для настройки пакета развертывания.</span><span class="sxs-lookup"><span data-stu-id="e6590-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="e6590-162">Развертывание с помощью Microsoft Endpoint Configuration Manager, а также создание пакета Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="e6590-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="e6590-163">Кроме того, если у вас есть макрос или надстройка, которая работала с предшествующими версиями Office и у вас проблемы с совместимостью, мы предоставляем рекомендации по исправлению проблемы совместимости без дополнительных затрат с помощью программы App Assure.</span><span class="sxs-lookup"><span data-stu-id="e6590-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="e6590-164">Дополнительные сведения см. в части App <strong>Assure</strong> в <a href="#windows-10">Windows 10.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e6590-165">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, как это определено в требованиях системы <a href="https://go.microsoft.com/fwlink/?LinkID=723597">для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-166"><strong>Сетевое здоровье</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="e6590-167">Мы предоставляем удаленные рекомендации по получению и интерпретации данных подключения к ключевым сетям из среды, показывающие соответствие сайтов организации принципам сетевого подключения Корпорации <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">Майкрософт.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="e6590-168">Это подчеркивает оценку сети, которая напрямую влияет на скорость миграции, пользовательский опыт, производительность службы и надежность.</span><span class="sxs-lookup"><span data-stu-id="e6590-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="e6590-169">Мы также поможем вам с помощью любых действий по исправлению последствий, которые будут выделены в этих данных, чтобы помочь вам улучшить оценку сети.</span><span class="sxs-lookup"><span data-stu-id="e6590-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="e6590-170">Доступ к Центру администрирования Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="e6590-171">Требуются новые версии приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="e6590-172">Службы расположения, включенные в качестве рекомендаций по производительности Сети в Центре администрирования <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 (предварительный просмотр).</a></span><span class="sxs-lookup"><span data-stu-id="e6590-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="e6590-173">Безопасность и соответствие требованиям</span><span class="sxs-lookup"><span data-stu-id="e6590-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-174"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-175"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-176"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="e6590-177"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="e6590-178">Мы предоставляем удаленные рекомендации по обеспечению безопасности облачных удостоверений для следующих сценариев.</span><span class="sxs-lookup"><span data-stu-id="e6590-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="e6590-179">

<strong>Безопасная инфраструктура фундамента</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="e6590-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="e6590-180">Настройка и включение сильной проверки подлинности для удостоверений, включая защиту с помощью многофакторной проверки подлинности Azure (только в облаке), приложения Microsoft Authenticator и комбинированной регистрации для azure MFA и сброса паролей самообслуживаемых (SSPR).</span><span class="sxs-lookup"><span data-stu-id="e6590-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="e6590-181">Для клиентов, не использующих Azure AD Premium, предоставляются рекомендации по обеспечению безопасности удостоверений с помощью по умолчанию безопасности.</span><span class="sxs-lookup"><span data-stu-id="e6590-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="e6590-182">Для премиум-клиентов Azure AD предоставляются рекомендации по обеспечению безопасности удостоверений с помощью условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="e6590-183">Обнаружение и блокировка использования слабых паролей с помощью Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="e6590-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="e6590-184">Обеспечение удаленного доступа к локальному веб-приложениям с помощью прокси-сервера Приложения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="e6590-185">Включение обнаружения и устранения рисков с помощью Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="e6590-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="e6590-186">Включение настраиваемого экрана регистрации, включая логотип, текст и изображения с настраиваемым брендингом.</span><span class="sxs-lookup"><span data-stu-id="e6590-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="e6590-187">Безопасное совместное использование приложений и служб с гостевых пользователей с помощью Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="e6590-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="e6590-188">Управление доступом для администраторов Office 365 с помощью встроенных административных ролей управления доступом на основе ролей и уменьшение числа привилегированных учетных записей администратора.</span><span class="sxs-lookup"><span data-stu-id="e6590-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="e6590-189">Настройка гибридного присоединиться Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e6590-190">Настройка присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="e6590-191">
  
<strong>Мониторинг и отчетность</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-192">Включение удаленного мониторинга для AD FS, Azure AD Connect и контроллеров домена с помощью Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="e6590-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-193">
  
<strong>Управление</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-194">Управление удостоверением Azure AD и доступ к жизненному циклу в масштабе с помощью управления правами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="e6590-195">Управление членством в группах Azure AD, доступом к корпоративным приложениям и назначениями ролей с помощью обзоров доступа к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-196">Просмотр терминов использования Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-197">Управление и управление доступом к привилегированным учетным записям администратора с помощью Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="e6590-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-198">
  
<strong>Автоматизация и эффективность </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-199">Включение SSPR Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="e6590-200">Позволяет пользователям создавать и управлять собственными группами облачной безопасности или Office 365 с помощью управления группами самообслуживки Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-201">Управление делегированием доступа к корпоративным приложениям с помощью делегирования группы Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-202">Включение динамических групп Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-203">Организация приложений на портале Мои приложения с помощью коллекций.</span><span class="sxs-lookup"><span data-stu-id="e6590-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-204">Локальное active Directory и его среда были подготовлены для Azure AD Premium, включая устранение выявленных проблем, препятствуя интеграции с функциями Azure AD и Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="e6590-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-205"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="e6590-206">Дополнительные сведения о azure Information Protection см. в этой <strong>таблице.</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="e6590-207"><strong>Ответ & обнаружения</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="e6590-208"><strong>Advanced eDiscovery</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="e6590-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="e6590-209">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="e6590-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="e6590-210">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="e6590-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="e6590-211">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="e6590-212">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="e6590-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="e6590-213"><strong>Расширенный аудит</strong> (поддерживается только в E5)</span><span class="sxs-lookup"><span data-stu-id="e6590-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="e6590-214">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-214">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="e6590-215">Включение усовершенствования аудита.</span><span class="sxs-lookup"><span data-stu-id="e6590-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="e6590-216">Выполнение пользовательского интерфейса журнала аудита поиска и основных команд powerShell аудита.</span><span class="sxs-lookup"><span data-stu-id="e6590-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="e6590-217">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-218">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-219">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-220">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-221">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-222">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-223">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-224">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="e6590-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="e6590-225">Настраиваемый сценарий или кодирование.</span><span class="sxs-lookup"><span data-stu-id="e6590-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="e6590-226">API eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="e6590-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="e6590-227">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="e6590-228">Границы соответствия требованиям и фильтры безопасности.</span><span class="sxs-lookup"><span data-stu-id="e6590-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="e6590-229">Исследования данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="e6590-230">Запросы субъекта данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="e6590-231">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-232">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-233">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="e6590-234">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="e6590-235"><strong>Управление инсайдерской угрозой</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="e6590-236">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="e6590-237">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="e6590-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="e6590-238">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="e6590-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="e6590-239">Создание дел.</span><span class="sxs-lookup"><span data-stu-id="e6590-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="e6590-240">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="e6590-241">Руководство по созданию соединиттеля кадровых ресурсов (HR).</span><span class="sxs-lookup"><span data-stu-id="e6590-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="e6590-242">

<strong> Соответствие требованиям связи </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="e6590-243">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="e6590-244">Создание политик и просмотр параметров.</span><span class="sxs-lookup"><span data-stu-id="e6590-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="e6590-245">Доступ к отчетам и оповещениям.</span><span class="sxs-lookup"><span data-stu-id="e6590-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="e6590-246">Создание шаблонов уведомлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="e6590-247">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-248">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-249">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-250">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-251">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-252">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-253">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-254">

<strong>Ниже приводится неосякаемая область </strong> 
</span><span class="sxs-lookup"><span data-stu-id="e6590-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="e6590-255">Создание и управление потоками Power Automate.</span><span class="sxs-lookup"><span data-stu-id="e6590-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="e6590-256">Соединители данных (за пределами соединитетеля управления персоналом).</span><span class="sxs-lookup"><span data-stu-id="e6590-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="e6590-257">Настраиваемые конфигурации регулярного выражения (RegEx).</span><span class="sxs-lookup"><span data-stu-id="e6590-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="e6590-258">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-259">Информационные барьеры.</span><span class="sxs-lookup"><span data-stu-id="e6590-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="e6590-260">Управление привилегированным доступом.</span><span class="sxs-lookup"><span data-stu-id="e6590-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="e6590-261">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-262">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="e6590-263">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="e6590-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="e6590-265">Microsoft 365 Defender — это единый пакет защиты предприятия до и после нарушения, который полностью координирует обнаружение, предотвращение, расследование и реагирование между конечными точками, удостоверениями, электронной почтой и приложениями для обеспечения комплексной защиты от сложных атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="e6590-266">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="e6590-267">Предоставление обзора центра безопасности Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="e6590-268">Анализ инцидентов с перекрестным продуктом, в том числе сосредоточение внимания на критически важных задачах, обеспечивая полную область атаки, влияние на активы и автоматизированные действия по исправлению, которые сгруппировали вместе.</span><span class="sxs-lookup"><span data-stu-id="e6590-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="e6590-269">Демонстрация того, как Microsoft 365 Defender может организовать исследование активов, пользователей, устройств и почтовых ящиков, которые могли быть скомпрометированы с помощью автоматического самовосстановления.</span><span class="sxs-lookup"><span data-stu-id="e6590-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="e6590-270">Объяснение и предоставление примеров того, как клиенты могут активно охотиться за попытками вторжения и действиями взлома, влияющими на вашу электронную почту, данные, устройства и учетные записи в нескольких наборах данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="e6590-271">Показывая клиентам, как они могут целостно пересматривать и улучшать свою осанку безопасности с помощью Microsoft Secure Score.</span><span class="sxs-lookup"><span data-stu-id="e6590-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="e6590-272"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="e6590-273">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="e6590-274">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="e6590-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="e6590-275">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="e6590-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="e6590-276">Исправление или интерпретация различных типов оповещений и отслеживаемой активности.</span><span class="sxs-lookup"><span data-stu-id="e6590-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="e6590-277">Изучение пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="e6590-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="e6590-278">Настраиваемая охота на угрозы.</span><span class="sxs-lookup"><span data-stu-id="e6590-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="e6590-279">Сведения о безопасности и управление событиями (SIEM) или интеграция API.</span><span class="sxs-lookup"><span data-stu-id="e6590-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="e6590-281">Microsoft Cloud App Security — это брокер облачной безопасности доступа (CASB), который обеспечивает богатую видимость, контроль над перемещениями данных и сложную аналитику для выявления и борьбы с киберугрозами во всех облачных службах Майкрософт и сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="e6590-282">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-283">Настройка портала, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="e6590-284">Импорт групп пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="e6590-285">Управление доступом и настройками администратора.</span><span class="sxs-lookup"><span data-stu-id="e6590-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="e6590-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span><span class="sxs-lookup"><span data-stu-id="e6590-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="e6590-287">Настройка ip-диапазонов и тегов.</span><span class="sxs-lookup"><span data-stu-id="e6590-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="e6590-288">Персонализация интерфейса для конечных пользователей с помощью логотипа и настраиваемого обмена сообщениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="e6590-289">Настройка облачных открытий для предоставления теневых ИТ-данных с помощью:</span><span class="sxs-lookup"><span data-stu-id="e6590-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="e6590-290">Microsoft Defender для конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="e6590-291">Zscaler.</span><span class="sxs-lookup"><span data-stu-id="e6590-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="e6590-292">iboss.</span><span class="sxs-lookup"><span data-stu-id="e6590-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="e6590-293">Подключение <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">рекомендуемых приложений с</a> помощью соединители приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="e6590-294">Настройка управления приложениями условного доступа на порталах безопасности условного доступа и облачных приложений для применения элементов управления сеансами в режиме реального времени.</span><span class="sxs-lookup"><span data-stu-id="e6590-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="e6590-295">Развертывание панелей безопасности облачных приложений и облачных открытий.</span><span class="sxs-lookup"><span data-stu-id="e6590-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="e6590-296">Настройка оценки рисков приложений в зависимости от приоритетов организации.</span><span class="sxs-lookup"><span data-stu-id="e6590-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="e6590-297">Создание тегов и категорий приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="e6590-298">Санкции и несанкционные приложения.</span><span class="sxs-lookup"><span data-stu-id="e6590-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="e6590-299">Использование журналов действий и файлов.</span><span class="sxs-lookup"><span data-stu-id="e6590-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="e6590-300">Управление приложениями OAuth.</span><span class="sxs-lookup"><span data-stu-id="e6590-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="e6590-301">Понимание корреляции инцидентов на портале Microsoft 365 Defender.</span><span class="sxs-lookup"><span data-stu-id="e6590-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="e6590-302">Предоставление помощи в настройке в <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> лучших случаях использования casBs (включая создание или обновление до шести политик) за исключением:</span><span class="sxs-lookup"><span data-stu-id="e6590-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="e6590-303">Аудит конфигурации среды интернета как среды службы (IaaS) (#18).</span><span class="sxs-lookup"><span data-stu-id="e6590-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="e6590-304">Мониторинг действий пользователей для защиты от угроз в средах IaaS (#19).</span><span class="sxs-lookup"><span data-stu-id="e6590-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="e6590-305"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="e6590-306">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="e6590-307">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="e6590-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="e6590-308">Настройка инфраструктуры, установки или развертывания автоматических загрузок журналов для непрерывных отчетов с помощью Docker или сборщика журналов.</span><span class="sxs-lookup"><span data-stu-id="e6590-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="e6590-309">Дополнительные сведения см. в <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">топ-20 случаев использования casBs.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="e6590-310">Создание отчета об обнаружении облачных данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="e6590-311">Блокировка использования приложений с помощью скриптов блоков.</span><span class="sxs-lookup"><span data-stu-id="e6590-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="e6590-312">Подключение настраиваемой программы.</span><span class="sxs-lookup"><span data-stu-id="e6590-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="e6590-313">Интеграция с сторонними поставщиками удостоверений (isPs) и поставщиками защиты от потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="e6590-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="e6590-314">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="e6590-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="e6590-315">Автоматическое исследование и исправление, включая книги Microsoft Power Automate.</span><span class="sxs-lookup"><span data-stu-id="e6590-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="e6590-316">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="e6590-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="e6590-317">Развертывание обнаружения облачных приложений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="e6590-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="e6590-318"><strong>Расширенная защита от угроз (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="e6590-319">Расширенная защита от угроз (ATP) в Microsoft Defender — это платформа, разработанная для обнаружения, предотвращения и исследования расширенных угроз в корпоративных сетях, а также для реагирования на них.</span><span class="sxs-lookup"><span data-stu-id="e6590-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="e6590-320">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-321">Развертывание технологий для защиты конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="e6590-322">Настройка профилей защиты конечной точки и ограничений устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="e6590-323">Оценка управления версиями ОС и устройствами (включая Intune, Microsoft Endpoint Configuration Manager, Объекты групповой политики (GPOs) и сторонние конфигурации), а также состояние служб av Защитник Windows или другого программного обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e6590-324">Оценка состояния служб av Windows или другого программного обеспечения безопасности конечной точки.</span><span class="sxs-lookup"><span data-stu-id="e6590-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e6590-325">Оценка прокси и брандмауэров, ограничивающих сетевой трафик.</span><span class="sxs-lookup"><span data-stu-id="e6590-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="e6590-326">Включение службы ATP Защитника Майкрософт, объясняя, как развернуть профиль агента ATP с помощью конечной точки на борту.</span><span class="sxs-lookup"><span data-stu-id="e6590-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="e6590-327">Рекомендации по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="e6590-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-328">Управление угрозами и уязвимостями.</span><span class="sxs-lookup"><span data-stu-id="e6590-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-329">Сокращение направлений атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-330">Защита нового поколения.</span><span class="sxs-lookup"><span data-stu-id="e6590-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-331">Выявление конечных точек и реагирование на них.</span><span class="sxs-lookup"><span data-stu-id="e6590-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-332">Автоматическое исследование и защита.</span><span class="sxs-lookup"><span data-stu-id="e6590-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-333">Оценка безопасности</span><span class="sxs-lookup"><span data-stu-id="e6590-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-334">Просмотр имитаций и учебных пособий (например, сценариев практики, поддельных вредоносных программ и автоматических расследований).</span><span class="sxs-lookup"><span data-stu-id="e6590-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="e6590-335">Общие сведения о функциях создания отчетов и аналитики угроз.</span><span class="sxs-lookup"><span data-stu-id="e6590-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="e6590-336">Интеграция ATP Office 365 с ATP в Microsoft Defender</span><span class="sxs-lookup"><span data-stu-id="e6590-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="e6590-337">Пошаговые руководства по поведению на портале Центра безопасности в Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="e6590-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="e6590-338">Следующие операционные системы:</span><span class="sxs-lookup"><span data-stu-id="e6590-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-339">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-340">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="e6590-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-341">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="e6590-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-342">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="e6590-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-343">Windows Server Semi-Annual (SAC) версии 1803.</span><span class="sxs-lookup"><span data-stu-id="e6590-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-344">версии macOS 10.13, 10.14 и 10.15.</span><span class="sxs-lookup"><span data-stu-id="e6590-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="e6590-345">
<strong>Примечание:</strong> Все версии Windows Server должны управляться последней версией System Center Configuration Manager 2012 (версии 1012 R2, 1511 или 1602) или Microsoft Endpoint Configuration Manager (версии 2002 или более).</span><span class="sxs-lookup"><span data-stu-id="e6590-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="e6590-346"></li>
</ul>

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-347">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="e6590-348">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="e6590-349">Текущее управление и реагирование на угрозы.</span><span class="sxs-lookup"><span data-stu-id="e6590-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="e6590-350">Подключение и настройка следующих агентов ATP в Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="e6590-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-351">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="e6590-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-352">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="e6590-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-353">Linux.</span><span class="sxs-lookup"><span data-stu-id="e6590-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-354">Мобильные устройства (Android и iOS).</span><span class="sxs-lookup"><span data-stu-id="e6590-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="e6590-355">Виртуальная инфраструктура настольных компьютеров (VDI) (сохраняемая или нестойка).</span><span class="sxs-lookup"><span data-stu-id="e6590-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-356">Бортовая и конфигурация сервера:</span><span class="sxs-lookup"><span data-stu-id="e6590-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-357">Настройка прокси-сервера для автономной связи.</span><span class="sxs-lookup"><span data-stu-id="e6590-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-358">Настройка пакетов развертывания Configuration Manager на экземплярах и версиях диспетчера конфигурации на уровне.</span><span class="sxs-lookup"><span data-stu-id="e6590-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-359">На борту серверов в Центр безопасности Azure.</span><span class="sxs-lookup"><span data-stu-id="e6590-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-360">Серверы, не управляемые диспетчером конфигурации.</span><span class="sxs-lookup"><span data-stu-id="e6590-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-361">бортовая и конфигурация macOS:</span><span class="sxs-lookup"><span data-stu-id="e6590-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-362">Развертывание на основе ручного intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-363">Развертывание на основе JAMF.</span><span class="sxs-lookup"><span data-stu-id="e6590-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="e6590-364">Другое развертывание на основе продуктов для управления мобильными устройствами (MDM).</span><span class="sxs-lookup"><span data-stu-id="e6590-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-365">Ручное развертывание.</span><span class="sxs-lookup"><span data-stu-id="e6590-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-366">Конфигурация следующих возможностей сокращения направлений атак:</span><span class="sxs-lookup"><span data-stu-id="e6590-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-367">Аппаратная изоляция.</span><span class="sxs-lookup"><span data-stu-id="e6590-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-368">Управление приложениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="e6590-369">Управление устройствами.</span><span class="sxs-lookup"><span data-stu-id="e6590-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="e6590-370">Защита от эксплойтов.</span><span class="sxs-lookup"><span data-stu-id="e6590-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-371">Сетевой брандмауэр.</span><span class="sxs-lookup"><span data-stu-id="e6590-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="e6590-372">Конфигурация или управление функциями защиты учетных записей, например:</span><span class="sxs-lookup"><span data-stu-id="e6590-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="e6590-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="e6590-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="e6590-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="e6590-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="e6590-375">Конфигурация или управление BitLocker.</span><span class="sxs-lookup"><span data-stu-id="e6590-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="e6590-376">Развертывание или конфигурация экспертов Майкрософт по угрозам.</span><span class="sxs-lookup"><span data-stu-id="e6590-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="e6590-377">Настройка или обучение, просмотр API или сведений о безопасности и подключений к управлению событиями (SIEM).</span><span class="sxs-lookup"><span data-stu-id="e6590-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="e6590-378">Развертывание или конфигурация защиты от угроз (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="e6590-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="e6590-379">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="e6590-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="e6590-380">Учебные материалы или руководства по использованию или созданию запросов Kusto.</span><span class="sxs-lookup"><span data-stu-id="e6590-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="e6590-381">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e6590-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="e6590-382"><strong>Защитник Майкрософт для удостоверения </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="e6590-383">Microsoft Defender для удостоверений — это облачное решение для обеспечения безопасности, использующее ваши локальные сигналы Active Directory для выявления, обнаружения и исследования расширенных угроз, скомпрометированных удостоверений и вредоносных внутренних действий, направленных против вашей организации.</span><span class="sxs-lookup"><span data-stu-id="e6590-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="e6590-384">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="e6590-385">Создание экземпляра Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="e6590-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="e6590-386">Подключение защитника удостоверений к Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e6590-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="e6590-387">Оценка готовности среды к развертыванию датчика Defender для удостоверений на контроллерах домена, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="e6590-388">Запуск средства размеров для планирования емкости ресурсов.</span><span class="sxs-lookup"><span data-stu-id="e6590-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="e6590-389">Запуск средства аудита для оценки совместимости контроллеров домена с датчиком.</span><span class="sxs-lookup"><span data-stu-id="e6590-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="e6590-390">Развертывание датчика для захвата и размыва сетевого трафика и событий Windows непосредственно из контроллеров домена, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="e6590-391">Загрузка пакета датчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="e6590-392">Настройка датчика.</span><span class="sxs-lookup"><span data-stu-id="e6590-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="e6590-393">Установка датчика на контроллере домена безмолвно.</span><span class="sxs-lookup"><span data-stu-id="e6590-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="e6590-394">Развертывание датчика в многолесной среде.</span><span class="sxs-lookup"><span data-stu-id="e6590-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="e6590-395">Интеграция defender for Identity с безопасностью облачных приложений Microsoft (лицензирование безопасности облачных приложений не требуется).</span><span class="sxs-lookup"><span data-stu-id="e6590-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="e6590-396">Предоставление рекомендаций по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="e6590-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="e6590-397">Настройка среды для уменьшения "шума".</span><span class="sxs-lookup"><span data-stu-id="e6590-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="e6590-398">Понимание отчета об оценке состояния безопасности удостоверений.</span><span class="sxs-lookup"><span data-stu-id="e6590-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="e6590-399">Понимание оценки приоритетов для исследования пользователей и отчета о рейтинге исследования пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="e6590-400">Понимание неактивного отчета пользователя.</span><span class="sxs-lookup"><span data-stu-id="e6590-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="e6590-401">Предоставление параметров исправлений на скомпрометированную учетную запись.</span><span class="sxs-lookup"><span data-stu-id="e6590-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="e6590-402">Упрощение переноса из Advanced Threat Analytics (ATA) в Defender for Identity.</span><span class="sxs-lookup"><span data-stu-id="e6590-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="e6590-403"><strong>Ниже приводится неосякаемая область</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="e6590-404">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="e6590-405">Постоянное управление, реагирование на угрозы и исправление.</span><span class="sxs-lookup"><span data-stu-id="e6590-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="e6590-406">Развертывание датчика Defender для удостоверений, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="e6590-407">Ручное планирование емкости.</span><span class="sxs-lookup"><span data-stu-id="e6590-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="e6590-408">Развертывание датчика в автономных емкостях.</span><span class="sxs-lookup"><span data-stu-id="e6590-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="e6590-409">Развертывание датчика с помощью адаптора сетевого интерфейса (NIC).</span><span class="sxs-lookup"><span data-stu-id="e6590-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="e6590-410">Развертывание датчика через сторонний инструмент.</span><span class="sxs-lookup"><span data-stu-id="e6590-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="e6590-411">Подключение к облачной службе Defender for Identity с помощью подключения веб-прокси.</span><span class="sxs-lookup"><span data-stu-id="e6590-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="e6590-412">Создание и управление медоносами.</span><span class="sxs-lookup"><span data-stu-id="e6590-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="e6590-413">Рекомендации по развертыванию или обучение по:</span><span class="sxs-lookup"><span data-stu-id="e6590-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="e6590-414">Исправление или интерпретация различных типов оповещений и отслеживаемой деятельности.</span><span class="sxs-lookup"><span data-stu-id="e6590-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="e6590-415">Исследование пути перемещения пользователя, компьютера, поодаль или объекта.</span><span class="sxs-lookup"><span data-stu-id="e6590-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="e6590-416">Угроза или продвинутая охота.</span><span class="sxs-lookup"><span data-stu-id="e6590-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="e6590-417">Реагирование на инцидент.</span><span class="sxs-lookup"><span data-stu-id="e6590-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="e6590-418">Предоставление лабораторного руководства по оповещению о безопасности для Defender для identity.</span><span class="sxs-lookup"><span data-stu-id="e6590-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="e6590-419">Предоставление уведомлений, когда Defender for Identity обнаруживает подозрительные действия, отправляя оповещения безопасности на сервер syslog с помощью назначенного датчика.</span><span class="sxs-lookup"><span data-stu-id="e6590-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="e6590-420">Настройка defender for Identity для выполнения запросов с помощью удаленного протокола диспетчера безопасности (SAMR) для идентификации локальных администраторов на определенных машинах.</span><span class="sxs-lookup"><span data-stu-id="e6590-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="e6590-421">Настройка VPN-решений для добавления сведений из VPN-подключения на страницу профиля пользователя.</span><span class="sxs-lookup"><span data-stu-id="e6590-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="e6590-422">Сведения о безопасности и управление событиями (SIEM) или интеграция API (включая Azure Sentinel).</span><span class="sxs-lookup"><span data-stu-id="e6590-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="e6590-423">Развертывание датчиков Defender для удостоверений в качестве доказательства концепции.</span><span class="sxs-lookup"><span data-stu-id="e6590-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e6590-424">Развернут Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e6590-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="e6590-425">Контроллеры домена, которые вы собираетесь установить датчики Defender для удостоверений, подключены к облачной службе Defender для удостоверений.</span><span class="sxs-lookup"><span data-stu-id="e6590-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="e6590-426">Брандмауэр и прокси должны быть открыты для связи с облачной службой Defender for Identity (\*.atp.azure.com порт 443 должен быть открыт).</span><span class="sxs-lookup"><span data-stu-id="e6590-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="e6590-427">Контроллеры домена, работающие на одном из следующих:</span><span class="sxs-lookup"><span data-stu-id="e6590-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="e6590-428">Windows Server 2008 R2 SP1.</span><span class="sxs-lookup"><span data-stu-id="e6590-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="e6590-429">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="e6590-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="e6590-430">Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="e6590-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="e6590-431">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="e6590-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="e6590-432">Windows Server 2019 с KB4487044 (сборка ОС 17763.316).</span><span class="sxs-lookup"><span data-stu-id="e6590-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="e6590-433"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="e6590-434">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-435">Создание и публикация меток и политик хранения (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="e6590-436">Управление записями (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="e6590-437">Проверка создания плана файлов.</span><span class="sxs-lookup"><span data-stu-id="e6590-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="e6590-438">Создание и управление записями (включая записи на основе событий).</span><span class="sxs-lookup"><span data-stu-id="e6590-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="e6590-439">Просмотр диспозиции.</span><span class="sxs-lookup"><span data-stu-id="e6590-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="e6590-440">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-441">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-442">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-443">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-444">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-445">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-446">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-447">

  <strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="e6590-448">Разработка плана файлов управления записями.</span><span class="sxs-lookup"><span data-stu-id="e6590-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="e6590-449">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="e6590-450">Разработка информационной архитектуры в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e6590-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="e6590-451">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="e6590-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e6590-452">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-453">Поддержка E3.</span><span class="sxs-lookup"><span data-stu-id="e6590-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="e6590-454">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-455">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="e6590-456">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-457"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="e6590-458">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-459">Классификация данных (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-460">Типы конфиденциальной информации (поддерживаемые в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-461">Создание меток конфиденциальности (поддерживаемых в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-462">Применение меток чувствительности (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-463">Классификаторы, которые можно обучить (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-464">Знание данных с помощью обозревателя контента и проводника действий (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-465">Публикация меток с использованием политик (ручная и автоматическая) (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-466">Создание политик предотвращения потери данных конечной точки (DLP) для устройств Windows 10 (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-467">Создание политик DLP для чатов и каналов Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="e6590-468">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-469">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-470">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-471">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-472">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-473">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-474">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-475">

<strong> Защита информации Azure</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="e6590-476">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-477">Активация и настройка клиента.</span><span class="sxs-lookup"><span data-stu-id="e6590-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="e6590-478">Создание и настройка меток и политик (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-479">Применение защиты информации к документам (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-480">Автоматическое классификация и маркировка сведений в приложениях Office (например, Word, PowerPoint, Excel и Outlook), работающих в Windows и использующих клиент Azure Information Protection (поддерживается в P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-481">Обнаружение и маркировка файлов в покое с помощью сканера защиты информации Azure (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-482">Отслеживание сообщений электронной почты в пути с помощью правил потока обработки почты Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="e6590-483">Мы также предоставляем рекомендации, если вы хотите применить защиту с помощью служб управления правами Microsoft Azure (Azure RMS), шифрования сообщений Office 365 (OME) и предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="e6590-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="e6590-484"><strong>Ниже приводится неосякаемая область </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="e6590-485">Ключ клиента.</span><span class="sxs-lookup"><span data-stu-id="e6590-485">Customer key.</span></span></li>
<li><span data-ttu-id="e6590-486">Настраиваемая разработка регулярных выражений (RegEx) для типов конфиденциальной информации.</span><span class="sxs-lookup"><span data-stu-id="e6590-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="e6590-487">Создание или изменение словарей ключевых слов.</span><span class="sxs-lookup"><span data-stu-id="e6590-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="e6590-488">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="e6590-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e6590-489">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="e6590-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="e6590-490">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-491">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-492">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="e6590-493">Помимо основной <strong></strong> части в <a href="#general">целом,</a>минимальные требования к системе, за исключением Azure Information Protection, не существуют.</span><span class="sxs-lookup"><span data-stu-id="e6590-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="e6590-494"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="e6590-495">Обязанности, необходимые для клиента, включают:</span><span class="sxs-lookup"><span data-stu-id="e6590-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-496">Список местоположений для совместной работы с файлами, которые необходимо отсканировать.</span><span class="sxs-lookup"><span data-stu-id="e6590-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="e6590-497">Утвержденная таксономия классификации.</span><span class="sxs-lookup"><span data-stu-id="e6590-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="e6590-498">Понимание любых нормативных ограничений или требований в отношении управления ключами.</span><span class="sxs-lookup"><span data-stu-id="e6590-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-499">Учетная запись службы, созданная для локального Active Directory, синхронизированного с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="e6590-500">Метки, настроенные для классификации и защиты.</span><span class="sxs-lookup"><span data-stu-id="e6590-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="e6590-501">Все необходимые условия для сканера защиты информации Azure на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="e6590-502">Дополнительные сведения см. в дополнительных сведениях, необходимых для установки и развертывания сканера единой маркировки <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="e6590-503">Убедитесь, что на устройствах пользователей запущена поддерживаемая операционная система и установлены необходимые условия.</span><span class="sxs-lookup"><span data-stu-id="e6590-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="e6590-504">Дополнительные сведения см. в следующих сведениях.</span><span class="sxs-lookup"><span data-stu-id="e6590-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="e6590-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Руководство по администрированию: Установите клиент единой маркировки Azure Information Protection для пользователей</a>   </span><span class="sxs-lookup"><span data-stu-id="e6590-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="e6590-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Что такое приложение Azure Information Protection для iOS или Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="e6590-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="e6590-507">Установка и конфигурация соединителя Azure RMS и серверов, включая соединителя Active Directory RMS (AD RMS) для гибридной поддержки.</span><span class="sxs-lookup"><span data-stu-id="e6590-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="e6590-508">Настройка и конфигурация Bring Your Own Key (BYOK), Double Key Encryption (DKE) (только для клиента единой маркировки) или Hold Your Own Key (HYOK) (только для классического клиента) если вам потребуется один из этих вариантов развертывания.</span><span class="sxs-lookup"><span data-stu-id="e6590-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="e6590-510">Мы предоставляем удаленные рекомендации по готовности использовать Intune в качестве облачного поставщика управления мобильными устройствами (MDM) и поставщика управления мобильными приложениями (MAM) для ваших приложений и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="e6590-511">Конкретные действия зависят от исходной среды и основаны на мобильном устройстве и требованиях к управлению мобильными приложениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="e6590-512">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="e6590-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-513">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e6590-514">Настройка удостоверений, которые будут использоваться Intune, используя локальное active Directory или облачные идентификаторы (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="e6590-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="e6590-515">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-516">Настройка полномочий MDM на основе потребностей управления, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-517">Настройка Intune в качестве центра MDM, когда Intune является единственным решением MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-518">Предоставление рекомендаций по MDM для следующих действий:</span><span class="sxs-lookup"><span data-stu-id="e6590-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-519">Настройка тестовых групп, используемых для проверки политик управления MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-520">Настройка политик управления MDM и таких служб, как:</span><span class="sxs-lookup"><span data-stu-id="e6590-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-521">Развертывание приложений для каждой поддерживаемой платформы с помощью веб-ссылок или глубоких ссылок.</span><span class="sxs-lookup"><span data-stu-id="e6590-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="e6590-522">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-523">Развертывание профилей электронной почты, беспроводных сетей и VPN, если у вас есть существующие полномочия сертификата, беспроводная сеть или инфраструктура VPN в организации.</span><span class="sxs-lookup"><span data-stu-id="e6590-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="e6590-524">Подключение к складу данных Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="e6590-525">Интеграция Intune со следующими компонентами:</span><span class="sxs-lookup"><span data-stu-id="e6590-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-526">Просмотр группы для удаленной помощи (требуется подписка на просмотр группы).</span><span class="sxs-lookup"><span data-stu-id="e6590-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e6590-527">Решения партнеров Mobile Threat Defense (MTD) (требуется подписка на MTD).</span><span class="sxs-lookup"><span data-stu-id="e6590-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e6590-528">Решение по управлению расходами телекома (требуется подписка на решение по управлению расходами на телеком).</span><span class="sxs-lookup"><span data-stu-id="e6590-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="e6590-529">Регистрация устройств всех поддерживаемых платформ в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="e6590-530">Предоставление рекомендаций по защите приложений по:</span><span class="sxs-lookup"><span data-stu-id="e6590-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-531">Настройка политик защиты приложений для каждой поддерживаемой платформы.</span><span class="sxs-lookup"><span data-stu-id="e6590-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="e6590-532">Настройка политик условного доступа для управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="e6590-533">Ориентация соответствующих групп пользователей с помощью ранее упомянутых политик MAM.</span><span class="sxs-lookup"><span data-stu-id="e6590-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-534">Использование отчетов об использовании управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-535">Предоставление руководства по миграции из устаревшего управления ПК в intune MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="e6590-536">
 
</li>
</ul>
  
<strong>Подключение к облаку</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="e6590-537">Мы повествуем о готовности к подключению к существующим средам Configuration Manager с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="e6590-538">Конкретные действия зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="e6590-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="e6590-539">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="e6590-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-540">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e6590-541">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory и облачных удостоверений.</span><span class="sxs-lookup"><span data-stu-id="e6590-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="e6590-542">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-543">Предоставление рекомендаций по настройке гибридного присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e6590-544">Предоставление рекомендаций по настройке автоматической регистрации Azure AD для автозарегистрации MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-545">Предоставление рекомендаций по настройкам шлюза управления облачными ресурсами при их совместном управлении удаленным управлением устройствами в Интернете.</span><span class="sxs-lookup"><span data-stu-id="e6590-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-546">Настройка поддерживаемых рабочих нагрузок, которые нужно перевести в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="e6590-547">Установка клиента диспетчера конфигураций на устройствах, зарегистрированных в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="e6590-548"><strong>Безопасно развертывание мобильных устройств Outlook для iOS и Android</strong> Мы можем предоставить рекомендации по безопасному развертыванию мобильных устройств Outlook для iOS и Android в организации, чтобы убедиться, что у пользователей установлены все необходимые приложения.</span><span class="sxs-lookup"><span data-stu-id="e6590-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="e6590-549">Действия по безопасному развертыванию мобильных устройств Outlook для iOS и Android с помощью Intune зависят от исходных сред.</span><span class="sxs-lookup"><span data-stu-id="e6590-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="e6590-550">Он может включать в себя:</span><span class="sxs-lookup"><span data-stu-id="e6590-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-551">Загрузка приложений Outlook для iOS и Android, Microsoft Authenticator и Портала компании Intune через Магазин приложений Apple или Магазин Google Play.</span><span class="sxs-lookup"><span data-stu-id="e6590-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="e6590-552">Предоставление рекомендаций по настройке:</span><span class="sxs-lookup"><span data-stu-id="e6590-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-553">Развертывание приложений Outlook для iOS и Android, Microsoft Authenticator и портала компании Intune с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="e6590-554">Политики защиты приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-555">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-556">Политики конфигурации приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="e6590-557">ИТ-администраторы должны иметь существующие инфраструктуры сертификатов, беспроводной сети и VPN, которые уже работают в рабочей среде при планировании развертывания профилей беспроводной сети и VPN с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="e6590-558"><strong>Примечание.</strong>Преимущество службы FastTrack не включает помощь в настройке или настройке органов сертификации, беспроводных сетей, инфраструктур VPN или push-сертификатов Apple MDM для Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="e6590-559"><strong>Примечание</strong>. Преимущество службы FastTrack не включает помощь по настройке или обновлению сервера сайта диспетчера конфигураций или клиента диспетчера конфигураций до минимальных требований, необходимых для поддержки подключения к облаку.</span><span class="sxs-lookup"><span data-stu-id="e6590-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="e6590-560">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="e6590-561"><strong>Интеграция Intune с Advanced Threat Protection (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="e6590-562"><strong>Примечание.</strong>Мы предоставляем помощь в интеграции Intune с ATP Microsoft Defender и создании политик соответствия требованиям устройств на основе оценки уровня риска Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="e6590-563">Мы не предоставляем помощь в приобретении, лицензировании или активации.</span><span class="sxs-lookup"><span data-stu-id="e6590-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="e6590-564">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="e6590-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="e6590-566">ИТ-администраторы отвечают за регистрацию устройств в организации путем отправки поставщиком оборудования идентификаторов оборудования от имени администраторов или с помощью самостоятельной их отправки в службу Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="e6590-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="e6590-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="e6590-568">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-569">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="e6590-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="e6590-570">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="e6590-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="e6590-571">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="e6590-572">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="e6590-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-573">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="e6590-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="e6590-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-575"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-576"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-577"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e6590-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="e6590-579">Для Exchange Online мы повеяем процесс, чтобы ваша организация была готова к использованию электронной почты.</span><span class="sxs-lookup"><span data-stu-id="e6590-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="e6590-580">Точные действия зависят от исходных сред и планов миграции электронной почты.</span><span class="sxs-lookup"><span data-stu-id="e6590-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="e6590-581">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-582">Настройка функций Exchange Online Protection (EOP) для всех доменов, поддерживающих почту и проверенных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-583">Указать записи обмена почтой (MX) в Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-584">Настройка функции ATP Office 365, если она является частью службы подписки.</span><span class="sxs-lookup"><span data-stu-id="e6590-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="e6590-585">Дополнительные сведения см. в части <strong>Office 365 Advanced Threat Protection</strong> в этой таблице.</span><span class="sxs-lookup"><span data-stu-id="e6590-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="e6590-p127">Настройка функции защиты от потери данных (DLP) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="e6590-p128">Настройка шифрования сообщений Office 365 (OME) для всех доменов с включенной поддержкой почты, проверенных в Office 365 в рамках подписки. Это выполняется, когда записи MX указывают на Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="e6590-590">
  <strong>Примечание:</strong> Служба репликации почтовых ящиков (MRS) пытается перенести электронные письма управляемых прав на информацию (IRM) из локального почтового ящика в соответствующий почтовый ящик Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="e6590-591">Возможность чтения защищенных данных после переноса зависит от сопоставления клиентом шаблонов службы Active Directory Rights Managed Services (AD RMS) и их копирования в службу Azure Rights Management Service (Azure RMS).</span><span class="sxs-lookup"><span data-stu-id="e6590-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-592">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="e6590-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e6590-593">Настройка DNS, включая необходимые рамки политики автообнаружения, политик отправитель (SPF), DomainKeys Identified Mail (DKIM), проверку подлинности сообщений на основе домена, отчетность и соответствие (DMARC) и записи MX (по мере необходимости).</span><span class="sxs-lookup"><span data-stu-id="e6590-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="e6590-594">Настройка потока обработки почты между исходной средой обмена сообщениями и Exchange Online (при необходимости).</span><span class="sxs-lookup"><span data-stu-id="e6590-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="e6590-595">Перенос почты из исходной среды обмена сообщениями в Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-596">Настройка почтовых клиентов (Outlook для Windows, Outlook в Интернете, Outlook для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="e6590-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="e6590-597">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="e6590-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="e6590-598">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="https://docs.microsoft.com/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="e6590-599">В исходных средах должен быть один из следующих минимальных уровней:</span><span class="sxs-lookup"><span data-stu-id="e6590-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-600">Одна или несколько организаций Exchange с Exchange Server 2003 или более поздней версии.</span><span class="sxs-lookup"><span data-stu-id="e6590-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="e6590-601">Одна почтовая среда, поддерживающая протокол IMAP.</span><span class="sxs-lookup"><span data-stu-id="e6590-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-602">Одна среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="e6590-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="e6590-603">Сведения о возможностях multi-Geo см. в <a href="https://go.microsoft.com/fwlink/?linkid=872776">сайте Multi-Geo Capabilities in Exchange Online.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="e6590-604">Клиентские программы в Интернете, такие как Project for Office 365, Outlook for Windows, Outlook для iOS и Android, клиент синхронизации OneDrive для бизнеса, Power BI Desktop и Skype для бизнеса должны быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-605"><strong>Управление информацией (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="e6590-606">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-607">Создание и публикация меток и политик хранения (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="e6590-608">Управление записями (поддерживается только в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="e6590-609">Проверка создания плана файлов.</span><span class="sxs-lookup"><span data-stu-id="e6590-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="e6590-610">Создание и управление записями (включая записи на основе событий).</span><span class="sxs-lookup"><span data-stu-id="e6590-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="e6590-611">Просмотр диспозиции.</span><span class="sxs-lookup"><span data-stu-id="e6590-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="e6590-612">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-613">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-614">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-615">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-616">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-617">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-618">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-619">

  <strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="e6590-620">Разработка плана файлов управления записями.</span><span class="sxs-lookup"><span data-stu-id="e6590-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="e6590-621">Соединители данных.</span><span class="sxs-lookup"><span data-stu-id="e6590-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="e6590-622">Разработка информационной архитектуры в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e6590-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="e6590-623">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="e6590-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e6590-624">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-625">Поддержка E3.</span><span class="sxs-lookup"><span data-stu-id="e6590-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="e6590-626">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-627">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="e6590-628">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-629"><strong>Защита информации (Майкрософт)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="e6590-630">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-631">Классификация данных (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-632">Типы конфиденциальной информации (поддерживаемые в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-633">Создание меток конфиденциальности (поддерживаемых в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-634">Применение меток чувствительности (поддерживается в E3 и E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-635">Классификаторы, которые можно обучить (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-636">Знание данных с помощью обозревателя контента и проводника действий (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-637">Публикация меток с использованием политик (ручная и автоматическая) (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-638">Создание политик предотвращения потери данных конечной точки (DLP) для устройств Windows 10 (поддерживается в E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="e6590-639">Создание политик DLP для чатов и каналов Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="e6590-640">

<strong> Диспетчер соответствия требованиям</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="e6590-641">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="e6590-642">Просмотр типов ролей.</span><span class="sxs-lookup"><span data-stu-id="e6590-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="e6590-643">Добавление и настройка оценок.</span><span class="sxs-lookup"><span data-stu-id="e6590-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="e6590-644">Оценка соответствия требованиям путем реализации действий по улучшению и определения того, как это влияет на оценку соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="e6590-645">Проверка встроенного сопоставления элементов управления и оценки элементов управления.</span><span class="sxs-lookup"><span data-stu-id="e6590-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="e6590-646">Создание отчета в рамках оценки.</span><span class="sxs-lookup"><span data-stu-id="e6590-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="e6590-647">

<strong> Защита информации Azure</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="e6590-648">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-649">Активация и настройка клиента.</span><span class="sxs-lookup"><span data-stu-id="e6590-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="e6590-650">Создание и настройка меток и политик (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-651">Применение защиты информации к документам (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-652">Автоматическое классификация и маркировка сведений в приложениях Office (например, Word, PowerPoint, Excel и Outlook), работающих в Windows и использующих клиент Azure Information Protection (поддерживается в P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-653">Обнаружение и маркировка файлов в покое с помощью сканера защиты информации Azure (поддерживается в P1 и P2).</span><span class="sxs-lookup"><span data-stu-id="e6590-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="e6590-654">Отслеживание сообщений электронной почты в пути с помощью правил потока обработки почты Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="e6590-655">Мы также предоставляем рекомендации, если вы хотите применить защиту с помощью служб управления правами Microsoft Azure (Azure RMS), шифрования сообщений Office 365 (OME) и предотвращения потери данных (DLP).</span><span class="sxs-lookup"><span data-stu-id="e6590-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="e6590-656"><strong>Ниже приводится неосякаемая область </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="e6590-657">Ключ клиента.</span><span class="sxs-lookup"><span data-stu-id="e6590-657">Customer key.</span></span></li>
<li><span data-ttu-id="e6590-658">Настраиваемая разработка регулярных выражений (RegEx) для типов конфиденциальной информации.</span><span class="sxs-lookup"><span data-stu-id="e6590-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="e6590-659">Создание или изменение словарей ключевых слов.</span><span class="sxs-lookup"><span data-stu-id="e6590-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="e6590-660">Настраиваемый сценарий и кодирование.</span><span class="sxs-lookup"><span data-stu-id="e6590-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="e6590-661">Azure Purview.</span><span class="sxs-lookup"><span data-stu-id="e6590-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="e6590-662">Разработка, архитектор и проверка документов сторонних разработчиков.</span><span class="sxs-lookup"><span data-stu-id="e6590-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="e6590-663">Соблюдение отраслевых и региональных правил и требований.</span><span class="sxs-lookup"><span data-stu-id="e6590-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="e6590-664">Практическое выполнение рекомендуемых действий по улучшению для оценки в диспетчере соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="e6590-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="e6590-665">Помимо основной <strong></strong> части в <a href="#general">целом,</a>минимальные требования к системе, за исключением Azure Information Protection, не существуют.</span><span class="sxs-lookup"><span data-stu-id="e6590-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="e6590-666"><strong>Azure Information Protection</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="e6590-667">Обязанности, необходимые для клиента, включают:</span><span class="sxs-lookup"><span data-stu-id="e6590-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-668">Список местоположений для совместной работы с файлами, которые необходимо отсканировать.</span><span class="sxs-lookup"><span data-stu-id="e6590-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="e6590-669">Утвержденная таксономия классификации.</span><span class="sxs-lookup"><span data-stu-id="e6590-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="e6590-670">Понимание любых нормативных ограничений или требований в отношении управления ключами.</span><span class="sxs-lookup"><span data-stu-id="e6590-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-671">Учетная запись службы, созданная для локального Active Directory, синхронизированного с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="e6590-672">Метки, настроенные для классификации и защиты.</span><span class="sxs-lookup"><span data-stu-id="e6590-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="e6590-673">Все необходимые условия для сканера защиты информации Azure на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="e6590-674">Дополнительные сведения см. в дополнительных сведениях, необходимых для установки и развертывания сканера единой маркировки <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Azure Information Protection.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="e6590-675">Убедитесь, что на устройствах пользователей запущена поддерживаемая операционная система и установлены необходимые условия.</span><span class="sxs-lookup"><span data-stu-id="e6590-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="e6590-676">Дополнительные сведения см. в следующих сведениях.</span><span class="sxs-lookup"><span data-stu-id="e6590-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="e6590-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Руководство по администрированию: Установите клиент единой маркировки Azure Information Protection для пользователей</a>   </span><span class="sxs-lookup"><span data-stu-id="e6590-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="e6590-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Что такое приложение Azure Information Protection для iOS или Android?</a>  </span><span class="sxs-lookup"><span data-stu-id="e6590-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="e6590-679">Установка и конфигурация соединителя Azure RMS и серверов, включая соединителя Active Directory RMS (AD RMS) для гибридной поддержки.</span><span class="sxs-lookup"><span data-stu-id="e6590-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="e6590-680">Настройка и конфигурация Bring Your Own Key (BYOK), Double Key Encryption (DKE) (только для клиента единой маркировки) или Hold Your Own Key (HYOK) (только для классического клиента) если вам потребуется один из этих вариантов развертывания.</span><span class="sxs-lookup"><span data-stu-id="e6590-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="e6590-682">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-683">Подтверждение минимальных требований в Exchange Online, SharePoint Online, Office 365 Groups и Azure AD для поддержки Teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="e6590-684">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="e6590-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e6590-685">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="e6590-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="e6590-686">Подтверждение того, что рабочее пространство Teams включено в клиенте Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="e6590-687">Включение или отключение пользовательских лицензий.</span><span class="sxs-lookup"><span data-stu-id="e6590-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="e6590-688">Оценка сети для Teams:</span><span class="sxs-lookup"><span data-stu-id="e6590-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-689">Проверка портов и конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="e6590-690">Проверка качества подключения.</span><span class="sxs-lookup"><span data-stu-id="e6590-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="e6590-691">Оценка пропускной способности.</span><span class="sxs-lookup"><span data-stu-id="e6590-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="e6590-692">Настройка политики приложений Teams (веб-приложение Teams, приложение Teams Desktop и Teams для приложений для iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="e6590-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="e6590-693">Если применимо, мы также предоставляем рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-694">Устройства комнат Microsoft Teams:</span><span class="sxs-lookup"><span data-stu-id="e6590-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="e6590-695">Создание учетных записей интернет-служб, необходимых для поддерживаемых устройств телефонной и конференц-связи. Устройства перечислены в <a href="https://go.microsoft.com/fwlink/?linkid=2066478">каталоге устройств Teams</a>.</span><span class="sxs-lookup"><span data-stu-id="e6590-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="e6590-696">Удаленная помощь с конфигурацией на стороне служб сертифицированных устройств Microsoft Teams Rooms.</span><span class="sxs-lookup"><span data-stu-id="e6590-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="e6590-697">Включение Аудиоконференций:</span><span class="sxs-lookup"><span data-stu-id="e6590-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="e6590-698">Настройка организации с использованием параметров по умолчанию для схемы конференции.</span><span class="sxs-lookup"><span data-stu-id="e6590-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="e6590-699">Назначение моста конференции лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="e6590-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="e6590-700">Телефонная система:</span><span class="sxs-lookup"><span data-stu-id="e6590-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-701">Настройка облачных голосовых функций для организации.</span><span class="sxs-lookup"><span data-stu-id="e6590-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="e6590-702">Руководство по планам вызова<a href="https://go.microsoft.com/fwlink/?linkid=2066478">(доступные рынки):</a></span><span class="sxs-lookup"><span data-stu-id="e6590-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="e6590-703">Назначение номеров лицензированным пользователям.</span><span class="sxs-lookup"><span data-stu-id="e6590-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="e6590-704">Рекомендации по портированию локальных номеров до 999 в пользовательском интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="e6590-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="e6590-705">Поддержка запросов на обслуживание для портирования локальных номеров выше 999.</span><span class="sxs-lookup"><span data-stu-id="e6590-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-706">Руководство по прямой маршрутике:</span><span class="sxs-lookup"><span data-stu-id="e6590-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-707">Руководство по настройке организации для разработки сценариев с размещением партнеров или сценариев, развернутых клиентами, для 10 сайтов.</span><span class="sxs-lookup"><span data-stu-id="e6590-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="e6590-708">Обзор конфигурации пограничного контроллера сеанса (SBC).</span><span class="sxs-lookup"><span data-stu-id="e6590-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="e6590-709">Удаленная помощь с конфигурацией плана набора номеров.</span><span class="sxs-lookup"><span data-stu-id="e6590-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="e6590-710">Конфигурация голосового маршрута.</span><span class="sxs-lookup"><span data-stu-id="e6590-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="e6590-711">Обход мультимедиа и оптимизация локальных средств массовой информации.</span><span class="sxs-lookup"><span data-stu-id="e6590-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="e6590-712">Включение прямых трансляций Teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="e6590-713">Настройка организации и интеграция в Microsoft Stream.</span><span class="sxs-lookup"><span data-stu-id="e6590-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="e6590-714">Руководство по переходу Skype для бизнеса на teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e6590-715">Удостоверения, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-716">Пользователи, для которых включен SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="e6590-717">Почтовые ящики Exchange присутствуют (онлайн и локально в гибридной конфигурации Exchange).</span><span class="sxs-lookup"><span data-stu-id="e6590-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="e6590-718">Включено для групп Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="e6590-719">
  <strong>Примечание:</strong> Если пользователям не назначены и не включены лицензии SharePoint Online, у них не будет хранилища OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="e6590-720">Общий доступ к файлам продолжает работать в Channels, но пользователи не могут обмениваться файлами в чатах без хранения OneDrive для бизнеса в Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="e6590-721">Команды не поддерживают локальное участие в SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e6590-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="e6590-722">
  <strong>Примечание:</strong> Идеальное состояние для всех пользователей, чтобы их почтовые ящики были дома в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="e6590-723">Пользователи с почтовыми ящиками, в которые есть локальное помещение, должны синхронизировать свои удостоверения с каталогом Office 365 через Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="e6590-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="e6590-724">Для этих гибридных клиентов Exchange, если почтовый ящик пользователя является локальной, пользователь не может добавлять или настраивать соединители.</span><span class="sxs-lookup"><span data-stu-id="e6590-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="e6590-725">Установщики клиентов Microsoft Teams для настольных компьютеров Windows и Mac можно скачать на странице <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span><span class="sxs-lookup"><span data-stu-id="e6590-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="e6590-727">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-728">Включение компонентов "Безопасные ссылки", "Безопасные вложения" и защиты от фишинга.</span><span class="sxs-lookup"><span data-stu-id="e6590-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="e6590-729">Настройка автоматизации, исследований и ответов.</span><span class="sxs-lookup"><span data-stu-id="e6590-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="e6590-730">Использование эмулятора атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="e6590-731">Отчеты и анализ угроз.</span><span class="sxs-lookup"><span data-stu-id="e6590-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-732">Помимо основной <strong>части</strong> в <a href="#general">целом,</a>минимальные требования к системе не предъявляются.</span><span class="sxs-lookup"><span data-stu-id="e6590-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-733"><strong>Outlook для iOS и Android</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="e6590-734">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-735">Скачивание Outlook для iOS и Android через Apple App Store или Google Play.</span><span class="sxs-lookup"><span data-stu-id="e6590-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="e6590-736">Настройка учетных записей и оценка почтового ящика Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="e6590-737">Защита мобильных устройств Outlook (дополнительные сведения см. <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">в рублях Securing Outlook для iOS</a> и Android в Exchange Online).</span><span class="sxs-lookup"><span data-stu-id="e6590-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="e6590-738">Удостоверения, включенные в Azure AD для Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-739">Выполнена настройка Exchange Online, назначены соответствующие лицензии.</span><span class="sxs-lookup"><span data-stu-id="e6590-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="e6590-741">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-742">Назначение лицензий на Power BI.</span><span class="sxs-lookup"><span data-stu-id="e6590-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="e6590-743">Развертывание приложения Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="e6590-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-744">Программное обеспечение клиента в Интернете, например Power BI Desktop, должно быть на минимальном уровне, определенном в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="e6590-746">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-747">Проверка основных функций SharePoint, необходимых для работы Project Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="e6590-748">Добавление службы Project Online в клиент (в том числе добавление подписок для пользователей).</span><span class="sxs-lookup"><span data-stu-id="e6590-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="e6590-749">Настройка пула корпоративных ресурсов (ERP).</span><span class="sxs-lookup"><span data-stu-id="e6590-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="e6590-750">Создание первого проекта.</span><span class="sxs-lookup"><span data-stu-id="e6590-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-751">Программное обеспечение клиента в Интернете, например Project for Office 365, должно быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-752"><strong>Project Online Professional и Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="e6590-753">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-754">Решение проблем, связанных с развертыванием.</span><span class="sxs-lookup"><span data-stu-id="e6590-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="e6590-755">Назначение пользователям лицензий с помощью Центра администрирования Microsoft 365 и Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="e6590-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="e6590-756">Установка клиента Project Online для настольных ПК с использованием портала Office 365 и технологии "нажми и работай".</span><span class="sxs-lookup"><span data-stu-id="e6590-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="e6590-757">Настройка параметров обновления с помощью средства развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e6590-758">Настройка одного внутреннего сервера распространения для клиента Project Online для настольных ПК, в том числе помощь по созданию файла configuration.xml для его последующего использования в средстве развертывания Office 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="e6590-759">Подключение клиента Project Online для настольных ПК к Project Online профессиональный или Project Online расширенный.</span><span class="sxs-lookup"><span data-stu-id="e6590-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-760">Программное обеспечение клиента в Интернете, например Project for Office 365, должно быть на минимальном уровне, как это определено в требованиях системы для <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-761"><strong>SharePoint Online и OneDrive для бизнеса</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="e6590-762">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-763">Настройка DNS.</span><span class="sxs-lookup"><span data-stu-id="e6590-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="e6590-764">Настройка портов брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="e6590-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="e6590-765">Подготовка пользователей и лицензий.</span><span class="sxs-lookup"><span data-stu-id="e6590-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="e6590-766">Создание сайтов для администратора SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="e6590-767">Планирование семейств веб-сайтов.</span><span class="sxs-lookup"><span data-stu-id="e6590-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="e6590-768">Защита контента и управление разрешениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="e6590-769">Настройка функций SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="e6590-770">Настройка функций гибридной среды SharePoint, таких как гибридный поиск, гибридные сайты, гибридная таксономия, типы контента, гибридная функция самостоятельного создания сайтов (только для SharePoint Server 2013), расширенное средство запуска приложений, гибридная служба OneDrive для бизнеса и сайты экстрасети.</span><span class="sxs-lookup"><span data-stu-id="e6590-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="e6590-771">Подход к миграции.</span><span class="sxs-lookup"><span data-stu-id="e6590-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="e6590-772">Дополнительные рекомендации предоставляются для OneDrive для бизнеса в зависимости от версии SharePoint, например:</span><span class="sxs-lookup"><span data-stu-id="e6590-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-773">Определение параметров интеграции и проверка локальной и сетевой инфраструктуры и пропускной способности сети.</span><span class="sxs-lookup"><span data-stu-id="e6590-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="e6590-774">Установка SharePoint Online 2013 SP1 (если применимо), планирование и реализация требований синхронизации и удостоверений, а также определение клиента синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="e6590-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="e6590-775">Планирование и реализация единого внедрения для всех пользователей (или поэтапного внедрения).</span><span class="sxs-lookup"><span data-stu-id="e6590-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="e6590-776">Назначение лицензий, перенаправление сайтов и библиотек персональных документов в Office 365 (применимо к SharePoint Online 2013), настройка аудиторий для управления доступом к OneDrive (применимо к SharePoint Online 2013).</span><span class="sxs-lookup"><span data-stu-id="e6590-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="e6590-777">Перенаправление или перемещение известных папок в OneDrive.</span><span class="sxs-lookup"><span data-stu-id="e6590-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="e6590-778">Развертывание клиентской синхронизации OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="e6590-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="e6590-779">
  <strong>Миграция данных</strong>  </span><span class="sxs-lookup"><span data-stu-id="e6590-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="e6590-780">Сведения об использовании преимущества FastTrack для переноса данных в Office 365 см. <a href="https://docs.microsoft.com/fasttrack/data-migration">в этой информации.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="e6590-781"><strong>Гибрид SharePoint:</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-782">Гибридная конфигурация SharePoint включает настройку гибридного поиска, сайтов, таксономии, типов контента, OneDrive для бизнеса, расширенной пусковой системы приложений, сайтов экстрасетей и создания сайтов самообслуживания, подключенных из локальной среды в единую целевую среду SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e6590-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="e6590-783">
  <strong>Примечание:</strong> Создание сайтов самообслуживания не имеет возможности для локального сервера под управлением SharePoint 2013.</span><span class="sxs-lookup"><span data-stu-id="e6590-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-784">Чтобы включить гибрид SharePoint, необходимо иметь одну из следующих локальной сред SharePoint Server: 2013, 2016 или 2019.</span><span class="sxs-lookup"><span data-stu-id="e6590-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="e6590-785">
  <strong>Примечание:</strong> Обновление локальной среды SharePoint до SharePoint Server не является областью действия.</span><span class="sxs-lookup"><span data-stu-id="e6590-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="e6590-786">Обратитесь за <a href="https://go.microsoft.com/fwlink/?linkid=2080150">помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="e6590-787">Дополнительные сведения см. в раздел <a href="https://go.microsoft.com/fwlink/?linkid=853548">Минимальные уровни общедоступных обновлений для гибридных функций SharePoint.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="e6590-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="e6590-788">
  <strong>Примечание:</strong> Сведения о возможностях multi-Geo см. в <a href="https://go.microsoft.com/fwlink/?linkid=831056">разделе Multi-Geo Capabilities in OneDrive и SharePoint Online в Office 365.</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="e6590-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-789"><strong>Yammer корпоративный</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="e6590-790">Мы предоставляем удаленные рекомендации для включения службы Yammer Enterprise.</span><span class="sxs-lookup"><span data-stu-id="e6590-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="e6590-791">Программное обеспечение клиента в Интернете должно быть на минимальном уровне, как это определено в требованиях системы <a href="https://go.microsoft.com/fwlink/?LinkID=723597">для Microsoft 365 и Office.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="e6590-792">Enterprise Mobility + Security</span><span class="sxs-lookup"><span data-stu-id="e6590-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-793"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-794"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-795"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e6590-796"><strong>Azure Active Directory (Azure AD) и Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="e6590-797">Мы предоставляем удаленные рекомендации по обеспечению безопасности облачных удостоверений для следующих сценариев.</span><span class="sxs-lookup"><span data-stu-id="e6590-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="e6590-798">

<strong>Безопасная инфраструктура фундамента</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="e6590-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="e6590-799">Настройка и включение сильной проверки подлинности для удостоверений, включая защиту с помощью многофакторной проверки подлинности Azure (только в облаке), приложения Microsoft Authenticator и комбинированной регистрации для azure MFA и сброса паролей самообслуживаемых (SSPR).</span><span class="sxs-lookup"><span data-stu-id="e6590-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="e6590-800">Для клиентов, не использующих Azure AD Premium, предоставляются рекомендации по обеспечению безопасности удостоверений с помощью по умолчанию безопасности.</span><span class="sxs-lookup"><span data-stu-id="e6590-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="e6590-801">Для премиум-клиентов Azure AD предоставляются рекомендации по обеспечению безопасности удостоверений с помощью условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="e6590-802">Обнаружение и блокировка использования слабых паролей с помощью Azure AD Password Protection.</span><span class="sxs-lookup"><span data-stu-id="e6590-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="e6590-803">Обеспечение удаленного доступа к локальному веб-приложениям с помощью прокси-сервера Приложения Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="e6590-804">Включение обнаружения и устранения рисков с помощью Azure Identity Protection.</span><span class="sxs-lookup"><span data-stu-id="e6590-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="e6590-805">Включение настраиваемого экрана регистрации, включая логотип, текст и изображения с настраиваемым брендингом.</span><span class="sxs-lookup"><span data-stu-id="e6590-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="e6590-806">Безопасное совместное использование приложений и служб с гостевых пользователей с помощью Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="e6590-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="e6590-807">Управление доступом для администраторов Office 365 с помощью встроенных административных ролей управления доступом на основе ролей и уменьшение числа привилегированных учетных записей администратора.</span><span class="sxs-lookup"><span data-stu-id="e6590-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="e6590-808">Настройка гибридного присоединиться Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e6590-809">Настройка присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="e6590-810">
  
<strong>Мониторинг и отчетность</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-811">Включение удаленного мониторинга для AD FS, Azure AD Connect и контроллеров домена с помощью Azure AD Connect Health.</span><span class="sxs-lookup"><span data-stu-id="e6590-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-812">
  
<strong>Управление</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-813">Управление удостоверением Azure AD и доступ к жизненному циклу в масштабе с помощью управления правами Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="e6590-814">Управление членством в группах Azure AD, доступом к корпоративным приложениям и назначениями ролей с помощью обзоров доступа к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-815">Просмотр терминов использования Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-816">Управление и управление доступом к привилегированным учетным записям администратора с помощью Azure AD Privileged Identity Management.</span><span class="sxs-lookup"><span data-stu-id="e6590-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-817">
  
<strong>Автоматизация и эффективность </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-818">Включение SSPR Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="e6590-819">Позволяет пользователям создавать и управлять собственными группами облачной безопасности или Office 365 с помощью управления группами самообслуживки Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-820">Управление делегированием доступа к корпоративным приложениям с помощью делегирования группы Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-821">Включение динамических групп Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-822">Организация приложений на портале Мои приложения с помощью коллекций.</span><span class="sxs-lookup"><span data-stu-id="e6590-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="e6590-823">Локальное active Directory и его среда были подготовлены для Azure AD Premium, включая устранение выявленных проблем, препятствуя интеграции с функциями Azure AD и Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="e6590-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="e6590-824"><strong>Защита информации Azure </strong></span><span class="sxs-lookup"><span data-stu-id="e6590-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="e6590-825">Дополнительные сведения о защите информации Azure см. в <strong>веб-сайте Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> Security and Compliance.</span><span class="sxs-lookup"><span data-stu-id="e6590-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="e6590-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="e6590-827">Мы предоставляем удаленные рекомендации по готовности использовать Intune в качестве облачного поставщика управления мобильными устройствами (MDM) и поставщика управления мобильными приложениями (MAM) для ваших приложений и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="e6590-828">Конкретные действия зависят от исходной среды и основаны на мобильном устройстве и требованиях к управлению мобильными приложениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="e6590-829">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="e6590-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-830">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e6590-831">Настройка удостоверений, которые будут использоваться Intune, используя локальное active Directory или облачные идентификаторы (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="e6590-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="e6590-832">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-833">Настройка полномочий MDM на основе потребностей управления, в том числе:</span><span class="sxs-lookup"><span data-stu-id="e6590-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-834">Настройка Intune в качестве центра MDM, когда Intune является единственным решением MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-835">Предоставление рекомендаций по MDM для следующих действий:</span><span class="sxs-lookup"><span data-stu-id="e6590-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-836">Настройка тестовых групп, используемых для проверки политик управления MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-837">Настройка политик управления MDM и таких служб, как:</span><span class="sxs-lookup"><span data-stu-id="e6590-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-838">Развертывание приложений для каждой поддерживаемой платформы с помощью веб-ссылок или глубоких ссылок.</span><span class="sxs-lookup"><span data-stu-id="e6590-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="e6590-839">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-840">Развертывание профилей электронной почты, беспроводных сетей и VPN, если у вас есть существующие полномочия сертификата, беспроводная сеть или инфраструктура VPN в организации.</span><span class="sxs-lookup"><span data-stu-id="e6590-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="e6590-841">Подключение к складу данных Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="e6590-842">Интеграция Intune со следующими компонентами:</span><span class="sxs-lookup"><span data-stu-id="e6590-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-843">Просмотр группы для удаленной помощи (требуется подписка на просмотр группы).</span><span class="sxs-lookup"><span data-stu-id="e6590-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e6590-844">Решения партнеров Mobile Threat Defense (MTD) (требуется подписка на MTD).</span><span class="sxs-lookup"><span data-stu-id="e6590-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="e6590-845">Решение по управлению расходами телекома (требуется подписка на решение по управлению расходами на телеком).</span><span class="sxs-lookup"><span data-stu-id="e6590-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-846">Регистрация устройств всех поддерживаемых платформ в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="e6590-847">Предоставление рекомендаций по защите приложений по:</span><span class="sxs-lookup"><span data-stu-id="e6590-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-848">Настройка политик защиты приложений для каждой поддерживаемой платформы.</span><span class="sxs-lookup"><span data-stu-id="e6590-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="e6590-849">Настройка политик условного доступа для управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="e6590-850">Ориентация соответствующих групп пользователей с помощью ранее упомянутых политик MAM.</span><span class="sxs-lookup"><span data-stu-id="e6590-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-851">Использование отчетов об использовании управляемых приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-852">Предоставление руководства по миграции из устаревшего управления ПК в intune MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="e6590-853">
  
</li>
</ul>
  
<strong>Подключение к облаку</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="e6590-854">Мы повествуем о готовности к подключению к существующим средам Configuration Manager с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="e6590-855">Конкретные действия зависят от исходной среды.</span><span class="sxs-lookup"><span data-stu-id="e6590-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="e6590-856">Возможные действия:</span><span class="sxs-lookup"><span data-stu-id="e6590-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="e6590-857">Лицензирование конечных пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="e6590-858">Настройка удостоверений, применяемых в Intune с помощью локальной службы Active Directory и облачных удостоверений.</span><span class="sxs-lookup"><span data-stu-id="e6590-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="e6590-859">Добавление пользователей в подписку Intune, определение ролей ИТ-администраторов, а также создание групп пользователей и устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="e6590-860">Предоставление рекомендаций по настройке гибридного присоединиться к Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e6590-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="e6590-861">Предоставление рекомендаций по настройке автоматической регистрации Azure AD для автозарегистрации MDM.</span><span class="sxs-lookup"><span data-stu-id="e6590-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-862">Предоставление рекомендаций по настройкам шлюза управления облачными ресурсами при их совместном управлении удаленным управлением устройствами в Интернете.</span><span class="sxs-lookup"><span data-stu-id="e6590-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="e6590-863">Настройка поддерживаемых рабочих нагрузок, которые нужно перевести в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="e6590-864">Установка клиента диспетчера конфигураций на устройствах, зарегистрированных в Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="e6590-865"><strong>Безопасно развертывание мобильных устройств Outlook для iOS и Android</strong> Мы можем предоставить рекомендации по безопасному развертыванию мобильных устройств Outlook для iOS и Android в организации, чтобы убедиться, что у пользователей установлены все необходимые приложения.</span><span class="sxs-lookup"><span data-stu-id="e6590-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="e6590-866">Действия по безопасному развертыванию мобильных устройств Outlook для iOS и Android с помощью Intune зависят от исходных сред.</span><span class="sxs-lookup"><span data-stu-id="e6590-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="e6590-867">Он может включать в себя:</span><span class="sxs-lookup"><span data-stu-id="e6590-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-868">Загрузка приложений Outlook для iOS и Android, Microsoft Authenticator и Портала компании Intune через Магазин приложений Apple или Магазин Google Play.</span><span class="sxs-lookup"><span data-stu-id="e6590-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="e6590-869">Предоставление рекомендаций по настройке:</span><span class="sxs-lookup"><span data-stu-id="e6590-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-870">Развертывание приложений Outlook для iOS и Android, Microsoft Authenticator и портала компании Intune с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="e6590-871">Политики защиты приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-872">Политики условного доступа.</span><span class="sxs-lookup"><span data-stu-id="e6590-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="e6590-873">Политики конфигурации приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="e6590-874">ИТ-администраторы должны иметь существующие инфраструктуры сертификатов, беспроводной сети и VPN, которые уже работают в рабочей среде при планировании развертывания профилей беспроводной сети и VPN с помощью Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="e6590-875"><strong>Примечание.</strong>Преимущество службы FastTrack не включает помощь в настройке или настройке органов сертификации, беспроводных сетей, инфраструктур VPN или push-сертификатов Apple MDM для Intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="e6590-876"><strong>Примечание</strong>. Преимущество службы FastTrack не включает помощь по настройке или обновлению сервера сайта диспетчера конфигураций или клиента диспетчера конфигураций до минимальных требований, необходимых для поддержки подключения к облаку.</span><span class="sxs-lookup"><span data-stu-id="e6590-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="e6590-877">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="e6590-878"><strong>Интеграция Intune с Advanced Threat Protection (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="e6590-879"><strong>Примечание.</strong>Мы предоставляем помощь в интеграции Intune с ATP Microsoft Defender и создании политик соответствия требованиям устройств на основе оценки уровня риска Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="e6590-880">Мы не предоставляем помощь в приобретении, лицензировании или активации.</span><span class="sxs-lookup"><span data-stu-id="e6590-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="e6590-881">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">за помощью к партнеру</a> Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="e6590-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="e6590-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="e6590-883">ИТ-администраторы отвечают за регистрацию устройств в организации путем отправки поставщиком оборудования идентификаторов оборудования от имени администраторов или с помощью самостоятельной их отправки в службу Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="e6590-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="e6590-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="e6590-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-885"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-886"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-887"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e6590-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="e6590-889">Мы предоставляем рекомендации по обновлению с Windows 7 Профессиональная и Windows 8.1 Professional до Windows 10 Enterprise.</span><span class="sxs-lookup"><span data-stu-id="e6590-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="e6590-890">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-891">Понимание намерения Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="e6590-892">Оценка исходных сред и требований (убедитесь, что Microsoft Endpoint Configuration Manager обновляется до необходимого уровня для поддержки развертывания Windows 10).</span><span class="sxs-lookup"><span data-stu-id="e6590-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="e6590-893">Развертывание приложений Windows 10 Enterprise и Microsoft 365 с помощью Microsoft Endpoint Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="e6590-894">Рекомендации по оценке приложений с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="e6590-895">Включение использования desktop Analytics и руководства путем создания плана развертывания Desktop Analytics.</span><span class="sxs-lookup"><span data-stu-id="e6590-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="e6590-896">Оценка совместимости Приложений Microsoft 365 с помощью панели мониторинга готовности Office 365 в Configuration Manager или с автономным набор средств для Office плюс помощь в развертывании приложений Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="e6590-897">Создание контрольного списка исправлений для того, что необходимо сделать, чтобы привести исходные среды к минимальным требованиям для успешного развертывания.</span><span class="sxs-lookup"><span data-stu-id="e6590-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-898">Предоставление рекомендаций по обновлению существующих устройств в Windows 10 Enterprise, если они соответствуют необходимым требованиям оборудования устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="e6590-899">Предоставление рекомендаций по обновлению для поддержки существующего развертывания.</span><span class="sxs-lookup"><span data-stu-id="e6590-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="e6590-900">FastTrack предоставляет рекомендации и инструкции по обновлению до Windows 10 на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="e6590-901">Кроме того, предоставляются инструкции по установке чистых образов Windows и для сценариев развертывания Windows Autopilot.</span><span class="sxs-lookup"><span data-stu-id="e6590-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="e6590-902">Развертывание приложений Microsoft 365 с помощью configuration Manager в рамках развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="e6590-903">Предоставление рекомендаций, которые помогут вашей организации оставаться в курсе windows 10 Enterprise и Microsoft 365 Apps с помощью существующей среды Configuration Manager или Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="e6590-904">
  <strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-905">Обновление Configuration Manager до Current Branch.</span><span class="sxs-lookup"><span data-stu-id="e6590-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="e6590-906">Создание настраиваемых образов для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-907">Создание и поддержка сценариев для развертывания Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="e6590-908">Переход с BIOS на UEFI в системах с Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="e6590-909">Включение функций безопасности Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="e6590-910">Настройка служб развертывания Windows (WDS) для загрузки с помощью протокола удаленной загрузки (PXE).</span><span class="sxs-lookup"><span data-stu-id="e6590-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="e6590-911">Запись и развертывание образов Windows 10 с помощью набора средств Microsoft Deployment Toolkit (MDT).</span><span class="sxs-lookup"><span data-stu-id="e6590-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="e6590-912">Использование средства миграции пользовательской среды (USMT).</span><span class="sxs-lookup"><span data-stu-id="e6590-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="e6590-913">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e6590-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="e6590-914">Для обновления ПК должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="e6590-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-915">Ос-код источника: Windows 7 Корпоративная или Профессиональный, Windows 8.1 Корпоративная или Профессиональная.</span><span class="sxs-lookup"><span data-stu-id="e6590-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="e6590-916">Устройства: рабочий стол, записная книжка или форм-фактор планшета.</span><span class="sxs-lookup"><span data-stu-id="e6590-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="e6590-917">Целевая ОС: Окно 10 Корпоративная.</span><span class="sxs-lookup"><span data-stu-id="e6590-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="e6590-918">Для обновления инфраструктуры должны быть выполнены следующие требования:</span><span class="sxs-lookup"><span data-stu-id="e6590-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-919">Microsoft Endpoint Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="e6590-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="e6590-920">Версия Configuration Manager должна поддерживаться целевой версией Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="e6590-921">Дополнительные сведения см. в таблице поддержки Configuration Manager в статье <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Поддержка Windows 10 в Configuration Manager</a>.</span><span class="sxs-lookup"><span data-stu-id="e6590-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="e6590-922"><strong>Расширенная защита от угроз (ATP) в Microsoft Defender</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="e6590-923">Расширенная защита от угроз (ATP) в Microsoft Defender — это платформа, разработанная для обнаружения, предотвращения и исследования расширенных угроз в корпоративных сетях, а также для реагирования на них.</span><span class="sxs-lookup"><span data-stu-id="e6590-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="e6590-924">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-925">Развертывание технологий для защиты конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="e6590-926">Настройка профилей защиты конечной точки и ограничений устройств.</span><span class="sxs-lookup"><span data-stu-id="e6590-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="e6590-927">Оценка управления версиями ОС и устройствами (включая Intune, Microsoft Endpoint Configuration Manager, Объекты групповой политики (GPOs) и сторонние конфигурации), а также состояние служб av Защитник Windows или другого программного обеспечения безопасности конечных точек.</span><span class="sxs-lookup"><span data-stu-id="e6590-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e6590-928">Оценка состояния служб av Windows или другого программного обеспечения безопасности конечной точки.</span><span class="sxs-lookup"><span data-stu-id="e6590-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="e6590-929">Оценка прокси и брандмауэров, ограничивающих сетевой трафик.</span><span class="sxs-lookup"><span data-stu-id="e6590-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="e6590-930">Включение службы ATP Защитника Майкрософт, объясняя, как развернуть профиль агента ATP с помощью конечной точки на борту.</span><span class="sxs-lookup"><span data-stu-id="e6590-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="e6590-931">Рекомендации по развертыванию, помощь в настройке и обучение по:</span><span class="sxs-lookup"><span data-stu-id="e6590-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-932">Управление угрозами и уязвимостями.</span><span class="sxs-lookup"><span data-stu-id="e6590-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-933">Сокращение направлений атак.</span><span class="sxs-lookup"><span data-stu-id="e6590-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-934">Защита нового поколения.</span><span class="sxs-lookup"><span data-stu-id="e6590-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-935">Выявление конечных точек и реагирование на них.</span><span class="sxs-lookup"><span data-stu-id="e6590-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-936">Автоматическое исследование и защита.</span><span class="sxs-lookup"><span data-stu-id="e6590-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="e6590-937">AtP Защитника Microsoft (требуется лицензии Windows E5 или Microsoft 365 E5).</span><span class="sxs-lookup"><span data-stu-id="e6590-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="e6590-938">Оценка безопасности</span><span class="sxs-lookup"><span data-stu-id="e6590-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-939">Просмотр имитаций и учебных пособий (например, сценариев практики, поддельных вредоносных программ и автоматических расследований).</span><span class="sxs-lookup"><span data-stu-id="e6590-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="e6590-940">Общие сведения о функциях создания отчетов и аналитики угроз.</span><span class="sxs-lookup"><span data-stu-id="e6590-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="e6590-941">Интеграция ATP Office 365 с ATP в Microsoft Defender</span><span class="sxs-lookup"><span data-stu-id="e6590-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="e6590-942">Пошаговые руководства по поведению на портале Центра безопасности в Microsoft Defender.</span><span class="sxs-lookup"><span data-stu-id="e6590-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="e6590-943">Следующие операционные системы:</span><span class="sxs-lookup"><span data-stu-id="e6590-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-944">Windows 10.</span><span class="sxs-lookup"><span data-stu-id="e6590-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-945">Windows Server 2016.</span><span class="sxs-lookup"><span data-stu-id="e6590-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-946">Windows Server 2019.</span><span class="sxs-lookup"><span data-stu-id="e6590-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-947">Windows Server 2019 Core Edition.</span><span class="sxs-lookup"><span data-stu-id="e6590-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-948">Windows Server Semi-Annual (SAC) версии 1803.</span><span class="sxs-lookup"><span data-stu-id="e6590-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-949">версии macOS 10.13, 10.14 и 10.15.</span><span class="sxs-lookup"><span data-stu-id="e6590-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="e6590-950">
<strong>Примечание:</strong> Все версии Windows Server должны управляться последней версией System Center Configuration Manager 2012 (версии 1012 R2, 1511 или 1602) или Microsoft Endpoint Configuration Manager (версии 2002 или более).</span><span class="sxs-lookup"><span data-stu-id="e6590-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="e6590-951"></li>
</ul>

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-952">Управление проектами, связанное с действиями клиента по внесению исправлений.</span><span class="sxs-lookup"><span data-stu-id="e6590-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="e6590-953">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="e6590-954">Текущее управление и реагирование на угрозы.</span><span class="sxs-lookup"><span data-stu-id="e6590-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="e6590-955">Подключение и настройка следующих агентов ATP в Microsoft Defender:</span><span class="sxs-lookup"><span data-stu-id="e6590-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-956">Windows Server 2008.</span><span class="sxs-lookup"><span data-stu-id="e6590-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-957">Windows Server 2012.</span><span class="sxs-lookup"><span data-stu-id="e6590-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-958">Linux.</span><span class="sxs-lookup"><span data-stu-id="e6590-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-959">Мобильные устройства (Android и iOS).</span><span class="sxs-lookup"><span data-stu-id="e6590-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="e6590-960">Виртуальная инфраструктура настольных компьютеров (VDI) (сохраняемая или нестойка).</span><span class="sxs-lookup"><span data-stu-id="e6590-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-961">Бортовая и конфигурация сервера:</span><span class="sxs-lookup"><span data-stu-id="e6590-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-962">Настройка прокси-сервера для автономной связи.</span><span class="sxs-lookup"><span data-stu-id="e6590-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-963">Настройка пакетов развертывания Configuration Manager на экземплярах и версиях диспетчера конфигурации на уровне.</span><span class="sxs-lookup"><span data-stu-id="e6590-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-964">На борту серверов в Центр безопасности Azure.</span><span class="sxs-lookup"><span data-stu-id="e6590-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-965">Серверы, не управляемые диспетчером конфигурации.</span><span class="sxs-lookup"><span data-stu-id="e6590-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-966">бортовая и конфигурация macOS:</span><span class="sxs-lookup"><span data-stu-id="e6590-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-967">Развертывание на основе ручного intune.</span><span class="sxs-lookup"><span data-stu-id="e6590-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-968">Развертывание на основе JAMF.</span><span class="sxs-lookup"><span data-stu-id="e6590-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="e6590-969">Другое развертывание на основе продуктов для управления мобильными устройствами (MDM).</span><span class="sxs-lookup"><span data-stu-id="e6590-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-970">Ручное развертывание.</span><span class="sxs-lookup"><span data-stu-id="e6590-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="e6590-971">Конфигурация следующих возможностей сокращения направлений атак:</span><span class="sxs-lookup"><span data-stu-id="e6590-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-972">Аппаратная изоляция.</span><span class="sxs-lookup"><span data-stu-id="e6590-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-973">Управление приложениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="e6590-974">Управление устройствами.</span><span class="sxs-lookup"><span data-stu-id="e6590-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="e6590-975">Защита от эксплойтов.</span><span class="sxs-lookup"><span data-stu-id="e6590-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-976">Сетевой брандмауэр.</span><span class="sxs-lookup"><span data-stu-id="e6590-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="e6590-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="e6590-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="e6590-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="e6590-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="e6590-979">Конфигурация или управление BitLocker.</span><span class="sxs-lookup"><span data-stu-id="e6590-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="e6590-980">Развертывание или конфигурация экспертов Майкрософт по угрозам.</span><span class="sxs-lookup"><span data-stu-id="e6590-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="e6590-981">Настройка или обучение, просмотр API или сведений о безопасности и подключений к управлению событиями (SIEM).</span><span class="sxs-lookup"><span data-stu-id="e6590-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="e6590-982">Развертывание или конфигурация защиты от угроз (Майкрософт).</span><span class="sxs-lookup"><span data-stu-id="e6590-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="e6590-983">Учебные курсы или руководства по расширенной охоте.</span><span class="sxs-lookup"><span data-stu-id="e6590-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="e6590-984">Учебные материалы или руководства по использованию или созданию запросов Kusto.</span><span class="sxs-lookup"><span data-stu-id="e6590-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="e6590-985">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e6590-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="e6590-986">Виртуальный рабочий стол Windows</span><span class="sxs-lookup"><span data-stu-id="e6590-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-987"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-988"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-989"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="e6590-990"><strong>Виртуальный рабочий стол Windows</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="e6590-991">Мы предоставляем рекомендации по развертыванию для внедрения в Windows Virtual Desktop (служба виртуализации настольных компьютеров и приложений).</span><span class="sxs-lookup"><span data-stu-id="e6590-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="e6590-992">Виртуальный рабочий стол Windows 10 с несколькими сеансами и оптимизирован для Microsoft 365 Apps для предприятия с интегрированной безопасностью и управлением для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="e6590-993">Мы предоставляем удаленные рекомендации по:</span><span class="sxs-lookup"><span data-stu-id="e6590-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="e6590-994">Развертывание среды виртуальных настольных компьютеров Windows с несколькими сеансами Windows 10 Корпоративный и Microsoft 365 Apps для предприятия с помощью следующих ниже.</span><span class="sxs-lookup"><span data-stu-id="e6590-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="e6590-995">Azure Marketplace Image.</span><span class="sxs-lookup"><span data-stu-id="e6590-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="e6590-996">Общий образ.</span><span class="sxs-lookup"><span data-stu-id="e6590-996">Shared image.</span></span></li>
<li><span data-ttu-id="e6590-997">Развертывание office набор средств (ODT).</span><span class="sxs-lookup"><span data-stu-id="e6590-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="e6590-998">Настройка FSLogix:</span><span class="sxs-lookup"><span data-stu-id="e6590-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="e6590-999">Развертывание агента FSLogix с контейнером профилей.</span><span class="sxs-lookup"><span data-stu-id="e6590-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="e6590-1000">Развертывание агента FSLogix с контейнером Office.</span><span class="sxs-lookup"><span data-stu-id="e6590-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="e6590-1001">Настройка папки FSLogix с исключениями контента.</span><span class="sxs-lookup"><span data-stu-id="e6590-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="e6590-1002">Развертывание Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="e6590-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="e6590-1003">Развертывание Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="e6590-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="e6590-1004">Подключение с помощью клиентов Виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="e6590-1005">

<strong>Ниже приводится неосякаемая область</strong>
</span><span class="sxs-lookup"><span data-stu-id="e6590-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="e6590-1006">Управление проектами развертывания виртуального рабочего стола клиента с Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="e6590-1007">Виртуализация и развертывание сторонних приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="e6590-1008">Настраиваемые изображения.</span><span class="sxs-lookup"><span data-stu-id="e6590-1008">Custom images.</span></span></li>
<li><span data-ttu-id="e6590-1009">Миграции и сценарии с участием VMware и Citrix.</span><span class="sxs-lookup"><span data-stu-id="e6590-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="e6590-1010">Сценарии Linux.</span><span class="sxs-lookup"><span data-stu-id="e6590-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="e6590-1011">Преобразование или миграция профилей пользователей.</span><span class="sxs-lookup"><span data-stu-id="e6590-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="e6590-1012">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e6590-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="e6590-1013">У вас уже должно быть следующее:</span><span class="sxs-lookup"><span data-stu-id="e6590-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="e6590-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Требования к лицензированию виртуальных настольных компьютеров</a>Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="e6590-1015">Сеть Azure:</span><span class="sxs-lookup"><span data-stu-id="e6590-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="e6590-1016">Создание и подсети виртуальной сети (VNET).</span><span class="sxs-lookup"><span data-stu-id="e6590-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="e6590-1017">Брандмауэр и группы сетевой безопасности.</span><span class="sxs-lookup"><span data-stu-id="e6590-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="e6590-1018">VPN и ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="e6590-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="e6590-1019">Маршрутная маршрутивка в Azure из локального помещения.</span><span class="sxs-lookup"><span data-stu-id="e6590-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="e6590-1020">Правила брандмауэра, позволяющие подключаться к Виртуальному рабочему столу Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="e6590-1021">Дополнительные сведения см. в <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">веб-версии Поддерживаемые клиенты удаленного рабочего стола.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="e6590-1022">Общая настройка Azure AD:</span><span class="sxs-lookup"><span data-stu-id="e6590-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="e6590-1023">Стратегия <i>удостоверения (можно использовать только один из следующих трех вариантов):</i>
</span><span class="sxs-lookup"><span data-stu-id="e6590-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="e6590-1024">Active Directory с Azure AD Connect в Azure.</span><span class="sxs-lookup"><span data-stu-id="e6590-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="e6590-1025">Active Directory с локальной сетью Azure AD Connect через VPN или ExpressRoute.</span><span class="sxs-lookup"><span data-stu-id="e6590-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="e6590-1026">Службы домена Active Directory (AD DS).</span><span class="sxs-lookup"><span data-stu-id="e6590-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="e6590-1027">App Assure</span><span class="sxs-lookup"><span data-stu-id="e6590-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-1028"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-1029"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-1030"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e6590-1031"><strong>App Assure</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="e6590-1032">App Assure — это служба, предназначенная для решения проблем с совместимостью приложений Windows 10 и Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e6590-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="e6590-1033">При запросе службы App Assure мы работаем с вами для решения проблем с допустимым приложением без каких-либо дополнительных затрат для вас с помощью доступной подписки.</span><span class="sxs-lookup"><span data-stu-id="e6590-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="e6590-1034">Мы также предоставляем рекомендации для клиентов, сталкивающихся с вопросами совместимости при развертывании Windows Virtual Desktop и Microsoft Edge, и прилоя все разумные усилия для решения проблем совместимости.</span><span class="sxs-lookup"><span data-stu-id="e6590-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="e6590-1035">Мы предоставляем помощь в исправлении приложений, развернутых в следующих продуктах Майкрософт:</span><span class="sxs-lookup"><span data-stu-id="e6590-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="e6590-1036"><strong>Windows 10 </strong> (включая устройства ARM64)</span><span class="sxs-lookup"><span data-stu-id="e6590-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="e6590-1037"><strong>Приложения Microsoft 365</strong>  </span><span class="sxs-lookup"><span data-stu-id="e6590-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="e6590-1038"><strong>Microsoft Edge —</strong> Сведения о развертывании <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">см. в обзоре каналов Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="e6590-1039"><strong>Виртуальный рабочий стол Windows</strong> - Дополнительные сведения см. в дополнительных сведениях о том, что такое <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">виртуальный настольный компьютер Windows?</a> и много сеансов <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">для Windows 10 Enterprise.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="e6590-1040">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-p147">Изучение и тестирование приложения с целью определения того, какие функции поддерживаются и не поддерживаются в Windows 10 и приложениях Microsoft 365. Дополнительные руководства по этому процессу см. на странице <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Центр развертывания компьютеров</a>. Если вас интересует глубокая оценка готовности к обновлению, заполните форму <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Запрос клиента на оценку современных компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="e6590-p147">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps. For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>. If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="e6590-1044">Анализ приложений независимых поставщиков программного обеспечения (ISV) на совместимость с Windows 10 и сведений о поддержке.</span><span class="sxs-lookup"><span data-stu-id="e6590-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="e6590-1045">Дополнительные сведения см. в разделе <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Аналитика компьютеров</a>.</span><span class="sxs-lookup"><span data-stu-id="e6590-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="e6590-1046">Услуги по упаковке приложений.</span><span class="sxs-lookup"><span data-stu-id="e6590-1046">App packaging-only services.</span></span> <span data-ttu-id="e6590-1047">Команда App Assure упаковывает приложения, исправленные для Windows 10, чтобы обеспечить возможность их развертывания в среде клиента.</span><span class="sxs-lookup"><span data-stu-id="e6590-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="e6590-1048">

<strong>Обязанности клиента включают в себя</strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="e6590-1049">Создание ведомости приложения</span><span class="sxs-lookup"><span data-stu-id="e6590-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="e6590-1050">Проверки работы данных приложений в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="e6590-1051">
<strong>Примечание:</strong>  Корпорация Майкрософт не может вносить изменения в исходный код.</span><span class="sxs-lookup"><span data-stu-id="e6590-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="e6590-1052">Однако команда App Assure предоставляет руководство для разработчиков приложений, если для приложений доступен исходный код.</span><span class="sxs-lookup"><span data-stu-id="e6590-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="e6590-1053">Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</span><span class="sxs-lookup"><span data-stu-id="e6590-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="e6590-1054"><strong>Windows 10 и Microsoft 365 Apps</strong>
</span><span class="sxs-lookup"><span data-stu-id="e6590-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-1055">Приложения, работающие в Windows 7, Windows 8,1, Office 2010 и Office 2013, также работают в Windows 10 и приложениях Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="e6590-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-1056">
<strong>Windows 10 на ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="e6590-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="e6590-1057">Приложения, которые работали в Windows 7, Office 2010 или более поздних версиях, также работают на устройствах с Windows 10 и Microsoft 365 Apps на устройствах ARM64.</span><span class="sxs-lookup"><span data-stu-id="e6590-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="e6590-1058">
  <strong>Примечание:</strong> 
</span><span class="sxs-lookup"><span data-stu-id="e6590-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="e6590-1059">Эмуляция x64 (64-bit) доступна в предварительном режиме для клиентов, участвующих в <a href="https://insider.windows.com/">программе предварительного просмотра Windows.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="e6590-1060">Для пользователей, не использующих Windows Insider в Windows 10 версии 2004 (или более поздней версии), photoshop ARM64 поддерживается с помощью <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">пакета совместимости OpenCL и OpenGL.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="e6590-1061">Пользователи программы инсайдерской windows могут скачать внутреннюю версию пакета совместимости OpenCL и OpenGL для использования с дополнительными приложениями.</span><span class="sxs-lookup"><span data-stu-id="e6590-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="e6590-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="e6590-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-1063">Если веб-приложения или сайты работают в Internet Explorer 11, поддерживаемых версиях Google Chrome или любой версии Microsoft Edge, они также будут работать с Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="e6590-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-1064">Поскольку веб-сайт постоянно развивается, обязательно просмотрите опубликованный список известных изменений, которые влияют на совместимость <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">веб-сайтов для Microsoft Edge.</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-1065">
  <strong>Виртуальный рабочий стол Windows </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="e6590-1066">Виртуализованные приложения, работающие на узле сеансов удаленных рабочих столов в Windows Server, также работают в Windows 10 Корпоративная с поддержкой нескольких сеансов в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-1067">Приложения, работающие в любой среде виртуальной инфраструктуры настольных компьютеров Windows 7 или Windows 10, также работают на Windows 7 Корпоративная и Windows 10 Enterprise в рамках Windows Virtual Desktop.</span><span class="sxs-lookup"><span data-stu-id="e6590-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-1068">Приложения, работающие на клиентских устройствах Windows 7 или Windows 10, также работают в Windows 7 Корпоративная и Windows 10 Корпоративная в рамках виртуального рабочего стола Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="e6590-1069">
  <strong>Примечание:</strong> Исключения и ограничения совместимости с несколькими сеансами Windows 10 Enterprise включают следующие:</span><span class="sxs-lookup"><span data-stu-id="e6590-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="e6590-1070">Ограниченное перенаправление оборудования.</span><span class="sxs-lookup"><span data-stu-id="e6590-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-1071">Приложения с интенсивным использованием A/V могут работать с уменьшенной производительностью.</span><span class="sxs-lookup"><span data-stu-id="e6590-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="e6590-1072">16-разрядные приложения не поддерживаются в 64-разрядных виртуальных рабочих столах Windows.</span><span class="sxs-lookup"><span data-stu-id="e6590-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="e6590-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="e6590-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="e6590-1074"><strong>Служба</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="e6590-1075"><strong>Сведения о руководстве FastTrack</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="e6590-1076"><strong>Ожидания среды исходных источников</strong></span><span class="sxs-lookup"><span data-stu-id="e6590-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="e6590-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="e6590-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="e6590-1078">Мы предоставляем рекомендации по удаленному развертыванию и принятию и совместимости для:</span><span class="sxs-lookup"><span data-stu-id="e6590-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="e6590-1079">Развертывание Microsoft Edge в Windows 10 с помощью Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager или Intune).</span><span class="sxs-lookup"><span data-stu-id="e6590-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="e6590-1080">Настройка Microsoft Edge (с помощью групповых политик или конфигурации приложений Intune и политик приложений).</span><span class="sxs-lookup"><span data-stu-id="e6590-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="e6590-1081">Инвентаризация списка сайтов, которые могут потребовать использования в режиме Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="e6590-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="e6590-1082">Включение режима Internet Explorer в существующем списке корпоративных сайтов.</span><span class="sxs-lookup"><span data-stu-id="e6590-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="e6590-1083">(Дополнительные сведения см. в <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">странице Engaging FastTrack).</a></span><span class="sxs-lookup"><span data-stu-id="e6590-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="e6590-1084">Кроме того, если у вас есть веб-приложение или сайт, который работает с Internet Explorer или Google Chrome и вы испытываете проблемы с совместимостью, мы предоставляем рекомендации по устранению проблемы без дополнительных затрат.</span><span class="sxs-lookup"><span data-stu-id="e6590-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="e6590-1085">Чтобы запросить поддержку совместимости для App Assure, вопишитесь на портал <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack,</a> чтобы начать взаимодействие.</span><span class="sxs-lookup"><span data-stu-id="e6590-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="e6590-1086">Планирование руководства по внедрению edge и настройке закладки Microsoft Search.</span><span class="sxs-lookup"><span data-stu-id="e6590-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="e6590-1087">

<strong>Ниже приводится неосякаемая область </strong>  
</span><span class="sxs-lookup"><span data-stu-id="e6590-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="e6590-1088">Управление проектами по развертыванию Microsoft Edge для клиентов.</span><span class="sxs-lookup"><span data-stu-id="e6590-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="e6590-1089">Поддержка на месте.</span><span class="sxs-lookup"><span data-stu-id="e6590-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
