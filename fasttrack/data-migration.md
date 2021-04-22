---
title: Перенос данных
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса). Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас.
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927001"
---
# <a name="data-migration"></a><span data-ttu-id="f3dfe-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="f3dfe-104">Data Migration</span></span>

<span data-ttu-id="f3dfe-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="f3dfe-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="f3dfe-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="f3dfe-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="f3dfe-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="f3dfe-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="f3dfe-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-111">You create and schedule your migration events.</span></span> <span data-ttu-id="f3dfe-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="f3dfe-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="f3dfe-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="f3dfe-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-115">Considerations</span></span>

  - <span data-ttu-id="f3dfe-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="f3dfe-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="f3dfe-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="f3dfe-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="f3dfe-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="f3dfe-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="f3dfe-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="f3dfe-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="f3dfe-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="f3dfe-124">Migration service availability</span></span>

  - <span data-ttu-id="f3dfe-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="f3dfe-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="f3dfe-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="f3dfe-127">Migration to Exchange Online</span></span>

<span data-ttu-id="f3dfe-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3dfe-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="f3dfe-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-130">You create and schedule your migration events.</span></span> <span data-ttu-id="f3dfe-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3dfe-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="f3dfe-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-133">Considerations</span></span>

  - <span data-ttu-id="f3dfe-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="f3dfe-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="f3dfe-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f3dfe-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="f3dfe-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="f3dfe-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f3dfe-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="f3dfe-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="f3dfe-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="f3dfe-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="f3dfe-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="f3dfe-143">Source environments</span></span>

<span data-ttu-id="f3dfe-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="f3dfe-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="f3dfe-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="f3dfe-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="f3dfe-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f3dfe-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f3dfe-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f3dfe-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="f3dfe-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3dfe-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="f3dfe-154">
<strong>Примечание:</strong> Для зависимостей Exchange на локальной основе см. <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">предварительные условия гибридного развертывания.</span></a></span><span class="sxs-lookup"><span data-stu-id="f3dfe-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="f3dfe-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="f3dfe-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="f3dfe-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-156">Emails</span></span></li>
<li><span data-ttu-id="f3dfe-157">Правила почтового ящика на стороне сервера</span><span class="sxs-lookup"><span data-stu-id="f3dfe-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="f3dfe-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-158">Delegates</span></span></li>
<li><span data-ttu-id="f3dfe-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="f3dfe-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f3dfe-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="f3dfe-160">Calendar</span></span> </li>
<li> <span data-ttu-id="f3dfe-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-161">Tasks</span></span> </li>
<li> <span data-ttu-id="f3dfe-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="f3dfe-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="f3dfe-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="f3dfe-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-164">Signatures</span></span> </li>
<li> <span data-ttu-id="f3dfe-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="f3dfe-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="f3dfe-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-167">Public folders</span></span> </li>
<li> <span data-ttu-id="f3dfe-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3dfe-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="f3dfe-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="f3dfe-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3dfe-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="f3dfe-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="f3dfe-174">Правила клиентского почтового ящика</span><span class="sxs-lookup"><span data-stu-id="f3dfe-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-175"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="f3dfe-176">
<strong>Примечание:</strong> Среда G Suite должна соответствовать требованиям, описанным в миграции <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="f3dfe-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="f3dfe-177">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-178">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-178">Emails</span></span> </li>
<li> <span data-ttu-id="f3dfe-179">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="f3dfe-180">Календарь</span><span class="sxs-lookup"><span data-stu-id="f3dfe-180">Calendar</span></span> </li>
<li> <span data-ttu-id="f3dfe-181">Метки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-182">Правила</span><span class="sxs-lookup"><span data-stu-id="f3dfe-182">Rules</span></span> </li>
<li> <span data-ttu-id="f3dfe-183">Делегаты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-183">Delegates</span></span> </li>
<li> <span data-ttu-id="f3dfe-184">Подписи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-184">Signatures</span></span> </li>
<li> <span data-ttu-id="f3dfe-185">Задачи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-185">Tasks</span></span> </li>
<li> <span data-ttu-id="f3dfe-186">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="f3dfe-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3dfe-187">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-188">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="f3dfe-189">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="f3dfe-190">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3dfe-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-192">Группы Google</span><span class="sxs-lookup"><span data-stu-id="f3dfe-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="f3dfe-193">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="f3dfe-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="f3dfe-194">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="f3dfe-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="f3dfe-195">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="f3dfe-196">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="f3dfe-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="f3dfe-197">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3dfe-198"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-199">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="f3dfe-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="f3dfe-200">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-201">Правила</span><span class="sxs-lookup"><span data-stu-id="f3dfe-201">Rules</span></span> </li>
<li> <span data-ttu-id="f3dfe-202">Делегаты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-202">Delegates</span></span> </li>
<li> <span data-ttu-id="f3dfe-203">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="f3dfe-204">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="f3dfe-204">External contacts</span></span> </li>
<li> <span data-ttu-id="f3dfe-205">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="f3dfe-206">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-207">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="f3dfe-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="f3dfe-208">Календарь</span><span class="sxs-lookup"><span data-stu-id="f3dfe-208">Calendar</span></span> </li>
<li> <span data-ttu-id="f3dfe-209">Подписи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-209">Signatures</span></span> </li>
<li> <span data-ttu-id="f3dfe-210">Задачи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-210">Tasks</span></span> </li>
<li> <span data-ttu-id="f3dfe-211">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="f3dfe-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="f3dfe-212">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-212">Archive data</span></span> </li>
<li> <span data-ttu-id="f3dfe-213">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="f3dfe-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="f3dfe-214">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="f3dfe-215">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="f3dfe-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3dfe-216">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="f3dfe-216">FastTrack responsibilities</span></span>

