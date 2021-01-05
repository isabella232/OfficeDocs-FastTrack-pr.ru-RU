---
title: Перенос данных
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750046"
---
# <a name="data-migration"></a><span data-ttu-id="edd7b-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="edd7b-104">Data Migration</span></span>

<span data-ttu-id="edd7b-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="edd7b-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="edd7b-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="edd7b-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="edd7b-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="edd7b-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="edd7b-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="edd7b-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="edd7b-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="edd7b-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-111">You create and schedule your migration events.</span></span> <span data-ttu-id="edd7b-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="edd7b-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="edd7b-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="edd7b-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="edd7b-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="edd7b-115">Considerations</span></span>

  - <span data-ttu-id="edd7b-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="edd7b-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="edd7b-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="edd7b-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="edd7b-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="edd7b-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="edd7b-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="edd7b-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="edd7b-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="edd7b-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="edd7b-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="edd7b-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="edd7b-124">Migration service availability</span></span>

  - <span data-ttu-id="edd7b-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="edd7b-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="edd7b-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="edd7b-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="edd7b-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="edd7b-127">Migration to Exchange Online</span></span>

<span data-ttu-id="edd7b-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="edd7b-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="edd7b-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="edd7b-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-130">You create and schedule your migration events.</span></span> <span data-ttu-id="edd7b-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="edd7b-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="edd7b-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="edd7b-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="edd7b-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="edd7b-133">Considerations</span></span>

  - <span data-ttu-id="edd7b-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="edd7b-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="edd7b-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="edd7b-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="edd7b-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="edd7b-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="edd7b-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="edd7b-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="edd7b-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="edd7b-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="edd7b-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="edd7b-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="edd7b-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="edd7b-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="edd7b-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="edd7b-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="edd7b-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="edd7b-143">Source environments</span></span>

