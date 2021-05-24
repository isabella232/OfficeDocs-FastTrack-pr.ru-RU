---
title: Перенос данных
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: 437da2c12375bfc2d9614c452b0685f18ad3d188
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592430"
---
# <a name="data-migration"></a><span data-ttu-id="3ccb4-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="3ccb4-104">Data Migration</span></span>

<span data-ttu-id="3ccb4-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="3ccb4-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="3ccb4-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="3ccb4-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="3ccb4-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="3ccb4-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="3ccb4-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-111">You create and schedule your migration events.</span></span> <span data-ttu-id="3ccb4-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="3ccb4-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="3ccb4-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="3ccb4-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-115">Considerations</span></span>

  - <span data-ttu-id="3ccb4-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="3ccb4-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="3ccb4-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="3ccb4-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="3ccb4-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="3ccb4-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="3ccb4-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="3ccb4-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="3ccb4-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="3ccb4-124">Migration service availability</span></span>

  - <span data-ttu-id="3ccb4-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="3ccb4-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="3ccb4-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="3ccb4-127">Migration to Exchange Online</span></span>

<span data-ttu-id="3ccb4-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3ccb4-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="3ccb4-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-130">You create and schedule your migration events.</span></span> <span data-ttu-id="3ccb4-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3ccb4-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3ccb4-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-133">Considerations</span></span>

  - <span data-ttu-id="3ccb4-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="3ccb4-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="3ccb4-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3ccb4-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="3ccb4-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="3ccb4-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3ccb4-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="3ccb4-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="3ccb4-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="3ccb4-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="3ccb4-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="3ccb4-143">Source environments</span></span>

<span data-ttu-id="3ccb4-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="3ccb4-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="3ccb4-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="3ccb4-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="3ccb4-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3ccb4-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3ccb4-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3ccb4-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="3ccb4-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3ccb4-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="3ccb4-154">
<strong>Примечание:</strong> Для локального Exchange зависимостей см. предварительные условия <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">гибридного развертывания.</span></a></span><span class="sxs-lookup"><span data-stu-id="3ccb4-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="3ccb4-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="3ccb4-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="3ccb4-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-156">Emails</span></span></li>
<li><span data-ttu-id="3ccb4-157">Правила почтового ящика на стороне сервера</span><span class="sxs-lookup"><span data-stu-id="3ccb4-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="3ccb4-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-158">Delegates</span></span></li>
<li><span data-ttu-id="3ccb4-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="3ccb4-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3ccb4-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="3ccb4-160">Calendar</span></span> </li>
<li> <span data-ttu-id="3ccb4-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-161">Tasks</span></span> </li>
<li> <span data-ttu-id="3ccb4-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="3ccb4-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="3ccb4-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="3ccb4-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-164">Signatures</span></span> </li>
<li> <span data-ttu-id="3ccb4-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="3ccb4-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="3ccb4-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-167">Public folders</span></span> </li>
<li> <span data-ttu-id="3ccb4-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3ccb4-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="3ccb4-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="3ccb4-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3ccb4-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="3ccb4-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3ccb4-174">Правила клиентского почтового ящика</span><span class="sxs-lookup"><span data-stu-id="3ccb4-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-175"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="3ccb4-176">
<strong>Примечание:</strong> Среда G Suite должна соответствовать требованиям, описанным в миграции [G Suite.](/Exchange/mailbox-migration/perform-g-suite-migration)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in [Perform a G Suite migration](/Exchange/mailbox-migration/perform-g-suite-migration).</span></span></td>
<td><span data-ttu-id="3ccb4-177">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-178">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-178">Emails</span></span> </li>
<li> <span data-ttu-id="3ccb4-179">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="3ccb4-180">Календарь</span><span class="sxs-lookup"><span data-stu-id="3ccb4-180">Calendar</span></span> </li>
<li> <span data-ttu-id="3ccb4-181">Метки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-182">Правила</span><span class="sxs-lookup"><span data-stu-id="3ccb4-182">Rules</span></span> </li>
<li> <span data-ttu-id="3ccb4-183">Делегаты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-183">Delegates</span></span> </li>
<li> <span data-ttu-id="3ccb4-184">Подписи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-184">Signatures</span></span> </li>
<li> <span data-ttu-id="3ccb4-185">Задачи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-185">Tasks</span></span> </li>
<li> <span data-ttu-id="3ccb4-186">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="3ccb4-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3ccb4-187">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-188">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="3ccb4-189">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="3ccb4-190">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3ccb4-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-192">Группы Google</span><span class="sxs-lookup"><span data-stu-id="3ccb4-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="3ccb4-193">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="3ccb4-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="3ccb4-194">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="3ccb4-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="3ccb4-195">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="3ccb4-196">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="3ccb4-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="3ccb4-197">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3ccb4-198"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-199">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="3ccb4-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="3ccb4-200">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-201">Правила</span><span class="sxs-lookup"><span data-stu-id="3ccb4-201">Rules</span></span> </li>
<li> <span data-ttu-id="3ccb4-202">Делегаты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-202">Delegates</span></span> </li>
<li> <span data-ttu-id="3ccb4-203">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="3ccb4-204">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="3ccb4-204">External contacts</span></span> </li>
<li> <span data-ttu-id="3ccb4-205">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="3ccb4-206">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-207">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="3ccb4-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="3ccb4-208">Календарь</span><span class="sxs-lookup"><span data-stu-id="3ccb4-208">Calendar</span></span> </li>
<li> <span data-ttu-id="3ccb4-209">Подписи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-209">Signatures</span></span> </li>
<li> <span data-ttu-id="3ccb4-210">Задачи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-210">Tasks</span></span> </li>
<li> <span data-ttu-id="3ccb4-211">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="3ccb4-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="3ccb4-212">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-212">Archive data</span></span> </li>
<li> <span data-ttu-id="3ccb4-213">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="3ccb4-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="3ccb4-214">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="3ccb4-215">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="3ccb4-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="3ccb4-216">Обязанности FastTrack для Exchange Online миграций</span><span class="sxs-lookup"><span data-stu-id="3ccb4-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="3ccb4-217">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-218">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3ccb4-219">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="3ccb4-220">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="3ccb4-221">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="3ccb4-221">Your responsibilities</span></span>

