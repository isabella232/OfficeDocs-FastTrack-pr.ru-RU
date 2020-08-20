---
title: Перенос данных
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817716"
---
# <a name="data-migration"></a><span data-ttu-id="8625e-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="8625e-104">Data Migration</span></span>

<span data-ttu-id="8625e-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="8625e-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8625e-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="8625e-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8625e-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="8625e-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8625e-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8625e-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8625e-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8625e-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8625e-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="8625e-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8625e-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8625e-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="8625e-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8625e-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="8625e-115">Considerations</span></span>

  - <span data-ttu-id="8625e-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="8625e-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8625e-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8625e-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="8625e-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8625e-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="8625e-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8625e-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="8625e-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8625e-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="8625e-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8625e-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8625e-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8625e-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="8625e-124">Migration service availability</span></span>

  - <span data-ttu-id="8625e-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="8625e-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8625e-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="8625e-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8625e-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="8625e-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8625e-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8625e-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="8625e-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8625e-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8625e-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="8625e-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8625e-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8625e-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8625e-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="8625e-133">Considerations</span></span>

  - <span data-ttu-id="8625e-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="8625e-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8625e-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="8625e-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8625e-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8625e-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="8625e-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8625e-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="8625e-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8625e-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="8625e-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8625e-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="8625e-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8625e-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="8625e-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8625e-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="8625e-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8625e-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="8625e-143">Source environments</span></span>

<span data-ttu-id="8625e-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="8625e-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8625e-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="8625e-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8625e-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="8625e-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8625e-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="8625e-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8625e-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="8625e-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8625e-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8625e-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8625e-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8625e-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8625e-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8625e-154">
<strong>Примечание</strong>  Сведения о зависимостях для локального Exchange см. в статье  <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Предварительные условия для гибридного развертывания</span></a>.</span><span class="sxs-lookup"><span data-stu-id="8625e-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8625e-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="8625e-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8625e-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="8625e-156">Emails</span></span></li>
<li><span data-ttu-id="8625e-157">Правила для почтового ящика</span><span class="sxs-lookup"><span data-stu-id="8625e-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="8625e-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="8625e-158">Delegates</span></span></li>
<li><span data-ttu-id="8625e-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="8625e-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8625e-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="8625e-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8625e-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="8625e-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8625e-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="8625e-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8625e-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="8625e-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8625e-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="8625e-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8625e-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8625e-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="8625e-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="8625e-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8625e-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="8625e-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8625e-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="8625e-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8625e-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8625e-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="8625e-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8625e-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="8625e-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8625e-174"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8625e-175">
<strong>Примечание:</strong> Ваша среда G Suite должна соответствовать предварительным условиям, описанные в разделе <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Выполнение переноса данных G Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="8625e-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8625e-176">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-177">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="8625e-177">Emails</span></span> </li>
<li> <span data-ttu-id="8625e-178">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="8625e-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8625e-179">Календарь</span><span class="sxs-lookup"><span data-stu-id="8625e-179">Calendar</span></span> </li>
<li> <span data-ttu-id="8625e-180">Метки</span><span class="sxs-lookup"><span data-stu-id="8625e-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-181">Правила</span><span class="sxs-lookup"><span data-stu-id="8625e-181">Rules</span></span> </li>
<li> <span data-ttu-id="8625e-182">Делегаты</span><span class="sxs-lookup"><span data-stu-id="8625e-182">Delegates</span></span> </li>
<li> <span data-ttu-id="8625e-183">Подписи</span><span class="sxs-lookup"><span data-stu-id="8625e-183">Signatures</span></span> </li>
<li> <span data-ttu-id="8625e-184">Задачи</span><span class="sxs-lookup"><span data-stu-id="8625e-184">Tasks</span></span> </li>
<li> <span data-ttu-id="8625e-185">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="8625e-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8625e-186">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-187">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="8625e-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8625e-188">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="8625e-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8625e-189">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="8625e-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8625e-190">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="8625e-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8625e-191">Группы Google</span><span class="sxs-lookup"><span data-stu-id="8625e-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="8625e-192">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="8625e-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8625e-193">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="8625e-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8625e-194">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="8625e-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8625e-195">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="8625e-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8625e-196">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="8625e-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8625e-197"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8625e-198">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="8625e-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8625e-199">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="8625e-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8625e-200">Правила</span><span class="sxs-lookup"><span data-stu-id="8625e-200">Rules</span></span> </li>
<li> <span data-ttu-id="8625e-201">Делегаты</span><span class="sxs-lookup"><span data-stu-id="8625e-201">Delegates</span></span> </li>
<li> <span data-ttu-id="8625e-202">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="8625e-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8625e-203">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="8625e-203">External contacts</span></span> </li>
<li> <span data-ttu-id="8625e-204">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="8625e-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8625e-205">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-206">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="8625e-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8625e-207">Календарь</span><span class="sxs-lookup"><span data-stu-id="8625e-207">Calendar</span></span> </li>
<li> <span data-ttu-id="8625e-208">Подписи</span><span class="sxs-lookup"><span data-stu-id="8625e-208">Signatures</span></span> </li>
<li> <span data-ttu-id="8625e-209">Задачи</span><span class="sxs-lookup"><span data-stu-id="8625e-209">Tasks</span></span> </li>
<li> <span data-ttu-id="8625e-210">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="8625e-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8625e-211">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="8625e-211">Archive data</span></span> </li>
<li> <span data-ttu-id="8625e-212">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="8625e-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8625e-213">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="8625e-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8625e-214">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="8625e-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8625e-215">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="8625e-215">FastTrack responsibilities</span></span>