<span data-ttu-id="edd7b-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="edd7b-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="edd7b-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="edd7b-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="edd7b-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="edd7b-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="edd7b-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="edd7b-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="edd7b-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="edd7b-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="edd7b-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="edd7b-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="edd7b-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="edd7b-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="edd7b-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="edd7b-154">
<strong>Примечание.</strong> Для зависимостей локальной службы Exchange см. необходимые условия <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">для гибридного развертывания.</span></a></span><span class="sxs-lookup"><span data-stu-id="edd7b-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="edd7b-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="edd7b-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="edd7b-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="edd7b-156">Emails</span></span></li>
<li><span data-ttu-id="edd7b-157">Правила для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="edd7b-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="edd7b-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="edd7b-158">Delegates</span></span></li>
<li><span data-ttu-id="edd7b-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="edd7b-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="edd7b-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="edd7b-160">Calendar</span></span> </li>
<li> <span data-ttu-id="edd7b-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="edd7b-161">Tasks</span></span> </li>
<li> <span data-ttu-id="edd7b-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="edd7b-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="edd7b-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="edd7b-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="edd7b-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="edd7b-164">Signatures</span></span> </li>
<li> <span data-ttu-id="edd7b-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="edd7b-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="edd7b-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="edd7b-167">Public folders</span></span> </li>
<li> <span data-ttu-id="edd7b-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="edd7b-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="edd7b-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="edd7b-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="edd7b-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="edd7b-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="edd7b-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="edd7b-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="edd7b-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="edd7b-174"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="edd7b-175">
<strong>Примечание.</strong> Среда G Suite должна соответствовать предварительным требованиям, описанным в описании миграции <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="edd7b-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="edd7b-176">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-177">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="edd7b-177">Emails</span></span> </li>
<li> <span data-ttu-id="edd7b-178">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="edd7b-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="edd7b-179">Календарь</span><span class="sxs-lookup"><span data-stu-id="edd7b-179">Calendar</span></span> </li>
<li> <span data-ttu-id="edd7b-180">Метки</span><span class="sxs-lookup"><span data-stu-id="edd7b-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-181">Правила</span><span class="sxs-lookup"><span data-stu-id="edd7b-181">Rules</span></span> </li>
<li> <span data-ttu-id="edd7b-182">Делегаты</span><span class="sxs-lookup"><span data-stu-id="edd7b-182">Delegates</span></span> </li>
<li> <span data-ttu-id="edd7b-183">Подписи</span><span class="sxs-lookup"><span data-stu-id="edd7b-183">Signatures</span></span> </li>
<li> <span data-ttu-id="edd7b-184">Задачи</span><span class="sxs-lookup"><span data-stu-id="edd7b-184">Tasks</span></span> </li>
<li> <span data-ttu-id="edd7b-185">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="edd7b-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="edd7b-186">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-187">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="edd7b-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="edd7b-188">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="edd7b-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="edd7b-189">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="edd7b-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="edd7b-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="edd7b-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="edd7b-191">Группы Google</span><span class="sxs-lookup"><span data-stu-id="edd7b-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="edd7b-192">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="edd7b-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="edd7b-193">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="edd7b-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="edd7b-194">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="edd7b-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="edd7b-195">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="edd7b-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="edd7b-196">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="edd7b-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="edd7b-197"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="edd7b-198">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="edd7b-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="edd7b-199">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="edd7b-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="edd7b-200">Правила</span><span class="sxs-lookup"><span data-stu-id="edd7b-200">Rules</span></span> </li>
<li> <span data-ttu-id="edd7b-201">Делегаты</span><span class="sxs-lookup"><span data-stu-id="edd7b-201">Delegates</span></span> </li>
<li> <span data-ttu-id="edd7b-202">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="edd7b-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="edd7b-203">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="edd7b-203">External contacts</span></span> </li>
<li> <span data-ttu-id="edd7b-204">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="edd7b-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="edd7b-205">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-206">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="edd7b-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="edd7b-207">Календарь</span><span class="sxs-lookup"><span data-stu-id="edd7b-207">Calendar</span></span> </li>
<li> <span data-ttu-id="edd7b-208">Подписи</span><span class="sxs-lookup"><span data-stu-id="edd7b-208">Signatures</span></span> </li>
<li> <span data-ttu-id="edd7b-209">Задачи</span><span class="sxs-lookup"><span data-stu-id="edd7b-209">Tasks</span></span> </li>
<li> <span data-ttu-id="edd7b-210">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="edd7b-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="edd7b-211">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="edd7b-211">Archive data</span></span> </li>
<li> <span data-ttu-id="edd7b-212">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="edd7b-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="edd7b-213">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="edd7b-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="edd7b-214">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="edd7b-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="edd7b-215">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="edd7b-215">FastTrack responsibilities</span></span>

<span data-ttu-id="edd7b-216">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-217">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="edd7b-218">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="edd7b-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="edd7b-219">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="edd7b-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="edd7b-220">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="edd7b-220">Your responsibilities</span></span>

<span data-ttu-id="edd7b-221">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-222">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="edd7b-223">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="edd7b-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="edd7b-224">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="edd7b-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="edd7b-225">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="edd7b-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="edd7b-226">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="edd7b-227">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="edd7b-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="edd7b-228">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="edd7b-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="edd7b-229">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="edd7b-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="edd7b-230">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="edd7b-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="edd7b-231">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="edd7b-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="edd7b-232">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="edd7b-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="edd7b-233">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="edd7b-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="edd7b-234">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="edd7b-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="edd7b-235">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="edd7b-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="edd7b-236">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="edd7b-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="edd7b-237">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="edd7b-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="edd7b-238">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="edd7b-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="edd7b-239">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="edd7b-240">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="edd7b-241">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-241">You create and schedule your migration events.</span></span> <span data-ttu-id="edd7b-242">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="edd7b-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="edd7b-243">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="edd7b-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="edd7b-244">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="edd7b-244">Considerations</span></span>

  - <span data-ttu-id="edd7b-245">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="edd7b-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="edd7b-246">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="edd7b-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="edd7b-247">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="edd7b-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="edd7b-248">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="edd7b-248">Source environment details</span></span>