<span data-ttu-id="3ccb4-222">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-223">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3ccb4-224">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="3ccb4-225">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="3ccb4-226">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="3ccb4-227">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="3ccb4-228">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="3ccb4-229">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="3ccb4-230">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="3ccb4-231">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="3ccb4-232">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="3ccb4-233">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="3ccb4-234">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="3ccb4-235">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="3ccb4-236">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="3ccb4-237">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="3ccb4-238">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="3ccb4-239">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3ccb4-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="3ccb4-240">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3ccb4-241">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3ccb4-242">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-242">You create and schedule your migration events.</span></span> <span data-ttu-id="3ccb4-243">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3ccb4-244">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="3ccb4-245">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-245">Considerations</span></span>

 - <span data-ttu-id="3ccb4-246">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3ccb4-247">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="3ccb4-248">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="3ccb4-249">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="3ccb4-249">Source environment details</span></span>

<span data-ttu-id="3ccb4-250">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3ccb4-251">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3ccb4-252">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3ccb4-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3ccb4-254">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3ccb4-255">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="3ccb4-256"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="3ccb4-257"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="3ccb4-258"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-259"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3ccb4-260"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3ccb4-261">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-262">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-262">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-263">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-264">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-265">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-266">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-267">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-268">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-268">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-269">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-269">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-270">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-270">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-271">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="3ccb4-272">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3ccb4-273">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3ccb4-274">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3ccb4-275">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-276">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-277">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-278">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-279">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="3ccb4-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3ccb4-280">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="3ccb4-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3ccb4-281">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3ccb4-282">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="3ccb4-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3ccb4-283">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3ccb4-284">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-285">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3ccb4-286">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3ccb4-287">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-288"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-289">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-290">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="3ccb4-291">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-292">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-293">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-294">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-295">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-296">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-296">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-297">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-297">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-298">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-298">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-299">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-300">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3ccb4-301">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-302">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-303">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3ccb4-304">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-305">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-306">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-307">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-308">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-309">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-310">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-311">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-312">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="3ccb4-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3ccb4-313">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3ccb4-314">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3ccb4-315">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3ccb4-316">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-317">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-318">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3ccb4-319">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-320">Файлы, помеченные как ограниченные или не копируемые</span><span class="sxs-lookup"><span data-stu-id="3ccb4-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="3ccb4-321">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3ccb4-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-323">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-324">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-324">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-325">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-326">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-327">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-328">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-329">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-330">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-330">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-331">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-331">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-332">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-332">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-333">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-334">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3ccb4-335">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-336">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-337">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-338">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-339">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-340">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-341">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-342">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-343">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-344">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-345">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-346">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3ccb4-347">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3ccb4-348">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-349">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-350">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-351"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-352">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-353">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-353">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-354">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-355">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-356">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-357">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-358">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-359">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-359">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-360">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-360">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-361">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-361">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-362">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-363">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3ccb4-364">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-365">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-366">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-367">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-368">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-369">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-370">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-371">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-372">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-373">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-374">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3ccb4-375">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3ccb4-376">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3ccb4-377">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3ccb4-378">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3ccb4-379">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-380">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="3ccb4-381">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="3ccb4-382">Обязанности FastTrack для SharePoint миграций в Интернете</span><span class="sxs-lookup"><span data-stu-id="3ccb4-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="3ccb4-383">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-384">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="3ccb4-385">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="3ccb4-385">Your responsibilities</span></span>

