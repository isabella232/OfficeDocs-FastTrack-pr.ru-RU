---
title: Процесс FastTrack
description: Обзор процесса входящей миграции с использованием преимущества FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 3/03/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 5ba44a6c06fa8d607bb9587e33e9a4508b4eb48a
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347399"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="6b623-103">Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)</span><span class="sxs-lookup"><span data-stu-id="6b623-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="6b623-104">Если ваша организация может использовать преимущество FastTrack Center для EMS, вы можете удаленно сотрудничать со специалистами FastTrack для подготовки к использованию служб Microsoft Azure Active Directory Premium, Microsoft Intune и Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6b623-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="6b623-105">Кроме того, вы можете запросить помощь [на сайте FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) для Azure Information Protection и Microsoft Cloud App Security.</span><span class="sxs-lookup"><span data-stu-id="6b623-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection and Microsoft Cloud App Security.</span></span> <span data-ttu-id="6b623-106">Чтобы узнать, отвечает ли ваша организация требованиям, см. статью [Поддерживаемые службы и тарифные планы](M365-eligible-services-and-plans.md).</span><span class="sxs-lookup"><span data-stu-id="6b623-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="6b623-107">Рассматриваемые аспекты процесса входящей миграции:</span><span class="sxs-lookup"><span data-stu-id="6b623-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="6b623-108">Обзор процесса входящей миграции</span><span class="sxs-lookup"><span data-stu-id="6b623-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="6b623-109">Требования к исходной среде</span><span class="sxs-lookup"><span data-stu-id="6b623-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="6b623-110">Фазы процесса входящей миграции</span><span class="sxs-lookup"><span data-stu-id="6b623-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="6b623-111">[Обязанности специалистов FastTrack](EMS-fasttrack-responsibilities.md) на каждой фазе</span><span class="sxs-lookup"><span data-stu-id="6b623-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="6b623-112">[Обязанности клиента](EMS-your-responsibilities.md) на каждой фазе</span><span class="sxs-lookup"><span data-stu-id="6b623-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="6b623-113">По завершении входящей миграции вы можете ожидать следующее:</span><span class="sxs-lookup"><span data-stu-id="6b623-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="6b623-114">Будут созданы клиенты EMS для выбранных служб.</span><span class="sxs-lookup"><span data-stu-id="6b623-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="6b623-115">Лицензированные пользователи могут получать доступ к службам EMS с помощью одного из указанных ниже вариантов удостоверений.</span><span class="sxs-lookup"><span data-stu-id="6b623-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="6b623-116">Облачные удостоверения (уникальные учетные записи EMS).</span><span class="sxs-lookup"><span data-stu-id="6b623-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="6b623-117">Синхронизированные удостоверения: учетные записи EMS, синхронизируемые из локальной службы Active Directory с помощью средства Azure Active Directory Connect (синхронизация хэшей паролей или сквозная проверка подлинности).</span><span class="sxs-lookup"><span data-stu-id="6b623-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="6b623-118">Эта возможность доступна для клиентов с одним или несколькими лесами Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6b623-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="6b623-119">Федеративные удостоверения с учетными записями Microsoft EMS, которые:</span><span class="sxs-lookup"><span data-stu-id="6b623-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="6b623-120">Синхронизируются из Active Directory с помощью средства Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="6b623-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="6b623-121">Эта возможность доступна для клиентов с одним лесом Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6b623-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="6b623-122">Объединены со службами федерации Active Directory (AD FS) Windows Server 2012 R2 (версии 2.0 или более поздней) из локальной службы Active Directory.</span><span class="sxs-lookup"><span data-stu-id="6b623-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="6b623-123">Могут автоматически классифицировать и защищать как хранящиеся, так и передаваемые сведения с помощью службы Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6b623-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="6b623-124">Могут обнаруживать сведения на локальных файловых ресурсах и серверах SharePoint с помощью сканера Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="6b623-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="6b623-125">Могут управлять ключами клиента Azure Information Protection в хранилище Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="6b623-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 
