---
title: Перенос данных
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319951"
---
# <a name="data-migration"></a><span data-ttu-id="9cf2a-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="9cf2a-104">Data Migration</span></span>

<span data-ttu-id="9cf2a-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="9cf2a-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="9cf2a-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="9cf2a-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="9cf2a-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="9cf2a-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="9cf2a-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-111">You create and schedule your migration events.</span></span> <span data-ttu-id="9cf2a-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="9cf2a-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="9cf2a-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="9cf2a-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-115">Considerations</span></span>

  - <span data-ttu-id="9cf2a-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="9cf2a-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="9cf2a-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="9cf2a-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="9cf2a-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="9cf2a-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="9cf2a-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="9cf2a-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="9cf2a-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="9cf2a-124">Migration service availability</span></span>

  - <span data-ttu-id="9cf2a-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="9cf2a-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="9cf2a-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="9cf2a-127">Migration to Exchange Online</span></span>

<span data-ttu-id="9cf2a-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9cf2a-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="9cf2a-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-130">You create and schedule your migration events.</span></span> <span data-ttu-id="9cf2a-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9cf2a-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="9cf2a-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-133">Considerations</span></span>

  - <span data-ttu-id="9cf2a-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="9cf2a-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="9cf2a-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9cf2a-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="9cf2a-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="9cf2a-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9cf2a-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="9cf2a-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="9cf2a-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="9cf2a-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="9cf2a-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="9cf2a-143">Source environments</span></span>

<span data-ttu-id="9cf2a-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="9cf2a-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="9cf2a-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="9cf2a-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="9cf2a-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9cf2a-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9cf2a-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9cf2a-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="9cf2a-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9cf2a-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="9cf2a-154">
<strong>Примечание</strong>  Сведения о зависимостях для локального Exchange см. в статье  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Предварительные условия для гибридного развертывания</span></a>.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="9cf2a-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="9cf2a-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="9cf2a-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-156">Emails</span></span></li>
<li><span data-ttu-id="9cf2a-157">Правила для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="9cf2a-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="9cf2a-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-158">Delegates</span></span></li>
<li><span data-ttu-id="9cf2a-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="9cf2a-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9cf2a-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="9cf2a-160">Calendar</span></span> </li>
<li> <span data-ttu-id="9cf2a-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-161">Tasks</span></span> </li>
<li> <span data-ttu-id="9cf2a-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="9cf2a-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="9cf2a-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="9cf2a-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-164">Signatures</span></span> </li>
<li> <span data-ttu-id="9cf2a-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="9cf2a-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="9cf2a-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-167">Public folders</span></span> </li>
<li> <span data-ttu-id="9cf2a-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9cf2a-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="9cf2a-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="9cf2a-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9cf2a-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="9cf2a-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9cf2a-174"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="9cf2a-175">
<strong>Примечание:</strong> Ваша среда G Suite должна соответствовать предварительным условиям, описанные в разделе <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Выполнение переноса данных G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="9cf2a-176">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-177">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-177">Emails</span></span> </li>
<li> <span data-ttu-id="9cf2a-178">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="9cf2a-179">Календарь</span><span class="sxs-lookup"><span data-stu-id="9cf2a-179">Calendar</span></span> </li>
<li> <span data-ttu-id="9cf2a-180">Метки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-181">Правила</span><span class="sxs-lookup"><span data-stu-id="9cf2a-181">Rules</span></span> </li>
<li> <span data-ttu-id="9cf2a-182">Делегаты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-182">Delegates</span></span> </li>
<li> <span data-ttu-id="9cf2a-183">Подписи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-183">Signatures</span></span> </li>
<li> <span data-ttu-id="9cf2a-184">Задачи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-184">Tasks</span></span> </li>
<li> <span data-ttu-id="9cf2a-185">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="9cf2a-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9cf2a-186">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-187">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="9cf2a-188">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="9cf2a-189">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9cf2a-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="9cf2a-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="9cf2a-191">Группы Google</span><span class="sxs-lookup"><span data-stu-id="9cf2a-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="9cf2a-192">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="9cf2a-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="9cf2a-193">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="9cf2a-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="9cf2a-194">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="9cf2a-195">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="9cf2a-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="9cf2a-196">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9cf2a-197"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-198">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="9cf2a-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="9cf2a-199">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-200">Правила</span><span class="sxs-lookup"><span data-stu-id="9cf2a-200">Rules</span></span> </li>
<li> <span data-ttu-id="9cf2a-201">Делегаты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-201">Delegates</span></span> </li>
<li> <span data-ttu-id="9cf2a-202">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="9cf2a-203">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="9cf2a-203">External contacts</span></span> </li>
<li> <span data-ttu-id="9cf2a-204">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="9cf2a-205">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-206">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="9cf2a-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="9cf2a-207">Календарь</span><span class="sxs-lookup"><span data-stu-id="9cf2a-207">Calendar</span></span> </li>
<li> <span data-ttu-id="9cf2a-208">Подписи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-208">Signatures</span></span> </li>
<li> <span data-ttu-id="9cf2a-209">Задачи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-209">Tasks</span></span> </li>
<li> <span data-ttu-id="9cf2a-210">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="9cf2a-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="9cf2a-211">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="9cf2a-211">Archive data</span></span> </li>
<li> <span data-ttu-id="9cf2a-212">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="9cf2a-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="9cf2a-213">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="9cf2a-214">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="9cf2a-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9cf2a-215">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="9cf2a-215">FastTrack responsibilities</span></span>