<span data-ttu-id="3ccb4-386">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-387">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="3ccb4-388">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="3ccb4-389">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="3ccb4-390">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="3ccb4-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="3ccb4-391">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3ccb4-392">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3ccb4-393">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-393">You create and schedule your migration events.</span></span> <span data-ttu-id="3ccb4-394">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3ccb4-395">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="3ccb4-396">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-396">Considerations</span></span>

  - <span data-ttu-id="3ccb4-397">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3ccb4-398">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="3ccb4-399">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="3ccb4-400">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="3ccb4-401">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="3ccb4-401">Source environment details</span></span>

<span data-ttu-id="3ccb4-402">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="3ccb4-403">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="3ccb4-404">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="3ccb4-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="3ccb4-406">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="3ccb4-407">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3ccb4-408"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-409"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-410"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-411"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3ccb4-412"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3ccb4-413">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-414">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-414">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-415">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-416">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-417">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-418">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-419">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-420">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-420">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-421">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-421">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-422">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-422">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-423">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3ccb4-424">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3ccb4-425">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3ccb4-426">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3ccb4-427">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3ccb4-428">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-429">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-430">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-431">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="3ccb4-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3ccb4-432">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="3ccb4-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3ccb4-433">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3ccb4-434">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="3ccb4-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3ccb4-435">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3ccb4-436">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-437">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3ccb4-438">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3ccb4-439">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-440"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-441">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-442">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3ccb4-443">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-444">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-445">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-446">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-447">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-448">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-448">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-449">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-449">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-450">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-450">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-451">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-452">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3ccb4-453">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-454">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-455">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3ccb4-456">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-457">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-458">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-459">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-460">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-461">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-462">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-463">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-464">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="3ccb4-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3ccb4-465">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3ccb4-466">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3ccb4-467">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3ccb4-468">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-469">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-470">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3ccb4-471">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-472">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3ccb4-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-474">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-475">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-475">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-476">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-477">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-478">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-479">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-480">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-481">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-481">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-482">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-482">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-483">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-483">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-484">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-485">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-486">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-487">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-488">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-489">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-490">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-491">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-492">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-493">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-494">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-495">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-496">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3ccb4-497">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3ccb4-498">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-499">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-500">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-501"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-502">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-503">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-503">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-504">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-505">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-506">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-507">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-508">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-509">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-509">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-510">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-510">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-511">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-511">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-512">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-513">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3ccb4-514">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-515">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-516">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-517">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-518">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-519">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-520">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-521">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-522">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-523">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-524">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3ccb4-525">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3ccb4-526">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3ccb4-527">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3ccb4-528">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3ccb4-529">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-530">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-531">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="3ccb4-532">Обязанности FastTrack для OneDrive для бизнеса миграций</span><span class="sxs-lookup"><span data-stu-id="3ccb4-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="3ccb4-533">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-534">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="3ccb4-535">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="3ccb4-535">Your responsibilities</span></span>

<span data-ttu-id="3ccb4-536">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-537">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="3ccb4-538">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="3ccb4-539">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="3ccb4-540">Миграция в Microsoft Teams и Microsoft 365 группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="3ccb4-541">Если вы решите использовать FastTrack для переноса файлов в группы Microsoft Teams Microsoft 365, мы предоставляем рекомендации по миграции и миграции данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="3ccb4-542">Мы предоставляем рекомендации по планированию миграции, настройке исходных сред и групп Teams и Microsoft 365 и использования наших служб миграции данных для переноса файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="3ccb4-543">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-543">You create and schedule your migration events.</span></span> <span data-ttu-id="3ccb4-544">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="3ccb4-545">По завершению событий миграции можно ожидать перенос файлов из надлежащим образом запланированных и подходящих источников исходных сред в Teams и Microsoft 365 Groups.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="3ccb4-546">Teams каналов и Microsoft 365 группы должны быть предварительно заранее перенаправлены данные в эти типы назначения.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="3ccb4-547">Teams и Microsoft 365 группы влияют на ваши разрешения в расположении назначения файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="3ccb4-548">Teams и Microsoft 365 группы построены для того, чтобы разрешить совместную работу.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="3ccb4-549">Группа Teams или Microsoft 365 определяет, кто имеет доступ к этим файлам при миграции в эти пункты назначения.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="3ccb4-550">FastTrack не добавляет конечных пользователей или групп в Teams или Microsoft 365 групп во время миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="3ccb4-551">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-551">Considerations</span></span>

- <span data-ttu-id="3ccb4-552">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="3ccb4-553">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="3ccb4-554">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="3ccb4-555">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="3ccb4-555">Source environment details</span></span>