<span data-ttu-id="edd7b-249">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="edd7b-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="edd7b-250">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="edd7b-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="edd7b-251">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="edd7b-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="edd7b-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="edd7b-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="edd7b-253">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="edd7b-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="edd7b-254">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="edd7b-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="edd7b-255"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="edd7b-256"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="edd7b-257"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="edd7b-258"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="edd7b-259"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="edd7b-260">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-261">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-261">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-262">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-263">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="edd7b-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="edd7b-264">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="edd7b-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="edd7b-265">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-266">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-267">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-267">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-268">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-268">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-269">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-269">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-270">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="edd7b-271">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="edd7b-272">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="edd7b-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="edd7b-273">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="edd7b-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="edd7b-274">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="edd7b-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-275">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="edd7b-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="edd7b-276">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-277">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="edd7b-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="edd7b-278">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="edd7b-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="edd7b-279">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="edd7b-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="edd7b-280">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="edd7b-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="edd7b-281">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="edd7b-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="edd7b-282">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="edd7b-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="edd7b-283">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-284">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="edd7b-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="edd7b-285">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="edd7b-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="edd7b-286">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="edd7b-287"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="edd7b-288">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-289">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="edd7b-290">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-291">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-292">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-293">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-294">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-295">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-295">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-296">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-296">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-297">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-297">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-298">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-299">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="edd7b-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="edd7b-300">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="edd7b-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-301">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-302">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="edd7b-303">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-304">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-305">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="edd7b-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-306">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-307">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-308">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-309">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-310">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-311">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="edd7b-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="edd7b-312">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="edd7b-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="edd7b-313">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="edd7b-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="edd7b-314">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="edd7b-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="edd7b-315">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-316">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-317">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="edd7b-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="edd7b-318">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-319">Файлы, помеченные как ограниченные или не копируемые</span><span class="sxs-lookup"><span data-stu-id="edd7b-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="edd7b-320">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="edd7b-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="edd7b-322">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-323">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-323">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-324">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-325">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-326">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-327">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-328">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-329">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-329">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-330">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-330">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-331">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-331">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-332">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-333">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="edd7b-334">Заметки Box (преобразованные в формат документов Word)</span><span class="sxs-lookup"><span data-stu-id="edd7b-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-335">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-336">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="edd7b-337">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-338">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-339">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-340">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-341">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-342">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-343">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-344">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-345">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="edd7b-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="edd7b-346">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="edd7b-347">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-348">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-349">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="edd7b-350"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="edd7b-351">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-352">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-352">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-353">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-354">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-355">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-356">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-357">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-358">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-358">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-359">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-359">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-360">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-360">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-361">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-362">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="edd7b-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="edd7b-363">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-364">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-365">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="edd7b-366">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-367">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-368">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="edd7b-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-369">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-370">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-371">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-372">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-373">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="edd7b-374">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="edd7b-375">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="edd7b-376">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="edd7b-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="edd7b-377">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="edd7b-378">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-379">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="edd7b-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="edd7b-380">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="edd7b-381">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="edd7b-381">FastTrack responsibilities</span></span>

<span data-ttu-id="edd7b-382">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-383">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="edd7b-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="edd7b-384">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="edd7b-384">Your responsibilities</span></span>

<span data-ttu-id="edd7b-385">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-386">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="edd7b-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="edd7b-387">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="edd7b-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="edd7b-388">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="edd7b-389">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="edd7b-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="edd7b-390">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="edd7b-391">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="edd7b-392">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="edd7b-392">You create and schedule your migration events.</span></span> <span data-ttu-id="edd7b-393">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="edd7b-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="edd7b-394">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="edd7b-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="edd7b-395">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="edd7b-395">Considerations</span></span>

  - <span data-ttu-id="edd7b-396">На все миграции распространяются квоты OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="edd7b-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="edd7b-397">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="edd7b-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="edd7b-398">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="edd7b-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="edd7b-399">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="edd7b-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="edd7b-400">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="edd7b-400">Source environment details</span></span>

