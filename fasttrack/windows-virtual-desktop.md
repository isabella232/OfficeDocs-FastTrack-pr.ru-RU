---
title: Виртуальный рабочий стол Windows
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack предоставляет Windows для развертывания виртуальных настольных компьютеров, чтобы помочь вам на борту этого рабочего стола.
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592442"
---
# <a name="windows-virtual-desktop"></a>Виртуальный рабочий стол Windows

<table>
<thead>
<tr class="header">
<th><strong>Служба</strong></th>
<th><strong>Сведения о руководстве FastTrack</strong></th>
<th><strong>Требования к исходной среде</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Виртуальный рабочий стол Windows</td>
<td><p>FastTrack предоставляет Windows руководство по развертыванию виртуальных настольных компьютеров, чтобы помочь вам в этой службе виртуализации настольных компьютеров и приложений с легкостью использовать Windows 10 много сеансов, оптимизированные для Приложения Microsoft 365 для Enterprise с интегрированной безопасностью и управлением для Microsoft 365.</p>
<p>Вы работаете со специалистами FastTrack, чтобы:</p>
<ul>
<li><p>Развертывание среды WVD с Windows 10 Корпоративная нескольких сеансов + Приложения Microsoft 365 для Enterprise с помощью следующих ниже.</p>
<ul>
<li><p>Azure Marketplace Image</p></li>
<li><p>Общий образ</p></li>
<li><p>Office Развертывание набор средств (ODT)</p></li>
</ul></li>
<li><p>Настроить FSLogic</p>
<ul>
<li><p>Развертывание агента FSLogix с контейнером профилей</p></li>
<li><p>Развертывание агента FSLogix с Office контейнером</p></li>
<li><p>Настройка папки FSLogix с исключениями контента</p></li>
</ul></li>
<li><p>Развертывание Microsoft Edge</p></li>
<li><p>Развертывание Microsoft Teams</p></li>
<li><p>Подключение с Windows виртуальных настольных клиентов</p></li>
</ul>
<p><strong>Ниже приводится неосякаемая область</strong></p>
<ul>
<li><p>Project управления развертыванием виртуального рабочего стола Windows клиента.</p></li>
<li><p>Поддержка на месте.</p></li>
<li><p>Виртуализация и развертывание сторонних приложений.</p></li>
<li><p>Настраиваемые изображения.</p></li>
<li><p>Миграции и сценарии с участием VMware и Citrix.</p></li>
<li><p>Сценарии Linux.</p></li>
<li><p>Преобразование или миграция профилей пользователей.</p></li>
</ul>
<p>Обратитесь <a href="https://go.microsoft.com/fwlink/?linkid=2080150">к партнеру Майкрософт</a> за помощью в этих службах.</p></td>
<td><p>У вас уже должно быть следующее:</p>
<ul>
<li><p>[Требования к лицензированию WVD](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>Подсети создания &amp; VNET</p></li>
<li><p>Брандмауэр / Группы безопасности сети</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>Маршрутиротка в Azure из локальной области</p></li>
<li><p>Правила брандмауэра, позволяющие подключаться к WVD</p>
<ul>
<li><p>[Справка по docs](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory Общая настройка</p>
<ul>
<li><p>Стратегия <strong>удостоверений (Выберите ТОЛЬКО 1 из следующих 3 параметров)</strong></p>
<ul>
<li><p>Active Directory с azure AD Подключение Azure</p></li>
<li><p>Active Directory с azure AD Подключение локально над VPN / ER</p></li>
<li><p>Доменные службы Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
