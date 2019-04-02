---
title: Ожидание исходной среды
description: Требования к исходной среде для использования преимуществ FastTrack Center для EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0d0fa0415bc27013d7e035b75a5e5d9d9f9919c3
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016771"
---
# <a name="source-environment-expectations"></a>Требования к исходной среде

При использовании [преимуществ FastTrack Center для Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) для получения Microsoft Azure Active Directory Premium и готовности Microsoft Intune к использованию среда должна соответствовать ожиданиям, описанным в следующих разделах.

Возможно, у вас уже есть локальная служба Active Directory в Организации, которую необходимо интегрировать с Enterprise Mobility + Security (EMS) или любой из ее отдельных служб, использующих расширенное управление удостоверениями с одной консоли. Преимущества FastTrack Center для Enterprise Mobility + Security (EMS) помогут вам интегрировать Azure Active Directory с существующей локальной средой Active Directory.

В следующей таблице показаны ожидания для существующей исходной среды для встроенной среды.

|Действие|Требование к исходной среде|
|------------|----------------------------------|
|Базовые системные подключения|Леса Active Directory с функциональным уровнем леса, настроенным на Windows Server 2008 или более поздней версии, с использованием следующей конфигурации леса:<br /><br />— Один лес Active Directory<br />— Несколько лесов Active Directory; </br></br>**Примечание**. для всех конфигураций с несколькими лесами развертывание служб федерации Active Directory (AD FS) выходит за рамки FastTrack Center.|
|Встроенная служба Azure AD Premium|Локальная служба Active Directory и ее среда подготовлены к Azure AD Premium, которая включает исправление определенных проблем, препятствующих интеграции с Azure AD и функциями Azure AD Premium.|
|Локальная серверная плата Intune| ИТ-администраторы должны иметь существующие инфраструктуры центра сертификации, WiFi и VPN, уже работающие в рабочих средах при планировании развертывания профилей WiFi и VPN с помощью Intune.<br /><br /> **Note**: преимущества службы не включают в себя помощь по настройке или настройке центров сертификации, WiFi, инфраструктур VPN или Push-уведомлений Apple MDM для  |
|Управление|ИТ-администраторы несут ответственность за подготовку локальной среды, которая может включать исправление проблем, которые не позволяют одновременно управлять устройствами с Windows 10 с помощью Configuration Manager и Intune.<br /><br />**Note**: служба FastTrack не включает в себя помощь по настройке или обновлению сервера сайта Configuration Manager и/или клиента Configuration Manager до минимальных требований, необходимых для поддержки совместного управления устройствами с Windows 10. |
|Интеграция Intune с Advanced Threat Protection в Защитнике Windows (Защитник Windows ATP)|Подписка на пакет ATP для защитника Windows активирована и настроена в соответствии с требованиями безопасности компании.<br /><br />**Note**: служба FastTrack предоставляет помощь по интеграции Intune с защитником Windows ATP и созданию политик соответствия требованиям к устройствам на основе оценки уровня риска Windows 10. Преимущества службы FastTrack не предоставляют помощь по приобретению, лицензированию, активации или использованию пакета ATP для защитника Windows и его консоли безопасности. |
|Windows Autopilot|ИТ – администраторы отвечают за регистрацию своих устройств в Организации, получив поставщик оборудования на отправку идентификаторов оборудования от их имени или отправив их в службу Windows автопилота. |
|Безопасная установка Outlook для iOS и Android с помощью Intune|<br /><br />— Удостоверения пользователей, включенные в Azure AD для Office 365.<br />— Exchange Online или гибридный Exchange, настроенный с назначенными лицензиями пользователей.<br />|

> [!NOTE]
> **Хотите узнать больше?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Дальнейшие действия

[Преимущества FastTrack Center для фаз входящей миграции EMS](EMS-onboarding-phases.md)
