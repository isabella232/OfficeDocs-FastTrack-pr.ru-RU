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
ms.openlocfilehash: 0e33e8a79ebc577188644dbc69cd78707a575838
ms.sourcegitcommit: 69a30fee5e7e199bd6830fb0837af1ae4904ef3b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/11/2021
ms.locfileid: "52312447"
---
# <a name="data-migration"></a><span data-ttu-id="752b8-104">Перенос данных</span><span class="sxs-lookup"><span data-stu-id="752b8-104">Data Migration</span></span>

<span data-ttu-id="752b8-105">FastTrack поможет вам перенести данные почты и файла вашей исходной среды в Office 365 (Exchange Online. SharePoint Online и OneDrive для бизнеса).</span><span class="sxs-lookup"><span data-stu-id="752b8-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="752b8-106">Тип предоставляемой помощи зависит от количества лицензий Office 365 у вас:</span><span class="sxs-lookup"><span data-stu-id="752b8-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="752b8-107">**Для клиентов Office 365 с 150-499 лицензиями**: FastTrack предоставляет только руководство по переносу данных; ответственность за выполнение переноса данных лежит на вас.</span><span class="sxs-lookup"><span data-stu-id="752b8-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="752b8-108">Вам будет предоставлена документация, которая поможет спланировать и использовать бесплатные ресурсы для самостоятельного переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="752b8-109">**Для клиентов Office 365 с 500 и более лицензиями**: FastTrack предоставляет инструкции по руководство по переносу данных и службы переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="752b8-110">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и клиента Office 365, а также использовать наши службы переноса данных для переноса ваших данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="752b8-111">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-111">You create and schedule your migration events.</span></span> <span data-ttu-id="752b8-112">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="752b8-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="752b8-113">Если вы приобрели или обновили коммерческий план до 9/1/2017, вам необходимо только 150 лицензий для получения доступа к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="752b8-114">В случае планов для образовательных учреждений право на получение доступа к службам переноса данных есть только у преподавателей и персонала с оплаченными лицензиями.</span><span class="sxs-lookup"><span data-stu-id="752b8-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="752b8-115">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="752b8-115">Considerations</span></span>

  - <span data-ttu-id="752b8-116">Ваша исходная среда должна соответствовать определенным ожиданиям для переноса данных в Office 365.</span><span class="sxs-lookup"><span data-stu-id="752b8-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="752b8-117">Дополнительные сведения об ожиданиях исходной среды для Exchange, SharePoint и OneDrive для бизнеса, см. в статье [Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="752b8-118">Для использования служб переноса данных необходимо получить соответствующий доступ и разрешения для вашей исходной среды и клиента Office 365.</span><span class="sxs-lookup"><span data-stu-id="752b8-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="752b8-119">Наши службы переноса данных не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="752b8-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="752b8-120">В процессе переноса данных их можно переносить, хранить и обрабатывать в любом месте, где расположены наши офисы (за исключением случаев, когда для вашего проекта миграции FastTrack предусмотрено иное).</span><span class="sxs-lookup"><span data-stu-id="752b8-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="752b8-121">Мы не можем гарантировать скорость перемещения почты и файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="752b8-122">Непредвиденные проблемы (например, нечитаемые или поврежденные элементы в исходной среде) могут помешать переносу некоторых элементов данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="752b8-123">Внешние факторы, находящиеся вне нашего контроля, например, изменения в API сторонних разработчиков, могут привести к изменениям, задержкам или приостановке работы наших служб переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="752b8-124">Служба переноса данных доступна</span><span class="sxs-lookup"><span data-stu-id="752b8-124">Migration service availability</span></span>

  - <span data-ttu-id="752b8-125">**Для заказчиков — коммерческого сектора и государственных организаций Соединенного Королевства:** предоставляются услуги по переносу данных 24 часа в сутки семь (7) дней в неделю (24x7).</span><span class="sxs-lookup"><span data-stu-id="752b8-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="752b8-126">**Для заказчиков — государственных организаций и Министерства обороны США:** предоставляются услуги по переносу данных 24 часа в сутки пять (5) рабочих дней в неделю (24x5).</span><span class="sxs-lookup"><span data-stu-id="752b8-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="752b8-127">Перенос данных в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="752b8-127">Migration to Exchange Online</span></span>

<span data-ttu-id="752b8-128">После принятия вами решения об использовании FastTrack для переноса электронной почты в Exchange Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="752b8-129">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и Exchange Online, а также использовать наши службы переноса данных для переноса ваших почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="752b8-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="752b8-130">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-130">You create and schedule your migration events.</span></span> <span data-ttu-id="752b8-131">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="752b8-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="752b8-132">После окончания переноса данных, вы можете ожидать переноса почты из запланированных и зарегистрированных исходных почтовых ящиков в вашей исходной среде в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="752b8-133">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="752b8-133">Considerations</span></span>

  - <span data-ttu-id="752b8-134">До переноса данных необходимо выполнить подключения FastTrack для Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="752b8-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="752b8-135">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="752b8-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="752b8-136">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="752b8-137">FastTrack может перенести только в активные почтовые ящики Office 365.</span><span class="sxs-lookup"><span data-stu-id="752b8-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="752b8-138">При миграции из локальной среды Exchange необходимо соответствовать определенным требованиям.</span><span class="sxs-lookup"><span data-stu-id="752b8-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="752b8-139">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="752b8-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="752b8-140">Во всех исходных средах должны быть установлены последние пакет обновления (SP) и накопительный пакет обновления (CU) для соответствующих продуктов.</span><span class="sxs-lookup"><span data-stu-id="752b8-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="752b8-141">Списки рассылки (объекты *MailEnabledGroup*) и внешние контакты (объекты *MailEnabledContact*), которые находятся в локальном каталоге Active Directory, не переносятся при переносе данных почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="752b8-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="752b8-142">Однако вы можете синхронизировать их с помощью Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="752b8-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="752b8-143">Исходные среды</span><span class="sxs-lookup"><span data-stu-id="752b8-143">Source environments</span></span>