<span data-ttu-id="f3dfe-217">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-218">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3dfe-219">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="f3dfe-220">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3dfe-221">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="f3dfe-221">Your responsibilities</span></span>

<span data-ttu-id="f3dfe-222">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-223">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3dfe-224">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="f3dfe-225">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="f3dfe-226">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="f3dfe-227">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="f3dfe-228">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="f3dfe-229">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="f3dfe-230">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="f3dfe-231">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="f3dfe-232">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="f3dfe-233">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="f3dfe-234">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="f3dfe-235">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="f3dfe-236">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="f3dfe-237">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="f3dfe-238">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="f3dfe-239">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="f3dfe-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="f3dfe-240">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3dfe-241">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f3dfe-242">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-242">You create and schedule your migration events.</span></span> <span data-ttu-id="f3dfe-243">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3dfe-244">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="f3dfe-245">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-245">Considerations</span></span>

 - <span data-ttu-id="f3dfe-246">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f3dfe-247">Сведения о <a href="https://go.microsoft.com/fwlink/?LinkId=698855">лимитах SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="f3dfe-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="f3dfe-248">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="f3dfe-249">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="f3dfe-249">Source environment details</span></span>

<span data-ttu-id="f3dfe-250">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f3dfe-251">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f3dfe-252">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f3dfe-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f3dfe-254">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f3dfe-255">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="f3dfe-256"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="f3dfe-257"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="f3dfe-258"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-259"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3dfe-260"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f3dfe-261">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-262">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-262">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-263">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-264">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-265">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-266">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-267">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-268">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-268">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-269">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-269">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-270">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-270">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-271">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="f3dfe-272">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f3dfe-273">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f3dfe-274">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f3dfe-275">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-276">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-277">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-278">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-279">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="f3dfe-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f3dfe-280">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="f3dfe-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f3dfe-281">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f3dfe-282">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="f3dfe-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f3dfe-283">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f3dfe-284">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-285">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f3dfe-286">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f3dfe-287">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-288"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-289">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-290">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="f3dfe-291">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-292">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-293">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-294">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-295">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-296">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-296">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-297">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-297">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-298">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-298">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-299">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-300">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f3dfe-301">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-302">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-303">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f3dfe-304">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-305">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-306">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-307">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-308">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-309">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-310">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-311">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-312">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="f3dfe-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f3dfe-313">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f3dfe-314">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f3dfe-315">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f3dfe-316">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-317">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-318">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f3dfe-319">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-320">Файлы, помеченные как ограниченные или не копируемые</span><span class="sxs-lookup"><span data-stu-id="f3dfe-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="f3dfe-321">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3dfe-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-323">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-324">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-324">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-325">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-326">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-327">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-328">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-329">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-330">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-330">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-331">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-331">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-332">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-332">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-333">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-334">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="f3dfe-335">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-336">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-337">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-338">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-339">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-340">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-341">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-342">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-343">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-344">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-345">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-346">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f3dfe-347">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f3dfe-348">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-349">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-350">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-351"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-352">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-353">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-353">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-354">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-355">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-356">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-357">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-358">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-359">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-359">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-360">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-360">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-361">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-361">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-362">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-363">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f3dfe-364">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-365">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-366">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-367">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-368">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-369">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-370">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-371">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-372">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-373">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-374">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f3dfe-375">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f3dfe-376">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f3dfe-377">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f3dfe-378">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f3dfe-379">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-380">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="f3dfe-381">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3dfe-382">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="f3dfe-382">FastTrack responsibilities</span></span>