<span data-ttu-id="8625e-216">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-217">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8625e-218">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="8625e-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8625e-219">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="8625e-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8625e-220">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="8625e-220">Your responsibilities</span></span>

<span data-ttu-id="8625e-221">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-222">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8625e-223">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="8625e-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8625e-224">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="8625e-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8625e-225">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="8625e-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8625e-226">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8625e-227">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="8625e-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8625e-228">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="8625e-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8625e-229">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="8625e-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8625e-230">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="8625e-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8625e-231">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="8625e-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8625e-232">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="8625e-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8625e-233">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="8625e-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8625e-234">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="8625e-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8625e-235">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="8625e-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="8625e-236">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="8625e-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8625e-237">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="8625e-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8625e-238">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="8625e-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="8625e-239">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8625e-240">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="8625e-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8625e-241">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-241">You create and schedule your migration events.</span></span> <span data-ttu-id="8625e-242">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="8625e-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8625e-243">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8625e-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8625e-244">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="8625e-244">Considerations</span></span>

  - <span data-ttu-id="8625e-245">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="8625e-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8625e-246">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="8625e-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8625e-247">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="8625e-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8625e-248">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="8625e-248">Source environment details</span></span>

<span data-ttu-id="8625e-249">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="8625e-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8625e-250">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="8625e-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8625e-251">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="8625e-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8625e-252">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="8625e-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8625e-253">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="8625e-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8625e-254">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="8625e-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8625e-255"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8625e-256"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8625e-257"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8625e-258"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8625e-259"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8625e-260">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-261">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-261">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-262">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-263">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="8625e-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8625e-264">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="8625e-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8625e-265">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-266">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-267">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-267">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-268">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-268">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-269">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-269">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-270">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8625e-271">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="8625e-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8625e-272">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="8625e-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8625e-273">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="8625e-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8625e-274">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="8625e-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-275">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="8625e-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8625e-276">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-277">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="8625e-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="8625e-278">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="8625e-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8625e-279">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="8625e-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8625e-280">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="8625e-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8625e-281">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="8625e-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8625e-282">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="8625e-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8625e-283">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-284">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="8625e-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8625e-285">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="8625e-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8625e-286">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8625e-287"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8625e-288">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-289">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="8625e-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8625e-290">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-291">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-292">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-293">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-294">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-295">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-295">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-296">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-296">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-297">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-297">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-298">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-299">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="8625e-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8625e-300">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="8625e-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-301">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-302">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="8625e-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8625e-303">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-304">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-305">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="8625e-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-306">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-307">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-308">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-309">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-310">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-311">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="8625e-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8625e-312">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="8625e-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8625e-313">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="8625e-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8625e-314">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="8625e-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8625e-315">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-316">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-317">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="8625e-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8625e-318">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-319">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8625e-320"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8625e-321">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-322">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-322">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-323">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-324">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-325">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-326">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-327">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-328">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-328">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-329">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-329">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-330">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-330">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-331">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-332">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="8625e-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-333">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-334">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8625e-335">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-336">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-337">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="8625e-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-338">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-339">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-340">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-341">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-342">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-343">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="8625e-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8625e-344">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="8625e-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8625e-345">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-346">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-347">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8625e-348"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8625e-349">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-350">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-350">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-351">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-352">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-353">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-354">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-355">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-356">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-356">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-357">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-357">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-358">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-358">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-359">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-360">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="8625e-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8625e-361">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-362">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-363">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8625e-364">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-365">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-366">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="8625e-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-367">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-368">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-369">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-370">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-371">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8625e-372">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8625e-373">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8625e-374">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="8625e-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8625e-375">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8625e-376">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-377">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="8625e-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8625e-378">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8625e-379">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="8625e-379">FastTrack responsibilities</span></span>

<span data-ttu-id="8625e-380">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-381">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="8625e-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8625e-382">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="8625e-382">Your responsibilities</span></span>