<span data-ttu-id="752b8-144">Наша служба переноса данных переносит данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="752b8-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="752b8-145">Один или несколько лесов Active Directory с одной или несколькими организациями Exchange (каждая почтовая система Exchange должна быть Exchange 2010 или более поздней).</span><span class="sxs-lookup"><span data-stu-id="752b8-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="752b8-146">Одна почтовая среда с поддержкой IMAP.</span><span class="sxs-lookup"><span data-stu-id="752b8-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="752b8-147">Среда G Suite (только Gmail, Контакты и Календарь).</span><span class="sxs-lookup"><span data-stu-id="752b8-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="752b8-148">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="752b8-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="752b8-149"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="752b8-150"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="752b8-151"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="752b8-152"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="752b8-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="752b8-154">
<strong>Примечание:</strong> Для локального Exchange зависимостей см. предварительные условия <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">гибридного развертывания.</span></a></span><span class="sxs-lookup"><span data-stu-id="752b8-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="752b8-155">Миграция с гибридным развертыванием</span><span class="sxs-lookup"><span data-stu-id="752b8-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="752b8-156">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="752b8-156">Emails</span></span></li>
<li><span data-ttu-id="752b8-157">Правила почтового ящика на стороне сервера</span><span class="sxs-lookup"><span data-stu-id="752b8-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="752b8-158">Делегаты</span><span class="sxs-lookup"><span data-stu-id="752b8-158">Delegates</span></span></li>
<li><span data-ttu-id="752b8-159">контакты для почтового ящика;</span><span class="sxs-lookup"><span data-stu-id="752b8-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="752b8-160">Календарь</span><span class="sxs-lookup"><span data-stu-id="752b8-160">Calendar</span></span> </li>
<li> <span data-ttu-id="752b8-161">Задачи</span><span class="sxs-lookup"><span data-stu-id="752b8-161">Tasks</span></span> </li>
<li> <span data-ttu-id="752b8-162">Сообщения электронной почты с управляемыми правами</span><span class="sxs-lookup"><span data-stu-id="752b8-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="752b8-163">Зашифрованные сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="752b8-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="752b8-164">Подписи</span><span class="sxs-lookup"><span data-stu-id="752b8-164">Signatures</span></span> </li>
<li> <span data-ttu-id="752b8-165">Личный архив, перенесенный с почтовым ящиком пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="752b8-166">Элементы с возможностью восстановления</span><span class="sxs-lookup"><span data-stu-id="752b8-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-167">Общедоступные папки</span><span class="sxs-lookup"><span data-stu-id="752b8-167">Public folders</span></span> </li>
<li> <span data-ttu-id="752b8-168">Электронные письма, превышающие предельный размер сообщения.</span><span class="sxs-lookup"><span data-stu-id="752b8-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="752b8-169">Архив ведения журнала или сторонние решения для архивации</span><span class="sxs-lookup"><span data-stu-id="752b8-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="752b8-170">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-171">Архивные данные из PST-файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="752b8-172">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="752b8-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="752b8-173">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="752b8-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="752b8-174">Правила клиентского почтового ящика</span><span class="sxs-lookup"><span data-stu-id="752b8-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-175"><strong>Среда G Suite (только Gmail, Контакты и Календарь)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="752b8-176">
<strong>Примечание:</strong> Среда G Suite должна соответствовать требованиям, описанным в миграции <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="752b8-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="752b8-177">Прямая или поэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-178">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="752b8-178">Emails</span></span> </li>
<li> <span data-ttu-id="752b8-179">Контакты почтового ящика (переносятся не более трех адресов электронной почты для каждого контакта)</span><span class="sxs-lookup"><span data-stu-id="752b8-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="752b8-180">Календарь</span><span class="sxs-lookup"><span data-stu-id="752b8-180">Calendar</span></span> </li>
<li> <span data-ttu-id="752b8-181">Метки</span><span class="sxs-lookup"><span data-stu-id="752b8-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-182">Правила</span><span class="sxs-lookup"><span data-stu-id="752b8-182">Rules</span></span> </li>
<li> <span data-ttu-id="752b8-183">Делегаты</span><span class="sxs-lookup"><span data-stu-id="752b8-183">Delegates</span></span> </li>
<li> <span data-ttu-id="752b8-184">Подписи</span><span class="sxs-lookup"><span data-stu-id="752b8-184">Signatures</span></span> </li>
<li> <span data-ttu-id="752b8-185">Задачи</span><span class="sxs-lookup"><span data-stu-id="752b8-185">Tasks</span></span> </li>
<li> <span data-ttu-id="752b8-186">Письма и вложения, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="752b8-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="752b8-187">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-188">Архивные данные из PST-файлов или стороннего архива (например, Google Сейфа)</span><span class="sxs-lookup"><span data-stu-id="752b8-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="752b8-189">Сообщения с управляемыми правами или зашифрованные сообщения</span><span class="sxs-lookup"><span data-stu-id="752b8-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="752b8-190">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="752b8-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="752b8-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="752b8-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="752b8-192">Группы Google</span><span class="sxs-lookup"><span data-stu-id="752b8-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="752b8-193">Почтовые ящики ресурса</span><span class="sxs-lookup"><span data-stu-id="752b8-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="752b8-194">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="752b8-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="752b8-195">Параметры отпусков и параметры автоматических ответов</span><span class="sxs-lookup"><span data-stu-id="752b8-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="752b8-196">Общие календари, облачные вложения, ссылки Google Hangout и цвета событий</span><span class="sxs-lookup"><span data-stu-id="752b8-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="752b8-197">Сохраненные сообщения Hangout\*\* переносятся.</span><span class="sxs-lookup"><span data-stu-id="752b8-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="752b8-198"><strong>Источник IMAP4 (например, Domino, GroupWise или Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="752b8-199">Миграция с помощью собственных средств IMAP4</span><span class="sxs-lookup"><span data-stu-id="752b8-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="752b8-200">Сообщения электронной почты</span><span class="sxs-lookup"><span data-stu-id="752b8-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="752b8-201">Правила</span><span class="sxs-lookup"><span data-stu-id="752b8-201">Rules</span></span> </li>
<li> <span data-ttu-id="752b8-202">Делегаты</span><span class="sxs-lookup"><span data-stu-id="752b8-202">Delegates</span></span> </li>
<li> <span data-ttu-id="752b8-203">Списки рассылки</span><span class="sxs-lookup"><span data-stu-id="752b8-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="752b8-204">Внешние контакты</span><span class="sxs-lookup"><span data-stu-id="752b8-204">External contacts</span></span> </li>
<li> <span data-ttu-id="752b8-205">Пользователи с включенной поддержкой почты.</span><span class="sxs-lookup"><span data-stu-id="752b8-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="752b8-206">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-207">Контакты почтового ящика</span><span class="sxs-lookup"><span data-stu-id="752b8-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="752b8-208">Календарь</span><span class="sxs-lookup"><span data-stu-id="752b8-208">Calendar</span></span> </li>
<li> <span data-ttu-id="752b8-209">Подписи</span><span class="sxs-lookup"><span data-stu-id="752b8-209">Signatures</span></span> </li>
<li> <span data-ttu-id="752b8-210">Задачи</span><span class="sxs-lookup"><span data-stu-id="752b8-210">Tasks</span></span> </li>
<li> <span data-ttu-id="752b8-211">Сообщения электронной почты, превышающие предельный размер</span><span class="sxs-lookup"><span data-stu-id="752b8-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="752b8-212">Архивные данные</span><span class="sxs-lookup"><span data-stu-id="752b8-212">Archive data</span></span> </li>
<li> <span data-ttu-id="752b8-213">Зашифрованная электронная почта</span><span class="sxs-lookup"><span data-stu-id="752b8-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="752b8-214">Поврежденные элементы</span><span class="sxs-lookup"><span data-stu-id="752b8-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="752b8-215">Неактивные почтовые ящики</span><span class="sxs-lookup"><span data-stu-id="752b8-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="752b8-216">Обязанности FastTrack для Exchange Online миграций</span><span class="sxs-lookup"><span data-stu-id="752b8-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="752b8-217">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-218">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="752b8-219">Наши специалисты FastTrack выполняют также следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="752b8-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="752b8-220">Предоставляют руководство по включению сосуществования маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="752b8-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="752b8-221">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="752b8-221">Your responsibilities</span></span>