<span data-ttu-id="f3dfe-383">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-384">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3dfe-385">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="f3dfe-385">Your responsibilities</span></span>

<span data-ttu-id="f3dfe-386">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-387">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="f3dfe-388">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="f3dfe-389">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="f3dfe-390">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="f3dfe-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="f3dfe-391">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3dfe-392">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f3dfe-393">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-393">You create and schedule your migration events.</span></span> <span data-ttu-id="f3dfe-394">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3dfe-395">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="f3dfe-396">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-396">Considerations</span></span>

  - <span data-ttu-id="f3dfe-397">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f3dfe-398">Сведения о <a href="https://go.microsoft.com/fwlink/?LinkId=698855">лимитах SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="f3dfe-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="f3dfe-399">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="f3dfe-400">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="f3dfe-401">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="f3dfe-401">Source environment details</span></span>

<span data-ttu-id="f3dfe-402">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="f3dfe-403">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="f3dfe-404">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="f3dfe-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="f3dfe-406">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="f3dfe-407">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="f3dfe-408"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-409"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-410"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-411"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3dfe-412"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f3dfe-413">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-414">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-414">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-415">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-416">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-417">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-418">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-419">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-420">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-420">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-421">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-421">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-422">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-422">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-423">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="f3dfe-424">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f3dfe-425">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f3dfe-426">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f3dfe-427">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="f3dfe-428">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-429">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-430">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-431">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="f3dfe-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f3dfe-432">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="f3dfe-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f3dfe-433">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f3dfe-434">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="f3dfe-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f3dfe-435">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f3dfe-436">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-437">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f3dfe-438">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f3dfe-439">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-440"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-441">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-442">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="f3dfe-443">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-444">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-445">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-446">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-447">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-448">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-448">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-449">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-449">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-450">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-450">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-451">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-452">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f3dfe-453">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-454">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-455">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f3dfe-456">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-457">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-458">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-459">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-460">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-461">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-462">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-463">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-464">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="f3dfe-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f3dfe-465">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f3dfe-466">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f3dfe-467">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f3dfe-468">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-469">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-470">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f3dfe-471">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-472">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3dfe-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-474">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-475">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-475">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-476">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-477">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-478">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-479">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-480">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-481">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-481">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-482">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-482">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-483">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-483">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-484">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-485">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-486">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-487">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-488">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-489">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-490">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-491">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-492">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-493">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-494">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-495">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-496">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f3dfe-497">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f3dfe-498">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-499">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-500">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-501"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-502">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-503">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-503">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-504">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-505">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-506">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-507">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-508">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-509">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-509">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-510">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-510">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-511">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-511">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-512">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-513">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f3dfe-514">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-515">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-516">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-517">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-518">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-519">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-520">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-521">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-522">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-523">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-524">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f3dfe-525">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f3dfe-526">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f3dfe-527">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f3dfe-528">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f3dfe-529">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-530">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-531">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3dfe-532">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="f3dfe-532">FastTrack responsibilities</span></span>