<span data-ttu-id="edd7b-401">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="edd7b-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="edd7b-402">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="edd7b-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="edd7b-403">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="edd7b-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="edd7b-404">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="edd7b-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="edd7b-405">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="edd7b-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="edd7b-406">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="edd7b-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="edd7b-407"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="edd7b-408"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="edd7b-409"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="edd7b-410"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="edd7b-411"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="edd7b-412">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-413">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-413">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-414">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-415">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="edd7b-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="edd7b-416">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="edd7b-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="edd7b-417">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-418">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-419">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-419">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-420">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-420">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-421">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-421">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-422">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="edd7b-423">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="edd7b-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="edd7b-424">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="edd7b-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="edd7b-425">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="edd7b-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="edd7b-426">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="edd7b-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="edd7b-427">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="edd7b-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="edd7b-428">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-429">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="edd7b-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="edd7b-430">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="edd7b-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="edd7b-431">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="edd7b-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="edd7b-432">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="edd7b-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="edd7b-433">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="edd7b-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="edd7b-434">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="edd7b-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="edd7b-435">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-436">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="edd7b-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="edd7b-437">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="edd7b-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="edd7b-438">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="edd7b-439"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="edd7b-440">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-441">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="edd7b-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="edd7b-442">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-443">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-444">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-445">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-446">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-447">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-447">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-448">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-448">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-449">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-449">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-450">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-451">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="edd7b-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="edd7b-452">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="edd7b-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-453">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-454">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="edd7b-455">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-456">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-457">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="edd7b-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-458">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-459">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-460">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-461">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-462">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-463">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="edd7b-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="edd7b-464">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="edd7b-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="edd7b-465">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="edd7b-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="edd7b-466">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="edd7b-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="edd7b-467">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-468">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-469">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="edd7b-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="edd7b-470">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-471">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="edd7b-472"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="edd7b-473">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-474">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-474">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-475">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-476">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-477">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-478">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-479">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-480">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-480">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-481">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-481">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-482">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-482">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-483">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-484">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-485">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-486">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="edd7b-487">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-488">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-489">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-490">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-491">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-492">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-493">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-494">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="edd7b-495">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="edd7b-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="edd7b-496">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="edd7b-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="edd7b-497">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-498">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-499">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="edd7b-500"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="edd7b-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="edd7b-501">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="edd7b-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="edd7b-502">Документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-502">Documents</span></span> </li>
<li> <span data-ttu-id="edd7b-503">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="edd7b-504">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-505">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-506">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="edd7b-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="edd7b-507">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="edd7b-508">Дата создания</span><span class="sxs-lookup"><span data-stu-id="edd7b-508">Created date</span></span> </li>
<li> <span data-ttu-id="edd7b-509">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-509">Modified date</span></span> </li>
<li> <span data-ttu-id="edd7b-510">Автор</span><span class="sxs-lookup"><span data-stu-id="edd7b-510">Created by</span></span> </li>
<li> <span data-ttu-id="edd7b-511">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="edd7b-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="edd7b-512">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="edd7b-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="edd7b-513">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="edd7b-514">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="edd7b-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="edd7b-515">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="edd7b-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="edd7b-516">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="edd7b-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-517">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="edd7b-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="edd7b-518">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="edd7b-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="edd7b-519">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="edd7b-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="edd7b-520">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="edd7b-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="edd7b-521">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="edd7b-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="edd7b-522">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="edd7b-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="edd7b-523">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="edd7b-524">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="edd7b-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="edd7b-525">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="edd7b-526">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="edd7b-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="edd7b-527">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="edd7b-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="edd7b-528">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="edd7b-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="edd7b-529">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="edd7b-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="edd7b-530">Файлы и папки, превышающие текущие <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="edd7b-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="edd7b-531">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="edd7b-531">FastTrack responsibilities</span></span>

<span data-ttu-id="edd7b-532">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-533">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="edd7b-534">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="edd7b-534">Your responsibilities</span></span>

<span data-ttu-id="edd7b-535">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="edd7b-536">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="edd7b-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="edd7b-537">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="edd7b-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="edd7b-538">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="edd7b-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