<span data-ttu-id="8625e-383">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-384">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="8625e-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8625e-385">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="8625e-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8625e-386">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8625e-387">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="8625e-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8625e-388">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8625e-389">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="8625e-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8625e-390">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="8625e-390">You create and schedule your migration events.</span></span> <span data-ttu-id="8625e-391">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="8625e-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8625e-392">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="8625e-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8625e-393">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="8625e-393">Considerations</span></span>

  - <span data-ttu-id="8625e-394">На все миграции распространяются квоты OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="8625e-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="8625e-395">Дополнительные сведения см. в разделе [<span class="underline">Программные ограничения и пороговые значения SharePoint Online и OneDrive для бизнеса</span>](https://go.microsoft.com/fwlink/?LinkId=698855).</span><span class="sxs-lookup"><span data-stu-id="8625e-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8625e-396">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="8625e-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8625e-397">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="8625e-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8625e-398">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="8625e-398">Source environment details</span></span>

<span data-ttu-id="8625e-399">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="8625e-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8625e-400">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="8625e-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8625e-401">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="8625e-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8625e-402">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="8625e-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8625e-403">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="8625e-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8625e-404">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="8625e-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8625e-405"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8625e-406"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8625e-407"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8625e-408"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8625e-409"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8625e-410">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-411">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-411">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-412">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-413">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="8625e-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8625e-414">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="8625e-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8625e-415">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-416">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-417">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-417">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-418">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-418">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-419">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-419">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-420">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8625e-421">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="8625e-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8625e-422">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="8625e-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8625e-423">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="8625e-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8625e-424">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="8625e-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8625e-425">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="8625e-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8625e-426">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-427">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="8625e-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="8625e-428">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="8625e-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8625e-429">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="8625e-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8625e-430">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="8625e-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8625e-431">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="8625e-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8625e-432">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="8625e-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8625e-433">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-434">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="8625e-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8625e-435">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="8625e-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8625e-436">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8625e-437"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8625e-438">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-439">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="8625e-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8625e-440">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-441">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-442">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-443">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-444">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-445">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-445">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-446">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-446">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-447">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-447">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-448">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-449">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="8625e-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8625e-450">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="8625e-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-451">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-452">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="8625e-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8625e-453">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-454">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-455">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="8625e-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-456">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-457">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-458">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-459">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-460">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-461">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="8625e-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8625e-462">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="8625e-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8625e-463">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="8625e-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8625e-464">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="8625e-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8625e-465">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-466">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-467">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="8625e-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8625e-468">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-469">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8625e-470"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8625e-471">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-472">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-472">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-473">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-474">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-475">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-476">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-477">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-478">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-478">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-479">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-479">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-480">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-480">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-481">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-482">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="8625e-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-483">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-484">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8625e-485">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-486">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-487">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="8625e-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-488">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-489">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-490">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-491">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-492">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8625e-493">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="8625e-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8625e-494">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="8625e-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8625e-495">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-496">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-497">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8625e-498"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="8625e-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8625e-499">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="8625e-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8625e-500">Документы</span><span class="sxs-lookup"><span data-stu-id="8625e-500">Documents</span></span> </li>
<li> <span data-ttu-id="8625e-501">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8625e-502">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-503">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8625e-504">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="8625e-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8625e-505">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8625e-506">Дата создания</span><span class="sxs-lookup"><span data-stu-id="8625e-506">Created date</span></span> </li>
<li> <span data-ttu-id="8625e-507">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-507">Modified date</span></span> </li>
<li> <span data-ttu-id="8625e-508">Автор</span><span class="sxs-lookup"><span data-stu-id="8625e-508">Created by</span></span> </li>
<li> <span data-ttu-id="8625e-509">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="8625e-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8625e-510">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="8625e-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8625e-511">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8625e-512">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="8625e-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8625e-513">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="8625e-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8625e-514">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="8625e-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-515">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="8625e-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8625e-516">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="8625e-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8625e-517">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="8625e-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8625e-518">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="8625e-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8625e-519">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="8625e-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="8625e-520">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="8625e-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8625e-521">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8625e-522">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="8625e-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8625e-523">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8625e-524">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="8625e-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8625e-525">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="8625e-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8625e-526">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="8625e-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8625e-527">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="8625e-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8625e-528">Файлы или папки, для которых превышены текущие  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">Ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="8625e-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8625e-529">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="8625e-529">FastTrack responsibilities</span></span>

<span data-ttu-id="8625e-530">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-531">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8625e-532">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="8625e-532">Your responsibilities</span></span>

<span data-ttu-id="8625e-533">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8625e-534">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="8625e-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8625e-535">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="8625e-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8625e-536">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="8625e-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