<span data-ttu-id="f3dfe-533">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-534">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3dfe-535">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="f3dfe-535">Your responsibilities</span></span>

<span data-ttu-id="f3dfe-536">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-537">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="f3dfe-538">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="f3dfe-539">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="f3dfe-540">Миграция в группы Microsoft Teams и Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="f3dfe-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="f3dfe-541">Если вы решите использовать FastTrack для переноса файлов в Группы Microsoft Teams и Microsoft 365, мы предоставляем рекомендации по миграции и миграции данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="f3dfe-542">Мы предоставляем рекомендации по планированию миграции, настройке исходных сред и групп Teams и Microsoft 365 и использования наших служб миграции данных для переноса файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="f3dfe-543">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-543">You create and schedule your migration events.</span></span> <span data-ttu-id="f3dfe-544">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="f3dfe-545">После завершения событий миграции можно ожидать, что файлы из соответствующих запланированных и подходящих источников исходных сред будут перенесены в Teams и Microsoft 365 Groups.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="f3dfe-546">Каналы teams и Группы Microsoft 365 должны быть предварительно предварительно заранее перенаправлены данные в эти типы назначения.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="f3dfe-547">Teams и Microsoft 365 Groups влияют на ваши разрешения в месте назначения файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="f3dfe-548">Teams и Microsoft 365 Groups построены для обеспечения совместной работы.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="f3dfe-549">Канал Teams или группа Microsoft 365 определяют, кто имеет доступ к этим файлам при миграции в эти пункты назначения.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="f3dfe-550">FastTrack не добавляет конечных пользователей или групп ни к каналу Teams, ни к разрешению Microsoft 365 Groups во время миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="f3dfe-551">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-551">Considerations</span></span>

- <span data-ttu-id="f3dfe-552">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="f3dfe-553">Сведения о <a href="https://go.microsoft.com/fwlink/?LinkId=698855">лимитах SharePoint.</a></span><span class="sxs-lookup"><span data-stu-id="f3dfe-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="f3dfe-554">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="f3dfe-555">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="f3dfe-555">Source environment details</span></span>

