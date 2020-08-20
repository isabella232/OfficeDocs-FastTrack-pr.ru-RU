---
title: Процесс FastTrack
description: Обзор процесса входящей миграции с использованием преимущества FastTrack Center
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Normal
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a0fc877fa22f6198e45e212c85ea1234ed19da70
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817260"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Процесс реализации преимущества FastTrack Center для Enterprise Mobility + Security (EMS)

> [!CAUTION]
> Это содержимое больше не является текущим и запланировано на удаление. Для текущего содержимого используйте содержание в панели навигации слева.

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

