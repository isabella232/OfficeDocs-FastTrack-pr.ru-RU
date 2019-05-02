---
title: Процесс FastTrack
description: Обзор процесса входящей миграции FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513778"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="0b868-103">Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)</span><span class="sxs-lookup"><span data-stu-id="0b868-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="0b868-104">Если ваша организация может использовать FastTrack Center для служб EMS, вы можете работать с ними в удаленном режиме с помощью FastTrack-специалистов, чтобы получить Microsoft Azure Active Directory Premium, Microsoft Intune и Azure Information Protection готовы к использованию.</span><span class="sxs-lookup"><span data-stu-id="0b868-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="0b868-105">Вы также можете запросить помощь через [сайт FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) для Azure Information Protection, Microsoft Cloud App Security и Microsoft Advanced Threat Analytics.</span><span class="sxs-lookup"><span data-stu-id="0b868-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics.</span></span> <span data-ttu-id="0b868-106">Чтобы узнать, соответствует ли ваша организация требованиям, ознакомьтесь со статьями [Доступные службы и планы](M365-eligible-services-and-plans.md).</span><span class="sxs-lookup"><span data-stu-id="0b868-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="0b868-107">Мы рассмотрим процесс входящей миграции:</span><span class="sxs-lookup"><span data-stu-id="0b868-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="0b868-108">Общие сведения о процессе входящей миграции</span><span class="sxs-lookup"><span data-stu-id="0b868-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="0b868-109">Ожидания для исходной среды</span><span class="sxs-lookup"><span data-stu-id="0b868-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="0b868-110">Этапы процесса входящей миграции</span><span class="sxs-lookup"><span data-stu-id="0b868-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="0b868-111">[Обязанности FastTrack](EMS-fasttrack-responsibilities.md) для каждого этапа</span><span class="sxs-lookup"><span data-stu-id="0b868-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="0b868-112">[Обязанности клиента](EMS-your-responsibilities.md) для каждого этапа</span><span class="sxs-lookup"><span data-stu-id="0b868-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="0b868-113">При завершении входящей миграции вы можете ожидать:</span><span class="sxs-lookup"><span data-stu-id="0b868-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="0b868-114">Будут созданы клиенты EMS для выбранных служб.</span><span class="sxs-lookup"><span data-stu-id="0b868-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="0b868-115">Лицензированные пользователи могут получить доступ к службам EMS с помощью одного из следующих параметров удостоверения.</span><span class="sxs-lookup"><span data-stu-id="0b868-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="0b868-116">Облачные удостоверения (уникальные учетные записи EMS).</span><span class="sxs-lookup"><span data-stu-id="0b868-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="0b868-117">Синхронизированные удостоверения: учетные записи EMS, синхронизированные из локальной службы Active Directory, с помощью средства Azure Active Directory Connect (синхронизация хэша паролей или сквозная проверка подлинности).</span><span class="sxs-lookup"><span data-stu-id="0b868-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="0b868-118">Этот параметр предназначен для клиентов с одним лесом или несколькими лесами Active Directory.</span><span class="sxs-lookup"><span data-stu-id="0b868-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="0b868-119">Федеративные удостоверения (с учетными записями Майкрософт EMS):</span><span class="sxs-lookup"><span data-stu-id="0b868-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="0b868-120">Синхронизируется из Active Directory с помощью средства Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="0b868-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="0b868-121">Этот параметр предназначен для пользователей с одной конфигурацией леса Active Directory.</span><span class="sxs-lookup"><span data-stu-id="0b868-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="0b868-122">Федеративные службы федерации Active Directory (AD FS) с Windows Server 2012 R2 (AD FS) 2,0 или более поздней версии из локальной службы Active Directory.</span><span class="sxs-lookup"><span data-stu-id="0b868-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="0b868-123">Возможность автоматической классификации и защиты информации как в REST, так и в транзите с помощью Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="0b868-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="0b868-124">Возможность обнаружения сведений в локальных файловых ресурсах и серверах SharePoint с помощью сканера Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="0b868-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="0b868-125">Возможность управления ключами клиента Azure Information Protection в хранилище ключей Azure.</span><span class="sxs-lookup"><span data-stu-id="0b868-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 
