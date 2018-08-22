---
title: Обзор Преимущества FastTrack Center
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 8/2/18
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Если вы используете Преимущество FastTrack Center для Office 365, специалисты FastTrack удаленно подготовят среду Office 365 к использованию, а также спланируют ее развертывание и использование в вашей организации. Дополнительные сведения о требованиях программы см. в статье "Преимущество FastTrack Center для Office 365".
ms.openlocfilehash: 4b54fd05314f9eac96b6f3781e14e988e1282c6c
ms.sourcegitcommit: 7865f572bf312a6ec49f72981d983c6370f34b11
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/10/2018
ms.locfileid: "22449133"
---
# <a name="fasttrack-center-benefit-overview"></a>Обзор Преимущества FastTrack Center

Если вы используете Преимущество FastTrack Center для Office 365, специалисты FastTrack удаленно подготовят среду Office 365 к использованию, а также спланируют ее развертывание и использование в вашей организации. Дополнительные сведения о требованиях программы см. в статье [Преимущество FastTrack Center для Office 365](fasttrack-benefit-for-office-365.md).
  
Мы рассмотрим следующие темы:
  
- [Процесс FastTrack](fasttrack-process.md)
    
- [Требования к исходной среде](source-environment-expectations.md)
    
- [Этапы миграции (в том числе входящей)](onboarding-and-migration.md)
    
- [Миграция данных](data-migration.md)
    
- [Обязанности специалистов FastTrack](fasttrack-responsibilities.md)
    
- [Ваши обязанности](your-responsibilities.md)
    
- [Приложение А. Миграция с IBM Domino в Exchange Online](from-ibm-domino-to-exchange-online.md)
    
- [Приложение Б. Дополнительное преимущество FastTrack Center](fasttrack-additional-benefits.md)
    
По завершении входящей миграции будет создан клиент Office 365:. Пользователи с лицензиями могут получить доступ к Office 365: с помощью одного из указанных ниже вариантов удостоверений.
  
- Облачные удостоверения с уникальными учетными записями Office 365.
    
- Синхронизированные удостоверения с учетными записями Office 365:, синхронизируемыми из локальной службы Active Directory с помощью Azure Active Directory Connect (синхронизация хэшей паролей или сквозная проверка подлинности). Они предназначены для указанных ниже пользователей.
    
  - Среда с одним лесом Active Directory.
    
  - Поддерживаемая топология с несколькими лесами Active Directory. Список поддерживаемых топологий см. в статье [Требования к исходной среде](source-environment-expectations.md).
    
- Федеративные удостоверения с учетными записями Office 365, которые:
    
  - Синхронизированные из Active Directory с помощью средства Azure Active Directory Connect для пользователей, применяющих указанные ниже конфигурации.
    
      - в конфигурации с одним лесом Active Directory.
    
      - конфигурации с одним лесом учетных записей Active Directory (т. н. "лесом входа") и одним лесом ресурсов Active Directory.
    
  - Настроены с использованием локальной инфраструктуры служб федерации Active Directory (AD FS).
    
      - Объединение с ролью AD FS Windows Server 2012 R2 и более поздних версий из локальной службы Active Directory.
    
      - При необходимости роль прокси приложения (WAP) Windows Server 2012 R2 и более поздних версий используется для публикации локальной инфраструктуры AD FS в Интернете.
    
    > [!NOTE]
    > Развертывание и настройка AD FS и WAP выполняются с помощью [мастера конфигурации Azure AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) в локальной среде. 
  
- [Службы и планы](eligible-services-and-plans.md), доступные лицензированным пользователям.
    

 