<span data-ttu-id="9cf2a-216">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-217">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9cf2a-218">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="9cf2a-219">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9cf2a-220">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="9cf2a-220">Your responsibilities</span></span>

<span data-ttu-id="9cf2a-221">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-222">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9cf2a-223">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="9cf2a-224">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="9cf2a-225">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="9cf2a-226">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="9cf2a-227">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="9cf2a-228">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="9cf2a-229">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="9cf2a-230">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="9cf2a-231">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="9cf2a-232">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="9cf2a-233">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="9cf2a-234">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="9cf2a-235">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="9cf2a-236">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="9cf2a-237">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="9cf2a-238">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="9cf2a-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="9cf2a-239">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9cf2a-240">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9cf2a-241">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-241">You create and schedule your migration events.</span></span> <span data-ttu-id="9cf2a-242">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9cf2a-243">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="9cf2a-244">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-244">Considerations</span></span>

  - <span data-ttu-id="9cf2a-245">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="9cf2a-246">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="9cf2a-247">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="9cf2a-248">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="9cf2a-248">Source environment details</span></span>

<span data-ttu-id="9cf2a-249">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9cf2a-250">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9cf2a-251">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9cf2a-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9cf2a-253">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9cf2a-254">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9cf2a-255"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="9cf2a-256"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="9cf2a-257"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9cf2a-258"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9cf2a-259"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9cf2a-260">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-261">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-261">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-262">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-263">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="9cf2a-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9cf2a-264">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="9cf2a-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9cf2a-265">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-266">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-267">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-267">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-268">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-268">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-269">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-269">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-270">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="9cf2a-271">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9cf2a-272">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9cf2a-273">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9cf2a-274">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-275">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9cf2a-276">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-277">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="9cf2a-278">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="9cf2a-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9cf2a-279">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="9cf2a-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9cf2a-280">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9cf2a-281">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="9cf2a-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9cf2a-282">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9cf2a-283">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-284">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9cf2a-285">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9cf2a-286">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9cf2a-287"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-288">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-289">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="9cf2a-290">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-291">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-292">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-293">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-294">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-295">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-295">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-296">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-296">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-297">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-297">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-298">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-299">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9cf2a-300">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="9cf2a-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-301">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-302">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9cf2a-303">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-304">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-305">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="9cf2a-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-306">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-307">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-308">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-309">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-310">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-311">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="9cf2a-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9cf2a-312">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9cf2a-313">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9cf2a-314">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="9cf2a-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9cf2a-315">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-316">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-317">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9cf2a-318">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-319">Файлы, помеченные как ограниченные или недоступные для копирования</span><span class="sxs-lookup"><span data-stu-id="9cf2a-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="9cf2a-320">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9cf2a-321"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-322">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-323">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-323">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-324">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-325">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-326">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-327">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-328">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-329">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-329">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-330">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-330">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-331">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-331">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-332">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-333">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-334">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-335">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9cf2a-336">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-337">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-338">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-339">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-340">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-341">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-342">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-343">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-344">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9cf2a-345">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9cf2a-346">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-347">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-348">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9cf2a-349"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-350">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-351">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-351">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-352">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-353">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-354">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-355">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-356">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-357">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-357">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-358">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-358">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-359">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-359">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-360">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-361">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9cf2a-362">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-363">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-364">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9cf2a-365">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-366">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-367">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="9cf2a-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-368">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-369">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-370">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-371">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-372">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9cf2a-373">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9cf2a-374">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9cf2a-375">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9cf2a-376">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9cf2a-377">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-378">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="9cf2a-379">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9cf2a-380">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="9cf2a-380">FastTrack responsibilities</span></span>

