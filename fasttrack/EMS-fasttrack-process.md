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
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)
Если ваша организация может использовать преимущество FastTrack Center для EMS, вы можете удаленно сотрудничать со специалистами FastTrack для подготовки к использованию служб Microsoft Azure Active Directory Premium, Microsoft Intune и Azure Information Protection. Кроме того, вы можете запросить помощь [на сайте FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) для Azure Information Protection и Microsoft Cloud App Security. Чтобы узнать, отвечает ли ваша организация требованиям, см. статью [Поддерживаемые службы и тарифные планы](M365-eligible-services-and-plans.md).


Рассматриваемые аспекты процесса входящей миграции:

-   [Обзор процесса входящей миграции](EMS-fasttrack-benefit-overview.md)

-   [Требования к исходной среде](EMS-source-environment-expectations.md)

-   [Фазы процесса входящей миграции](EMS-onboarding-phases.md)

-   [Обязанности специалистов FastTrack](EMS-fasttrack-responsibilities.md) на каждой фазе

-   [Обязанности клиента](EMS-your-responsibilities.md) на каждой фазе

По завершении входящей миграции вы можете ожидать следующее:

-   Будут созданы клиенты EMS для выбранных служб.

-   Лицензированные пользователи могут получать доступ к службам EMS с помощью одного из указанных ниже вариантов удостоверений.

    -   Облачные удостоверения (уникальные учетные записи EMS).

    -   Синхронизированные удостоверения: учетные записи EMS, синхронизируемые из локальной службы Active Directory с помощью средства Azure Active Directory Connect (синхронизация хэшей паролей или сквозная проверка подлинности). Эта возможность доступна для клиентов с одним или несколькими лесами Active Directory.

    -   Федеративные удостоверения с учетными записями Microsoft EMS, которые:

        -   Синхронизируются из Active Directory с помощью средства Azure AD Connect. Эта возможность доступна для клиентов с одним лесом Active Directory.

        -   Объединены со службами федерации Active Directory (AD FS) Windows Server 2012 R2 (версии 2.0 или более поздней) из локальной службы Active Directory.

        -   Могут автоматически классифицировать и защищать как хранящиеся, так и передаваемые сведения с помощью службы Azure Information Protection. 

        -   Могут обнаруживать сведения на локальных файловых ресурсах и серверах SharePoint с помощью сканера Azure Information Protection. 

        -   Могут управлять ключами клиента Azure Information Protection в хранилище Azure Key Vault. 