<span data-ttu-id="f3dfe-556">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="f3dfe-557">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="f3dfe-558">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="f3dfe-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="f3dfe-560">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="f3dfe-561">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="f3dfe-562"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-563"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-564"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="f3dfe-565"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="f3dfe-566"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="f3dfe-567">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-568">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-568">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-569">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-570">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-571">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-572">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-573">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-574">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-574">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-575">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-575">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-576">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-576">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-577">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="f3dfe-578">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="f3dfe-579">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="f3dfe-580">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="f3dfe-581">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="f3dfe-582">На разрешения влияет канал Microsoft 365 Group и/или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f3dfe-583">Если конечным пунктом является канал Microsoft 365 Group или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f3dfe-584">Мы не рекомендуем перенос разрешений на файлы, переносимые на канал Microsoft 365 Group или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-585">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-586">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-587">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="f3dfe-588">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="f3dfe-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="f3dfe-589">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="f3dfe-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="f3dfe-590">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="f3dfe-591">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="f3dfe-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="f3dfe-592">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="f3dfe-593">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-594">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="f3dfe-595">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="f3dfe-596">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-597"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-598">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-599">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="f3dfe-600">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-601">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-602">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-603">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-604">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-605">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-605">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-606">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-606">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-607">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-607">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-608">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-609">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="f3dfe-610">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="f3dfe-611">\*Разрешения влияют на канал Microsoft 365 Group и/или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f3dfe-612">Если конечным пунктом является канал Microsoft 365 Group или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f3dfe-613">Мы не рекомендуем перенос разрешений на файлы, переносимые на канал Microsoft 365 Group или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="f3dfe-614">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-615">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="f3dfe-616">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-617">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-618">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-619">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-620">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-621">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-622">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-623">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-624">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="f3dfe-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="f3dfe-625">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="f3dfe-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="f3dfe-626">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="f3dfe-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="f3dfe-627">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="f3dfe-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="f3dfe-628">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-629">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-630">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="f3dfe-631">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-632">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="f3dfe-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-634">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-635">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-635">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-636">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-637">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-638">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-639">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-640">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-641">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-641">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-642">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-642">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-643">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-643">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-644">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-645">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="f3dfe-646">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="f3dfe-647">\*Разрешения влияют на канал Microsoft 365 Group и/или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f3dfe-648">Если конечным пунктом является канал Microsoft 365 Group или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f3dfe-649">Мы не рекомендуем перенос разрешений на файлы, переносимые на канал Microsoft 365 Group или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="f3dfe-650">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-651">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-652">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-653">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-654">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-655">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-656">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-657">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-658">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-659">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="f3dfe-660">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="f3dfe-661">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="f3dfe-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="f3dfe-662">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-663">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-664">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="f3dfe-665"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="f3dfe-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="f3dfe-666">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="f3dfe-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="f3dfe-667">Документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-667">Documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-668">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="f3dfe-669">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-670">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="f3dfe-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="f3dfe-671">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="f3dfe-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="f3dfe-672">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="f3dfe-673">Дата создания</span><span class="sxs-lookup"><span data-stu-id="f3dfe-673">Created date</span></span> </li>
<li> <span data-ttu-id="f3dfe-674">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-674">Modified date</span></span> </li>
<li> <span data-ttu-id="f3dfe-675">Автор</span><span class="sxs-lookup"><span data-stu-id="f3dfe-675">Created by</span></span> </li>
<li> <span data-ttu-id="f3dfe-676">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="f3dfe-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="f3dfe-677">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="f3dfe-678">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="f3dfe-679">\*Разрешения влияют на канал Microsoft 365 Group и/или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="f3dfe-680">Если конечным пунктом является канал Microsoft 365 Group или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="f3dfe-681">Мы не рекомендуем перенос разрешений на файлы, переносимые на канал Microsoft 365 Group или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="f3dfe-682">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="f3dfe-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="f3dfe-683">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="f3dfe-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="f3dfe-684">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="f3dfe-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-685">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="f3dfe-686">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="f3dfe-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="f3dfe-687">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="f3dfe-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="f3dfe-688">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="f3dfe-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="f3dfe-689">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="f3dfe-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="f3dfe-690">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="f3dfe-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="f3dfe-691">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="f3dfe-692">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="f3dfe-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="f3dfe-693">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="f3dfe-694">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="f3dfe-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="f3dfe-695">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="f3dfe-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="f3dfe-696">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="f3dfe-697">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="f3dfe-698">Файлы или папки, превышающие текущие ограничения <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">и ограничения SharePoint Online</span></a> </span><span class="sxs-lookup"><span data-stu-id="f3dfe-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="f3dfe-699">Обязанности специалистов FastTrack</span><span class="sxs-lookup"><span data-stu-id="f3dfe-699">FastTrack responsibilities</span></span>

<span data-ttu-id="f3dfe-700">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-701">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="f3dfe-702">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="f3dfe-702">Your responsibilities</span></span> 

<span data-ttu-id="f3dfe-703">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="f3dfe-704">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="f3dfe-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="f3dfe-705">Вы также выполняете следующие действия, определенные миграциям Microsoft Teams и Microsoft 365 Groups:</span><span class="sxs-lookup"><span data-stu-id="f3dfe-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="f3dfe-706">Подготовка всех каналов Microsoft Teams и Microsoft 365 Groups в качестве целевых для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="f3dfe-707">FastTrack не предусматривает подготовку каналов Microsoft Teams или Microsoft 365 Groups.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="f3dfe-708">FastTrack не добавляет конечных пользователей или групп в каналы Microsoft Teams или Группы Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="f3dfe-709">Перед переносом данных в эти пункты необходимо добавить конечных пользователей или группы во все каналы Microsoft Teams и Группы Microsoft 365, чтобы эти конечные пользователи могли получать доступ к этим недавно перенесенным документам.</span><span class="sxs-lookup"><span data-stu-id="f3dfe-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>