<span data-ttu-id="9cf2a-381">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-382">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9cf2a-383">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="9cf2a-383">Your responsibilities</span></span>

<span data-ttu-id="9cf2a-384">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-385">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="9cf2a-386">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="9cf2a-387">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="9cf2a-388">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="9cf2a-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="9cf2a-389">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="9cf2a-390">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="9cf2a-391">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-391">You create and schedule your migration events.</span></span> <span data-ttu-id="9cf2a-392">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="9cf2a-393">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="9cf2a-394">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-394">Considerations</span></span>

  - <span data-ttu-id="9cf2a-395">На все миграции распространяются квоты OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="9cf2a-396">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="9cf2a-397">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="9cf2a-398">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="9cf2a-399">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="9cf2a-399">Source environment details</span></span>

<span data-ttu-id="9cf2a-400">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="9cf2a-401">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="9cf2a-402">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="9cf2a-403">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="9cf2a-404">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="9cf2a-405">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="9cf2a-406"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="9cf2a-407"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="9cf2a-408"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="9cf2a-409"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9cf2a-410"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="9cf2a-411">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-412">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-412">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-413">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-414">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="9cf2a-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9cf2a-415">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="9cf2a-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="9cf2a-416">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-417">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-418">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-418">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-419">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-419">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-420">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-420">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-421">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="9cf2a-422">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="9cf2a-423">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="9cf2a-424">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="9cf2a-425">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="9cf2a-426">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="9cf2a-427">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-428">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="9cf2a-429">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="9cf2a-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="9cf2a-430">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="9cf2a-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="9cf2a-431">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="9cf2a-432">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="9cf2a-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="9cf2a-433">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="9cf2a-434">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-435">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="9cf2a-436">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="9cf2a-437">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9cf2a-438"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-439">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-440">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="9cf2a-441">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-442">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-443">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-444">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-445">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-446">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-446">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-447">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-447">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-448">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-448">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-449">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-450">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="9cf2a-451">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="9cf2a-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-452">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-453">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="9cf2a-454">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-455">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-456">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="9cf2a-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-457">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-458">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-459">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-460">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-461">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-462">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="9cf2a-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="9cf2a-463">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="9cf2a-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="9cf2a-464">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="9cf2a-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="9cf2a-465">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="9cf2a-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="9cf2a-466">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-467">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-468">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="9cf2a-469">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-470">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9cf2a-471"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-472">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-473">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-473">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-474">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-475">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-476">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-477">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-478">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-479">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-479">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-480">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-480">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-481">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-481">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-482">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-483">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-484">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-485">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9cf2a-486">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-487">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-488">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-489">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-490">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-491">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-492">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-493">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="9cf2a-494">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="9cf2a-495">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="9cf2a-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="9cf2a-496">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-497">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-498">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9cf2a-499"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="9cf2a-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="9cf2a-500">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="9cf2a-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-501">Документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-501">Documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-502">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="9cf2a-503">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-504">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-505">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="9cf2a-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="9cf2a-506">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="9cf2a-507">Дата создания</span><span class="sxs-lookup"><span data-stu-id="9cf2a-507">Created date</span></span> </li>
<li> <span data-ttu-id="9cf2a-508">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-508">Modified date</span></span> </li>
<li> <span data-ttu-id="9cf2a-509">Автор</span><span class="sxs-lookup"><span data-stu-id="9cf2a-509">Created by</span></span> </li>
<li> <span data-ttu-id="9cf2a-510">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="9cf2a-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="9cf2a-511">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="9cf2a-512">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="9cf2a-513">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="9cf2a-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="9cf2a-514">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="9cf2a-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="9cf2a-515">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="9cf2a-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-516">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="9cf2a-517">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="9cf2a-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="9cf2a-518">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="9cf2a-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="9cf2a-519">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="9cf2a-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="9cf2a-520">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="9cf2a-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="9cf2a-521">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="9cf2a-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="9cf2a-522">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="9cf2a-523">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="9cf2a-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="9cf2a-524">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="9cf2a-525">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="9cf2a-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="9cf2a-526">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="9cf2a-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="9cf2a-527">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="9cf2a-528">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="9cf2a-529">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="9cf2a-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="9cf2a-530">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="9cf2a-530">FastTrack responsibilities</span></span>

<span data-ttu-id="9cf2a-531">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-532">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="9cf2a-533">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="9cf2a-533">Your responsibilities</span></span>

<span data-ttu-id="9cf2a-534">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="9cf2a-535">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="9cf2a-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="9cf2a-536">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="9cf2a-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="9cf2a-537">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="9cf2a-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
