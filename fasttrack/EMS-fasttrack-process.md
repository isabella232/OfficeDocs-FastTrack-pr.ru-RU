---
title: Процесс FastTrack
description: Обзор процесса входящей миграции FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0516035e55bc791645b32ad1819839b6c73f1772
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359843"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="62eb0-103">Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)</span><span class="sxs-lookup"><span data-stu-id="62eb0-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="62eb0-p101">Если ваша организация соответствует преимуществам FastTrack Center для EMS, вы можете работать удаленно с FastTrack, чтобы получить Microsoft Azure Active Directory Premium и Microsoft Intune готов к использованию. Вы также можете запросить помощь через [сайт FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) для Azure Information Protection, Microsoft Cloud App Security и Microsoft Advanced Threat Analytics. Чтобы узнать, соответствует ли ваша организация требованиям, ознакомьтесь со статьями [Доступные службы и планы](M365-eligible-services-and-plans.md).</span><span class="sxs-lookup"><span data-stu-id="62eb0-p101">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use. You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics. To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="62eb0-107">Мы рассмотрим процесс входящей миграции:</span><span class="sxs-lookup"><span data-stu-id="62eb0-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="62eb0-108">Общие сведения о процессе входящей миграции</span><span class="sxs-lookup"><span data-stu-id="62eb0-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   <span data-ttu-id="62eb0-109">[требования к исходной среде](EMS-source-environment-expectations.md);</span><span class="sxs-lookup"><span data-stu-id="62eb0-109">[Expectations for your source environment](EMS-source-environment-expectations.md)</span></span>

-   [<span data-ttu-id="62eb0-110">Этапы процесса входящей миграции</span><span class="sxs-lookup"><span data-stu-id="62eb0-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="62eb0-111">[Обязанности FastTrack](EMS-fasttrack-responsibilities.md) для каждого этапа</span><span class="sxs-lookup"><span data-stu-id="62eb0-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="62eb0-112">[Обязанности клиента](EMS-your-responsibilities.md) для каждого этапа</span><span class="sxs-lookup"><span data-stu-id="62eb0-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="62eb0-113">По завершении входящей миграции вы можете ожидать следующее:</span><span class="sxs-lookup"><span data-stu-id="62eb0-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="62eb0-114">Будут созданы клиенты EMS для выбранных служб.</span><span class="sxs-lookup"><span data-stu-id="62eb0-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="62eb0-115">Лицензированные пользователи могут получить доступ к службам EMS с помощью одного из следующих параметров удостоверения.</span><span class="sxs-lookup"><span data-stu-id="62eb0-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="62eb0-116">Облачные удостоверения (уникальные учетные записи EMS).</span><span class="sxs-lookup"><span data-stu-id="62eb0-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="62eb0-p102">Синхронизированные удостоверения: учетные записи EMS, синхронизированные из локальной службы Active Directory, с помощью средства Azure Active Directory Connect (синхронизация хэша паролей или сквозная проверка поДлинности). Этот параметр предназначен для клиентов с одним лесом или несколькими лесами Active Directory.</span><span class="sxs-lookup"><span data-stu-id="62eb0-p102">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication). This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="62eb0-119">Федеративные удостоверения (с учетными записями Майкрософт EMS):</span><span class="sxs-lookup"><span data-stu-id="62eb0-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="62eb0-p103">Синхронизируется из Active Directory с помощью средства Azure AD Connect. Этот параметр предназначен для пользователей с одной конфигурацией леса Active Directory.</span><span class="sxs-lookup"><span data-stu-id="62eb0-p103">Synchronized from Active Directory with the Azure AD Connect tool. This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="62eb0-122">Федеративные службы федерации Active Directory (AD FS) с Windows Server 2012 R2 (AD FS) 2,0 или более поздней версии из локальной службы Active Directory.</span><span class="sxs-lookup"><span data-stu-id="62eb0-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>
