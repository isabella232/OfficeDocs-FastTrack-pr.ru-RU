---
title: Обзор Преимущества FastTrack Center
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011337"
---
# <a name="fasttrack-center-benefit-overview"></a>Обзор Преимущества FastTrack Center

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Мы рассмотрим следующие темы:
- [Процесс FastTrack](O365-fasttrack-process.md) 
- [Требования к исходной среде](O365-source-environment-expectations.md)
- [Этапы миграции (в том числе входящей)](O365-onboarding-and-migration.md)
- [Миграция данных](O365-data-migration.md)
- [Обязанности специалистов FastTrack](O365-fasttrack-responsibilities.md)
- [Ваши обязанности](O365-your-responsibilities.md) 
- [Приложение А. Дополнительное преимущество FastTrack Center](O365-fasttrack-additional-benefits.md)
- [Приложение Б. Соглашение HIPAA-BAA для FastTrack Center](O365-hipaa-business-associate-agreement.md)
- [Приложение В. Обзор преимущества FastTrack Center для Office 365 для государственных организаций США](US-Gov-appendix-overview.md)
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- Облачные удостоверения с уникальными учетными записями Office 365.
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - Среда с одним лесом Active Directory.
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
- Федеративные удостоверения с учетными записями Office 365, которые:
  - Синхронизированные из Active Directory с помощью средства Azure Active Directory Connect для пользователей, применяющих указанные ниже конфигурации.
      - в конфигурации с одним лесом Active Directory.
      - конфигурации с одним лесом учетных записей Active Directory (т. н. "лесом входа") и одним лесом ресурсов Active Directory.
  - Настроены с использованием локальной инфраструктуры служб федерации Active Directory (AD FS).
      - Объединение с ролью AD FS Windows Server 2012 R2 и более поздних версий из локальной службы Active Directory.
      - При необходимости роль прокси приложения (WAP) Windows Server 2012 R2 и более поздних версий используется для публикации локальной инфраструктуры AD FS в Интернете.
    > [!NOTE]
    > Развертывание и настройка AD FS и WAP выполняются с помощью [мастера конфигурации Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) в локальной среде. 
  
- [Службы и планы](M365-eligible-services-and-plans.md), доступные лицензированным пользователям.