<span data-ttu-id="3ccb4-556">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="3ccb4-557">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="3ccb4-558">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="3ccb4-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="3ccb4-560">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="3ccb4-561">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="3ccb4-562"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-563"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-564"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="3ccb4-565"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="3ccb4-566"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="3ccb4-567">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-568">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-568">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-569">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-570">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-571">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-572">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-573">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-574">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-574">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-575">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-575">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-576">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-576">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-577">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="3ccb4-578">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="3ccb4-579">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="3ccb4-580">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="3ccb4-581">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="3ccb4-582">Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3ccb4-583">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3ccb4-584">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-585">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-586">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-587">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="3ccb4-588">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="3ccb4-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="3ccb4-589">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="3ccb4-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="3ccb4-590">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="3ccb4-591">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="3ccb4-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="3ccb4-592">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="3ccb4-593">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-594">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="3ccb4-595">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="3ccb4-596">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-597"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-598">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-599">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="3ccb4-600">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-601">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-602">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-603">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-604">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-605">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-605">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-606">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-606">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-607">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-607">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-608">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-609">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="3ccb4-610">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="3ccb4-611">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3ccb4-612">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3ccb4-613">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="3ccb4-614">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-615">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="3ccb4-616">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-617">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-618">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-619">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-620">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-621">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-622">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-623">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-624">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="3ccb4-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="3ccb4-625">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="3ccb4-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="3ccb4-626">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="3ccb4-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="3ccb4-627">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="3ccb4-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="3ccb4-628">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-629">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-630">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="3ccb4-631">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-632">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="3ccb4-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-634">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-635">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-635">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-636">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-637">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-638">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-639">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-640">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-641">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-641">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-642">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-642">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-643">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-643">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-644">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-645">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="3ccb4-646">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="3ccb4-647">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3ccb4-648">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3ccb4-649">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="3ccb4-650">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-651">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-652">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-653">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-654">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-655">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-656">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-657">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-658">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-659">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="3ccb4-660">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="3ccb4-661">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="3ccb4-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="3ccb4-662">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-663">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-664">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="3ccb4-665"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="3ccb4-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="3ccb4-666">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="3ccb4-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="3ccb4-667">Документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-667">Documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-668">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="3ccb4-669">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-670">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="3ccb4-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="3ccb4-671">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="3ccb4-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="3ccb4-672">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="3ccb4-673">Дата создания</span><span class="sxs-lookup"><span data-stu-id="3ccb4-673">Created date</span></span> </li>
<li> <span data-ttu-id="3ccb4-674">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-674">Modified date</span></span> </li>
<li> <span data-ttu-id="3ccb4-675">Автор</span><span class="sxs-lookup"><span data-stu-id="3ccb4-675">Created by</span></span> </li>
<li> <span data-ttu-id="3ccb4-676">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="3ccb4-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="3ccb4-677">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="3ccb4-678">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="3ccb4-679">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="3ccb4-680">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="3ccb4-681">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="3ccb4-682">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="3ccb4-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="3ccb4-683">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="3ccb4-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="3ccb4-684">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="3ccb4-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-685">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="3ccb4-686">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="3ccb4-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="3ccb4-687">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="3ccb4-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="3ccb4-688">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="3ccb4-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="3ccb4-689">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="3ccb4-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="3ccb4-690">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="3ccb4-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="3ccb4-691">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="3ccb4-692">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="3ccb4-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="3ccb4-693">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="3ccb4-694">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="3ccb4-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="3ccb4-695">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="3ccb4-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="3ccb4-696">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="3ccb4-697">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="3ccb4-698">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="3ccb4-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="3ccb4-699">Обязанности FastTrack для миграций Microsoft Teams и Microsoft 365 групп</span><span class="sxs-lookup"><span data-stu-id="3ccb4-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="3ccb4-700">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-701">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="3ccb4-702">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="3ccb4-702">Your responsibilities</span></span> 

<span data-ttu-id="3ccb4-703">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="3ccb4-704">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="3ccb4-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="3ccb4-705">Вы также выполняете следующие действия, определенные миграциям Microsoft Teams и Microsoft 365 групп:</span><span class="sxs-lookup"><span data-stu-id="3ccb4-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="3ccb4-706">Подготовка всех Microsoft Teams каналов и Microsoft 365 групп в качестве целевых для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="3ccb4-707">FastTrack не заранее Microsoft Teams каналов или Microsoft 365 групп.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="3ccb4-708">FastTrack не добавляет конечных пользователей или групп в Microsoft Teams или Microsoft 365 группы.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="3ccb4-709">Перед переносом данных в эти пункты необходимо добавить конечных пользователей или группы во все Microsoft Teams и группы Microsoft 365, чтобы эти конечные пользователи могли получать доступ к этим недавно перенесенным документам.</span><span class="sxs-lookup"><span data-stu-id="3ccb4-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>