<span data-ttu-id="752b8-222">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-223">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="752b8-224">Вы также выполняете следующие действия, относящиеся к переносу данных в Exchange:</span><span class="sxs-lookup"><span data-stu-id="752b8-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="752b8-225">Выполнить подключение FastTrack для Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="752b8-226">При самостоятельном подключении требуется пройти необходимые проверки и выполнить предварительные условия.</span><span class="sxs-lookup"><span data-stu-id="752b8-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="752b8-227">Дополнительные сведения см. в разделе[Продукты и возможности](products-and-capabilities.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="752b8-228">Устанавливаете клиентское программное обеспечение необходимого уровня согласно рекомендациям для Office 365.</span><span class="sxs-lookup"><span data-stu-id="752b8-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="752b8-229">Дополнительные сведения см. в разделе [Современное рабочее место](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg).</span><span class="sxs-lookup"><span data-stu-id="752b8-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="752b8-230">Соответствие определенным требованиям при миграции из локальной среды Exchange.</span><span class="sxs-lookup"><span data-stu-id="752b8-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="752b8-231">Дополнительные сведения см. в разделе [Предварительные условия для гибридного развертывания](https://go.microsoft.com/fwlink/?LinkId=787528).</span><span class="sxs-lookup"><span data-stu-id="752b8-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="752b8-232">Убедитесь, что в каждой исходной среде используется последний пакет обновления (SP) и накопительный (RU) пакет обновления (CU), если это применимо.</span><span class="sxs-lookup"><span data-stu-id="752b8-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="752b8-233">Настройте и подтвердите сосуществование маршрутизации почты SMTP между вашими исходными средами и Exchange Online, если это применимо.</span><span class="sxs-lookup"><span data-stu-id="752b8-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="752b8-234">Убедитесь, что размер исходного почтового ящика не превышает квоту конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="752b8-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="752b8-235">В зависимости от исходной платформы может потребоваться ограничить объем исходных данных 85 процентами квоты конечного почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="752b8-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="752b8-236">При необходимости перенесите данные клиента.</span><span class="sxs-lookup"><span data-stu-id="752b8-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="752b8-237">Помимо прочего эти данные включают локальные адресные книги, данные в локальных PST-файлах, правила Outlook и локальные параметры Outlook.</span><span class="sxs-lookup"><span data-stu-id="752b8-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="752b8-238">Помогите вашим конечным пользователям в устранении проблем, связанных с переносом данных клиента.</span><span class="sxs-lookup"><span data-stu-id="752b8-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="752b8-239">Миграция в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="752b8-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="752b8-240">После принятия вами решения об использовании FastTrack для переноса ваших файлов в SharePoint Online, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="752b8-241">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и SharePoint Online, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="752b8-242">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-242">You create and schedule your migration events.</span></span> <span data-ttu-id="752b8-243">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="752b8-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="752b8-244">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="752b8-245">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="752b8-245">Considerations</span></span>

 - <span data-ttu-id="752b8-246">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="752b8-247">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="752b8-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="752b8-248">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="752b8-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="752b8-249">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="752b8-249">Source environment details</span></span>

<span data-ttu-id="752b8-250">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="752b8-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="752b8-251">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="752b8-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="752b8-252">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="752b8-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="752b8-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="752b8-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="752b8-254">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="752b8-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="752b8-255">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="752b8-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="752b8-256"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="752b8-257"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="752b8-258"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="752b8-259"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="752b8-260"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="752b8-261">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-262">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-262">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-263">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-264">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="752b8-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-265">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="752b8-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-266">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-267">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-268">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-268">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-269">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-269">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-270">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-270">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-271">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="752b8-272">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="752b8-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="752b8-273">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="752b8-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="752b8-274">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="752b8-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="752b8-275">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="752b8-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-276">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-277">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-278">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-279">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="752b8-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="752b8-280">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="752b8-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="752b8-281">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="752b8-282">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="752b8-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="752b8-283">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="752b8-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="752b8-284">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-285">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="752b8-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="752b8-286">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="752b8-287">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-288"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="752b8-289">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-290">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office), в том числе файлы, превышающие 10 МБ</span><span class="sxs-lookup"><span data-stu-id="752b8-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="752b8-291">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-292">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-293">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-294">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-295">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-296">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-296">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-297">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-297">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-298">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-298">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-299">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-300">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="752b8-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="752b8-301">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-302">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-303">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="752b8-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="752b8-304">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-305">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-306">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-307">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-308">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-309">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-310">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-311">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-312">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="752b8-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="752b8-313">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="752b8-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="752b8-314">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="752b8-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="752b8-315">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="752b8-316">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-317">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-318">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="752b8-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="752b8-319">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-320">Файлы, помеченные как ограниченные или не копируемые</span><span class="sxs-lookup"><span data-stu-id="752b8-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="752b8-321">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="752b8-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="752b8-323">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-324">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-324">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-325">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-326">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-327">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-328">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-329">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-330">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-330">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-331">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-331">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-332">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-332">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-333">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-334">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="752b8-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="752b8-335">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="752b8-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-336">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-337">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-338">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-339">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-340">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="752b8-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-341">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-342">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-343">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-344">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-345">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-346">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="752b8-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="752b8-347">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="752b8-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="752b8-348">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-349">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-350">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-351"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="752b8-352">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-353">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-353">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-354">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-355">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-356">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-357">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-358">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-359">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-359">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-360">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-360">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-361">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-361">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-362">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-363">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="752b8-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="752b8-364">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-365">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-366">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-367">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-368">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-369">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-370">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-371">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-372">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-373">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-374">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="752b8-375">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="752b8-376">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="752b8-377">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="752b8-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="752b8-378">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="752b8-379">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-380">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных)</span><span class="sxs-lookup"><span data-stu-id="752b8-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="752b8-381">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="752b8-382">Обязанности FastTrack для SharePoint миграций в Интернете</span><span class="sxs-lookup"><span data-stu-id="752b8-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="752b8-383">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-384">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="752b8-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="752b8-385">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="752b8-385">Your responsibilities</span></span>

<span data-ttu-id="752b8-386">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-387">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md)</span><span class="sxs-lookup"><span data-stu-id="752b8-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="752b8-388">Вы также выполняете следующие действия, относящиеся к переносу данных в SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="752b8-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="752b8-389">Настройте все сайты группы SharePoint для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="752b8-390">Миграция в OneDrive для бизнеса</span><span class="sxs-lookup"><span data-stu-id="752b8-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="752b8-391">После принятия вами решения об использовании FastTrack для переноса ваших файлов в OneDrive для бизнеса, вам будут предоставлены руководство по переносу данных и доступ к службам переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="752b8-392">Вам будет предоставлено руководство, которое поможет спланировать перенос ваших данных, настроить вашу исходную среду и OneDrive для бизнеса, а также использовать наши службы переноса данных для переноса ваших файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="752b8-393">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-393">You create and schedule your migration events.</span></span> <span data-ttu-id="752b8-394">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="752b8-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="752b8-395">После окончания переноса данных, вы можете ожидать переноса файлов из запланированных и зарегистрированных исходных источников в вашей исходной среде в OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="752b8-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

### <a name="considerations"></a><span data-ttu-id="752b8-396">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="752b8-396">Considerations</span></span>

  - <span data-ttu-id="752b8-397">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="752b8-398">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="752b8-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="752b8-399">Рекомендуем ограничить объем всех перенесенных вами данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="752b8-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="752b8-400">FastTrack переносится только на активные диски OneDrive для бизнеса.</span><span class="sxs-lookup"><span data-stu-id="752b8-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

### <a name="source-environment-details"></a><span data-ttu-id="752b8-401">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="752b8-401">Source environment details</span></span>

<span data-ttu-id="752b8-402">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="752b8-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="752b8-403">Файловые ресурсы (общие папки SMB на устройствах, поддерживающих SMB 2.0 и более поздней версии).</span><span class="sxs-lookup"><span data-stu-id="752b8-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="752b8-404">Одна среда G Suite (только Google Drive).</span><span class="sxs-lookup"><span data-stu-id="752b8-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="752b8-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="752b8-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="752b8-406">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="752b8-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="752b8-407">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="752b8-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="752b8-408"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="752b8-409"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="752b8-410"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="752b8-411"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="752b8-412"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="752b8-413">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-414">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-414">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-415">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-416">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="752b8-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-417">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="752b8-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-418">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-419">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-420">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-420">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-421">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-421">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-422">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-422">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-423">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="752b8-424">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="752b8-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="752b8-425">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="752b8-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="752b8-426">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="752b8-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="752b8-427">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="752b8-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="752b8-428">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-429">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-430">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-431">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="752b8-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="752b8-432">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="752b8-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="752b8-433">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="752b8-434">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="752b8-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="752b8-435">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="752b8-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="752b8-436">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-437">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="752b8-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="752b8-438">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="752b8-439">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-440"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="752b8-441">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-442">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="752b8-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="752b8-443">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-444">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-445">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-446">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-447">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-448">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-448">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-449">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-449">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-450">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-450">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-451">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-452">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="752b8-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="752b8-453">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-454">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-455">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="752b8-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="752b8-456">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-457">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-458">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-459">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-460">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-461">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-462">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-463">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-464">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="752b8-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="752b8-465">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="752b8-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="752b8-466">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="752b8-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="752b8-467">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="752b8-468">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-469">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-470">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="752b8-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="752b8-471">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-472">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="752b8-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="752b8-474">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-475">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-475">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-476">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-477">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-478">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-479">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-480">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-481">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-481">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-482">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-482">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-483">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-483">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-484">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-485">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="752b8-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-486">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-487">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-488">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-489">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-490">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="752b8-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-491">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-492">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-493">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-494">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-495">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-496">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="752b8-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="752b8-497">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="752b8-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="752b8-498">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-499">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-500">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-501"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="752b8-502">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-503">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-503">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-504">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-505">Разрешения на доступ к папкам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-506">Разрешения на доступ к папкам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="752b8-507">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-508">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-509">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-509">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-510">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-510">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-511">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-511">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-512">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-513">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="752b8-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="752b8-514">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="752b8-515">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-516">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-517">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-518">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-519">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-520">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-521">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-522">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-523">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-524">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="752b8-525">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="752b8-526">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="752b8-527">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="752b8-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="752b8-528">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="752b8-529">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-530">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-531">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="752b8-532">Обязанности FastTrack для OneDrive для бизнеса миграций</span><span class="sxs-lookup"><span data-stu-id="752b8-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="752b8-533">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-534">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="752b8-535">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="752b8-535">Your responsibilities</span></span>

<span data-ttu-id="752b8-536">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-537">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="752b8-538">Вы также выполняете следующие действия, относящиеся к переносу данных в OneDrive для бизнеса:</span><span class="sxs-lookup"><span data-stu-id="752b8-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="752b8-539">Настройте все сайты OneDrive для бизнеса для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="752b8-540">Миграция в Microsoft Teams и Microsoft 365 группы</span><span class="sxs-lookup"><span data-stu-id="752b8-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="752b8-541">Если вы решите использовать FastTrack для переноса файлов в группы Microsoft Teams Microsoft 365, мы предоставляем рекомендации по миграции и миграции данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="752b8-542">Мы предоставляем рекомендации по планированию миграции, настройке исходных сред и групп Teams и Microsoft 365 и использования наших служб миграции данных для переноса файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="752b8-543">Создайте и запланируйте события переноса данных.</span><span class="sxs-lookup"><span data-stu-id="752b8-543">You create and schedule your migration events.</span></span> <span data-ttu-id="752b8-544">Мы запускаем события переноса данных в соответствии с вашим графиком, следим за их ходом и предоставляем отчеты о состоянии.</span><span class="sxs-lookup"><span data-stu-id="752b8-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="752b8-545">По завершению событий миграции можно ожидать перенос файлов из надлежащим образом запланированных и подходящих источников исходных сред в Teams и Microsoft 365 Groups.</span><span class="sxs-lookup"><span data-stu-id="752b8-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="752b8-546">Teams каналов и Microsoft 365 группы должны быть предварительно заранее перенаправлены данные в эти типы назначения.</span><span class="sxs-lookup"><span data-stu-id="752b8-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="752b8-547">Teams и Microsoft 365 группы влияют на ваши разрешения в расположении назначения файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="752b8-548">Teams и Microsoft 365 группы построены для того, чтобы разрешить совместную работу.</span><span class="sxs-lookup"><span data-stu-id="752b8-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="752b8-549">Группа Teams или Microsoft 365 определяет, кто имеет доступ к этим файлам при миграции в эти пункты назначения.</span><span class="sxs-lookup"><span data-stu-id="752b8-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="752b8-550">FastTrack не добавляет конечных пользователей или групп в Teams или Microsoft 365 групп во время миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

### <a name="considerations"></a><span data-ttu-id="752b8-551">Рекомендации</span><span class="sxs-lookup"><span data-stu-id="752b8-551">Considerations</span></span>

- <span data-ttu-id="752b8-552">На все миграции распространяются квоты SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="752b8-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="752b8-553">Обратитесь <a href="https://go.microsoft.com/fwlink/?LinkId=698855">к SharePoint для</a> подробных сведений.</span><span class="sxs-lookup"><span data-stu-id="752b8-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="752b8-554">Рекомендуем ограничить объем всех перенесенных данных до 75 % места от общей квоты хранилища SharePoint Online. Это условие распространяется и на дополнительное пространство в хранилище, которое можно приобрести дополнительно.</span><span class="sxs-lookup"><span data-stu-id="752b8-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


### <a name="source-environment-details"></a><span data-ttu-id="752b8-555">Сведения об исходной среде</span><span class="sxs-lookup"><span data-stu-id="752b8-555">Source environment details</span></span>

<span data-ttu-id="752b8-556">Наши службы переноса данных переносят данные из следующих исходных сред:</span><span class="sxs-lookup"><span data-stu-id="752b8-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="752b8-557">Файловые ресурсы (общие каталоги SMB на устройствах, поддерживающих SMB 2.0 и более поздних версий).</span><span class="sxs-lookup"><span data-stu-id="752b8-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="752b8-558">Одна среда G Suite (только Google Диск).</span><span class="sxs-lookup"><span data-stu-id="752b8-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="752b8-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="752b8-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="752b8-560">Dropbox для Teams (стандартная и расширенная).</span><span class="sxs-lookup"><span data-stu-id="752b8-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="752b8-561">В следующей таблице представлена подробная информация о переносе данных, относящиеся к каждой исходной среде:</span><span class="sxs-lookup"><span data-stu-id="752b8-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="752b8-562"><strong>Исходная среда</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="752b8-563"><strong>Тип миграции</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="752b8-564"><strong>Что переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="752b8-565"><strong>Что не переносится</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="752b8-566"><strong>Любое устройство с файловым ресурсом, поддерживающее SMB 2.0 и более поздних версий</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="752b8-567">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-568">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-568">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-569">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-570">Разрешения на доступ к папкам и файлам на уровне пользователя\*</span><span class="sxs-lookup"><span data-stu-id="752b8-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-571">Разрешения на доступ к папкам и файлам на уровне группы\*</span><span class="sxs-lookup"><span data-stu-id="752b8-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-572">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-573">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-574">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-574">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-575">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-575">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-576">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-576">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-577">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="752b8-578">\* Требуется настроить синхронизацию службы каталогов.</span><span class="sxs-lookup"><span data-stu-id="752b8-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="752b8-579">Переносятся только разрешения NTFS, доступные в проводнике Windows.</span><span class="sxs-lookup"><span data-stu-id="752b8-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="752b8-580">Разрешения, управление которыми происходит непосредственно на устройствах с файловым ресурсом, не переносятся.</span><span class="sxs-lookup"><span data-stu-id="752b8-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="752b8-581">Если данные хранятся на устройстве SMB 2.0, переносятся разрешения, эквивалентные разрешениям NTFS, предоставляемые протоколом SMB.</span><span class="sxs-lookup"><span data-stu-id="752b8-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="752b8-582">Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="752b8-583">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="752b8-584">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-585">Журнал владения и предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-586">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-587">Предыдущие версии</span><span class="sxs-lookup"><span data-stu-id="752b8-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="752b8-588">Атрибуты файлов и папок Windows (например, "Только чтение", "Скрытый")</span><span class="sxs-lookup"><span data-stu-id="752b8-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="752b8-589">Дополнительные разрешения и специальные параметры NTFS в Windows и другой операционной системе</span><span class="sxs-lookup"><span data-stu-id="752b8-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="752b8-590">Разрешения на отклонение, предоставленные непосредственно (удаляются после миграции, содержимое, для которого назначены параллельные разрешения или разрешения для родительской папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="752b8-591">Конфигурация аудита NTFS</span><span class="sxs-lookup"><span data-stu-id="752b8-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="752b8-592">Дополнительные метаданные файлов, предоставленные инфраструктурой классификации файлов (FCI).</span><span class="sxs-lookup"><span data-stu-id="752b8-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="752b8-593">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-594">Скрытые общие папки</span><span class="sxs-lookup"><span data-stu-id="752b8-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="752b8-595">Общий доступ (например, разрешения, предоставленные на уровне общей папки)</span><span class="sxs-lookup"><span data-stu-id="752b8-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="752b8-596">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-597"><strong>Одна среда G Suite (только Google Диск)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="752b8-598">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-599">"Google Документы", "Google Таблицы", "Google Презентации" (файлы преобразуются в эквивалентный формат Office, в том числе файлы, превышающие 10 МБ)</span><span class="sxs-lookup"><span data-stu-id="752b8-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="752b8-600">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-601">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="752b8-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-602">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="752b8-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-603">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-604">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-605">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-605">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-606">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-606">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-607">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-607">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-608">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-609">Общие диски (папки и файлы)</span><span class="sxs-lookup"><span data-stu-id="752b8-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="752b8-610">Общее содержимое, принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="752b8-611">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="752b8-612">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="752b8-613">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="752b8-614">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-615">Описания файлов и папок, цвета папок</span><span class="sxs-lookup"><span data-stu-id="752b8-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="752b8-616">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-617">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-618">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-619">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-620">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-621">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-622">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-623">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-624">Google Фото, Google Формы, Google Карты и другие связанные приложения  </span><span class="sxs-lookup"><span data-stu-id="752b8-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="752b8-625">Google Рисунки</span><span class="sxs-lookup"><span data-stu-id="752b8-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="752b8-626">Общее содержимое, не хранящееся на серверах организации</span><span class="sxs-lookup"><span data-stu-id="752b8-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="752b8-627">Содержимое, не принадлежащее переносимой учетной записи Google Drive</span><span class="sxs-lookup"><span data-stu-id="752b8-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="752b8-628">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты администратора Google Drive для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-629">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-630">Разрешения на доступ к общему диску (<strong>Note</strong>: Используйте отчеты администратора Google Drive для определения наличия доступа к общему диску.</span><span class="sxs-lookup"><span data-stu-id="752b8-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="752b8-631">Проинструктируйте конечных пользователей о необходимости настроить параметры их доступа в целевой системе перед переносом данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-632">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="752b8-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="752b8-634">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-635">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-635">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-636">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-637">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="752b8-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-638">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="752b8-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-639">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-640">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-641">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-641">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-642">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-642">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-643">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-643">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-644">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-645">Общее содержимое, принадлежащее переносимой учетной записи Box</span><span class="sxs-lookup"><span data-stu-id="752b8-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="752b8-646">Box Notes (преобразован в формат документа Word)</span><span class="sxs-lookup"><span data-stu-id="752b8-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="752b8-647">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="752b8-648">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="752b8-649">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="752b8-650">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-651">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-652">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-653">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-654">Дополнительные метаданные и теги Box</span><span class="sxs-lookup"><span data-stu-id="752b8-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-655">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-656">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-657">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-658">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-659">Заблокированные или неактивные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="752b8-660">Приложения Box, закладки, избранное и рабочие процессы</span><span class="sxs-lookup"><span data-stu-id="752b8-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="752b8-661">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Box</span><span class="sxs-lookup"><span data-stu-id="752b8-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="752b8-662">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Box для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-663">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-664">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="752b8-665"><strong>Dropbox для Teams (стандартная и расширенная)</strong></span><span class="sxs-lookup"><span data-stu-id="752b8-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="752b8-666">Одно- или многоэтапная миграция</span><span class="sxs-lookup"><span data-stu-id="752b8-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="752b8-667">Документы</span><span class="sxs-lookup"><span data-stu-id="752b8-667">Documents</span></span> </li>
<li> <span data-ttu-id="752b8-668">Структура файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="752b8-669">Разрешения папок на уровне пользователей\*</span><span class="sxs-lookup"><span data-stu-id="752b8-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-670">Разрешения на папку группового уровня\*</span><span class="sxs-lookup"><span data-stu-id="752b8-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="752b8-671">Файлы размером до 15 ГБ</span><span class="sxs-lookup"><span data-stu-id="752b8-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="752b8-672">Базовые метаданные документов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="752b8-673">Дата создания</span><span class="sxs-lookup"><span data-stu-id="752b8-673">Created date</span></span> </li>
<li> <span data-ttu-id="752b8-674">Дата изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-674">Modified date</span></span> </li>
<li> <span data-ttu-id="752b8-675">Автор</span><span class="sxs-lookup"><span data-stu-id="752b8-675">Created by</span></span> </li>
<li> <span data-ttu-id="752b8-676">Автор последнего изменения</span><span class="sxs-lookup"><span data-stu-id="752b8-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="752b8-677">Папки и содержимое для совместной работы</span><span class="sxs-lookup"><span data-stu-id="752b8-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="752b8-678">Общее содержимое, принадлежащее переносимой учетной записи Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="752b8-679">\*Разрешения влияют на Microsoft 365 и/или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="752b8-680">Если конечным пунктом является канал Microsoft 365 или Microsoft Teams, группа или канал определяют окончательный профиль разрешений для перенесенных файлов.</span><span class="sxs-lookup"><span data-stu-id="752b8-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="752b8-681">Мы не рекомендуем перенос разрешений на файлы, мигрирующие в Microsoft 365 или Microsoft Teams канал.</span><span class="sxs-lookup"><span data-stu-id="752b8-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="752b8-682">Журнал владения, предыдущие версии и комментарии</span><span class="sxs-lookup"><span data-stu-id="752b8-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="752b8-683">Описания файлов и папок</span><span class="sxs-lookup"><span data-stu-id="752b8-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="752b8-684">Разрешения на доступ к файлам на уровне пользователя</span><span class="sxs-lookup"><span data-stu-id="752b8-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-685">Разрешения на доступ к файлам на уровне группы</span><span class="sxs-lookup"><span data-stu-id="752b8-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="752b8-686">Расширенные метаданные</span><span class="sxs-lookup"><span data-stu-id="752b8-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="752b8-687">Атрибуты блокировки файлов</span><span class="sxs-lookup"><span data-stu-id="752b8-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="752b8-688">Преобразование внедренных URL-адресов в содержимом</span><span class="sxs-lookup"><span data-stu-id="752b8-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="752b8-689">Элементы, перемещенные в корзину</span><span class="sxs-lookup"><span data-stu-id="752b8-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="752b8-690">Поврежденные и недоступные документы</span><span class="sxs-lookup"><span data-stu-id="752b8-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="752b8-691">Несмонтированные папки Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="752b8-692">Удаленные или отключенные пользователи</span><span class="sxs-lookup"><span data-stu-id="752b8-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="752b8-693">Документы, демонстрации и пробелы Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="752b8-694">Приложения и Избранное Dropbox (закрепленные файлы и звезды)</span><span class="sxs-lookup"><span data-stu-id="752b8-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="752b8-695">Содержимое, которое не принадлежит пользователю с перенесенной учетной записью Dropbox</span><span class="sxs-lookup"><span data-stu-id="752b8-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="752b8-696">Разрешения и основные метаданные внешних пользователей (<strong>Примечание</strong>: Используйте отчеты Dropbox для идентификации содержимого, совместно используемого с внешними пользователями.</span><span class="sxs-lookup"><span data-stu-id="752b8-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="752b8-697">Проинструктируйте конечных пользователей о необходимости повторно предоставить общий доступ к содержимому после переноса данных).</span><span class="sxs-lookup"><span data-stu-id="752b8-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="752b8-698">Файлы или папки, превышающие текущие SharePoint ограничения и ограничения в Интернете <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline"></span></a> </span><span class="sxs-lookup"><span data-stu-id="752b8-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="752b8-699">Обязанности FastTrack для миграций Microsoft Teams и Microsoft 365 групп</span><span class="sxs-lookup"><span data-stu-id="752b8-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="752b8-700">Наши специалисты FastTrack выполняют стандартные действия в процессе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-701">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

### <a name="your-responsibilities"></a><span data-ttu-id="752b8-702">Ваши обязанности</span><span class="sxs-lookup"><span data-stu-id="752b8-702">Your responsibilities</span></span> 

<span data-ttu-id="752b8-703">Вы выполняете стандартные действия в ходе проекта миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="752b8-704">Дополнительные сведения об обязанностях по переносу данных см. в разделе[Процесс и ожидания](process-and-expectations.md).</span><span class="sxs-lookup"><span data-stu-id="752b8-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="752b8-705">Вы также выполняете следующие действия, определенные миграциям Microsoft Teams и Microsoft 365 групп:</span><span class="sxs-lookup"><span data-stu-id="752b8-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="752b8-706">Подготовка всех Microsoft Teams каналов и Microsoft 365 групп в качестве целевых для событий миграции.</span><span class="sxs-lookup"><span data-stu-id="752b8-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="752b8-707">FastTrack не заранее Microsoft Teams каналов или Microsoft 365 групп.</span><span class="sxs-lookup"><span data-stu-id="752b8-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="752b8-708">FastTrack не добавляет конечных пользователей или групп в Microsoft Teams или Microsoft 365 группы.</span><span class="sxs-lookup"><span data-stu-id="752b8-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="752b8-709">Перед переносом данных в эти пункты необходимо добавить конечных пользователей или группы во все Microsoft Teams и группы Microsoft 365, чтобы эти конечные пользователи могли получать доступ к этим недавно перенесенным документам.</span><span class="sxs-lookup"><span data-stu-id="752b8-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>