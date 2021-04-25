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
description: FastTrack предоставляет рекомендации по развертыванию виртуальных настольных компьютеров Windows, чтобы помочь вам на борту этого рабочего стола.
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996242"
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
<td><p>FastTrack предоставляет рекомендации по развертыванию виртуальных настольных компьютеров Windows, чтобы помочь вам в этой службе виртуализации настольных компьютеров и приложений с легкостью использовать много сеансы Windows 10, оптимизированные для Microsoft 365 Apps для предприятия с интегрированной безопасностью и управлением для Microsoft 365.</p>
<p>Вы работаете со специалистами FastTrack, чтобы:</p>
<ul>
<li><p>Развертывание среды WVD с несколькими сеансами Windows 10 Enterprise + Microsoft 365 Apps для предприятия с помощью следующих ниже.</p>
<ul>
<li><p>Azure Marketplace Image</p></li>
<li><p>Общий образ</p></li>
<li><p>Развертывание office набор средств (ODT)</p></li>
</ul></li>
<li><p>Настроить FSLogic</p>
<ul>
<li><p>Развертывание агента FSLogix с контейнером профилей</p></li>
<li><p>Развертывание агента FSLogix с контейнером Office</p></li>
<li><p>Настройка папки FSLogix с исключениями контента</p></li>
</ul></li>
<li><p>Развертывание Microsoft Edge</p></li>
<li><p>Развертывание Microsoft Teams</p></li>
<li><p>Подключение с помощью виртуальных клиентов настольных компьютеров Windows</p></li>
</ul>
<p><strong>Ниже приводится неосякаемая область</strong></p>
<ul>
<li><p>Управление проектами развертывания виртуального рабочего стола клиента с Windows.</p></li>
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
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Требования к лицензированию WVD</a></p></li>
<li><p>Azure Networking:</p>
<ul>
<li><p>Подсети создания &amp; VNET</p></li>
<li><p>Брандмауэр / Группы безопасности сети</p></li>
<li><p>VPN / ExpressRoute</p></li>
<li><p>Маршрутиротка в Azure из локальной области</p></li>
<li><p>Правила брандмауэра, позволяющие подключаться к WVD</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Справка по docs</a></p></li>
</ul></li>
</ul></li>
<li><p>Установка общего каталога Azure Active</p>
<ul>
<li><p>Стратегия <strong>удостоверений (Выберите ТОЛЬКО 1 из следующих 3 параметров)</strong></p>
<ul>
<li><p>Active Directory с Подключением Azure AD в Azure</p></li>
<li><p>Active Directory с Azure AD Connect on Premise over VPN /ER</p></li>
<li><p>Доменные службы Active Directory</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
