---
title: Приложение А. Миграция с IBM Domino в Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/27/18
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'Переход с IBM Domino на Exchange Online включает ряд важных аспектов, в том числе действия, выполняемые в ходе следующих этапов:'
ms.openlocfilehash: 99374774942ff70156977460831bda9fe7a0a151
ms.sourcegitcommit: ce2f0b156075cb8f07efa96c02115baf20779b6d
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/30/2018
ms.locfileid: "21499156"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="6d57c-103">Приложение А. Миграция с IBM Domino в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="6d57c-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="6d57c-104">Переход с IBM Domino на Exchange Online включает ряд важных аспектов, в том числе действия, выполняемые в ходе следующих этапов:</span><span class="sxs-lookup"><span data-stu-id="6d57c-104">Migration from IBM Domino to MO_ExchangeOnline_2nd includes several important aspects, including what happens during the following phases:</span></span>
  
- [<span data-ttu-id="6d57c-105">Начальная фаза</span><span class="sxs-lookup"><span data-stu-id="6d57c-105">Initiate phase</span></span>](#initiate-phase)
    
- [<span data-ttu-id="6d57c-106">Фаза оценки</span><span class="sxs-lookup"><span data-stu-id="6d57c-106">Assess phase</span></span>](#assess-phase)
    
- [<span data-ttu-id="6d57c-107">Фаза исправления</span><span class="sxs-lookup"><span data-stu-id="6d57c-107">Remediate phase</span></span>](#remediate-phase)
    
- [<span data-ttu-id="6d57c-108">Фаза включения</span><span class="sxs-lookup"><span data-stu-id="6d57c-108">Enable phase</span></span>](#enable-phase)
    
- [<span data-ttu-id="6d57c-109">Фаза миграции</span><span class="sxs-lookup"><span data-stu-id="6d57c-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="6d57c-110">Удостоверения</span><span class="sxs-lookup"><span data-stu-id="6d57c-110">Identities</span></span>

<span data-ttu-id="6d57c-p101">Вы несете ответственность за создание удостоверений (облачных, синхронизированных или объединенных с локальной службой Active Directory) и управление ими. Сопоставление удостоверений (если это еще не сделано) между Domino и локальной службой Active Directory или Azure AD необходимо выполнить на ранних этапах подключения.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p101">You are responsible for creating and managing the identities (Cloud only, synchronized, or federated with their on-premises Active Directory). You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or WindowsAzureAD_2nd during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="6d57c-113">Сосуществование</span><span class="sxs-lookup"><span data-stu-id="6d57c-113">Coexistence</span></span>

<span data-ttu-id="6d57c-114">Преимущество FastTrack Center для Office 365 обеспечивает двунаправленный поток обработки почты между локальной средой Domino и Exchange Online для всех клиентов.</span><span class="sxs-lookup"><span data-stu-id="6d57c-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="6d57c-115">Миграция</span><span class="sxs-lookup"><span data-stu-id="6d57c-115">Migration</span></span>

<span data-ttu-id="6d57c-p102">Стандартный процесс миграции Domino в Exchange Online для FastTrack Center включает предварительное размещение данных Domino в Azure перед переносом в почтовые ящики Exchange Online. Для миграции FastTrack вам и сотрудникам FastTrack Center потребуется выполнять некоторые действия на разных этапах подключения. Эти действия рассматриваются в следующих разделах.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p102">The standard FastTrack Center process for migration from Domino to MO_ExchangeOnline_2nd involves pre-staging Domino data to WindowsAzure before migration to MO_ExchangeOnline_2nd mailboxes.
FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. These activities are outlined in the following sections.
</span></span>
  
> [!NOTE]
> <span data-ttu-id="6d57c-p103">Данные, переносимые с помощью служб FastTrack, могут передаваться, храниться и обрабатываться в США или в других странах, в которых имеются необходимые средства корпорации Майкрософт. Службы FastTrack не предназначены для работы с данными, попадающими под действие особых законодательных или нормативных актов.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="6d57c-121">Начальная фаза</span><span class="sxs-lookup"><span data-stu-id="6d57c-121">Initiate phase</span></span>

 <span data-ttu-id="6d57c-122">**Основные действия**</span><span class="sxs-lookup"><span data-stu-id="6d57c-122">**Key actions**</span></span>
  
- <span data-ttu-id="6d57c-123">Определите Domino в качестве исходной почтовой платформы.</span><span class="sxs-lookup"><span data-stu-id="6d57c-123">Identify Domino as the source mail platform.</span></span>
    
- <span data-ttu-id="6d57c-124">Определите, выполняет ли FastTrack Center миграцию.</span><span class="sxs-lookup"><span data-stu-id="6d57c-124">Determine whether FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="6d57c-125">**Обязанности клиента**</span><span class="sxs-lookup"><span data-stu-id="6d57c-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="6d57c-126">Предоставьте основные сведения об исходной платформе обмена сообщениями и подтвердите цель миграции в FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="6d57c-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span>
    
- <span data-ttu-id="6d57c-127">Участвуйте в процессах использования FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="6d57c-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>
    
- <span data-ttu-id="6d57c-128">Подпишите соглашение об использовании служб FastTrack.</span><span class="sxs-lookup"><span data-stu-id="6d57c-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="6d57c-129">Фаза оценки</span><span class="sxs-lookup"><span data-stu-id="6d57c-129">Assess phase</span></span>

 <span data-ttu-id="6d57c-130">**Основные действия**</span><span class="sxs-lookup"><span data-stu-id="6d57c-130">**Key actions**</span></span>
  
- <span data-ttu-id="6d57c-131">FastTrack Center проводит с клиентом семинар по миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-131">FastTrack Center conducts a migration workshop with the customer.</span></span>
    
- <span data-ttu-id="6d57c-132">Вы выполняете предварительные требования миграции, например заполнение анкеты и подготовку рабочих станций администраторов.</span><span class="sxs-lookup"><span data-stu-id="6d57c-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>
    
- <span data-ttu-id="6d57c-133">Оценка миграции для Domino выполняется в локальной среде.</span><span class="sxs-lookup"><span data-stu-id="6d57c-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="6d57c-134">**Обязанности клиента**</span><span class="sxs-lookup"><span data-stu-id="6d57c-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="6d57c-135">Подготовка рабочих станций администраторов, которые FastTrack Center использует для администрирования входящей миграции и таких задач, как оценка, создание реплик, аудит, настройка переадресации во время миграции и т. д.</span><span class="sxs-lookup"><span data-stu-id="6d57c-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    
    > [!NOTE]
    > <span data-ttu-id="6d57c-p104">Оценка крайне важна для успешного планирования и выполнения скоростной миграции. Ее выполняет архитектор миграции, которому требуется определенный уровень доступа к среде Domino. Необходимые компоненты рабочих станций администраторов включают клиент Notes, настроенный для доступа ко всем исходным почтовым серверам Domino и реплике промежуточного сервера Domino в Azure.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the WindowsAzure Domino replica staging server.</span></span> 
  
- <span data-ttu-id="6d57c-p105">Предоставление группе миграции удаленного доступа к рабочим станциям администраторов, учетных записей и разрешений для выполнения действий по оценке и миграции. Это включает подготовку в локальной среде и в Exchange Online нескольких учетных записей с разрешениями администратора, необходимыми для миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in MO_ExchangeOnline_2nd with administrative permissions needed for migration.</span></span>
    
- <span data-ttu-id="6d57c-p106">Открытие портов брандмауэра. Между исходными почтовыми серверами Domino и промежуточным сервером Azure должны быть открыты исходящие порты. Кроме того, следует открыть и другие порты, необходимые для обмена данными, например порты, используемые для рабочих станций администраторов, исходных серверов Domino и локальных серверов Exchange (при их наличии).</span><span class="sxs-lookup"><span data-stu-id="6d57c-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the WindowsAzure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span>
    
- <span data-ttu-id="6d57c-p107">Включение перекрестной сертификации между исходной средой Domino и промежуточным сервером Azure Domino для упрощения репликации. Задачи перекрестной сертификации координируются между администратором Domino пользователя и FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p107">Enable cross-certification between the source Domino environment and the WindowsAzure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer’s Domino administrator and the FastTrack Center.</span></span>
    
- <span data-ttu-id="6d57c-146">Заполнение анкеты миграции, которая содержит сведения, необходимые для настройки среды миграции в Azure (например, инструменты, сценарии и серверы миграции).</span><span class="sxs-lookup"><span data-stu-id="6d57c-146">Complete the migration questionnaire, which captures information required to configure the migration environment in WindowsAzure (like tools, scripts, and migration servers).</span></span>
    
- <span data-ttu-id="6d57c-147">Включение протокола MAPI в целевых почтовых ящиках в Office 365.</span><span class="sxs-lookup"><span data-stu-id="6d57c-147">Ensure target mailboxes in O365_W14_2nd have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>
    
> [!NOTE]
> <span data-ttu-id="6d57c-p108">Некоторые планы Office 365 не поддерживают протокол MAPI. Для переноса данных почтовые ящики из этих планов необходимо заранее преобразовать в планы, поддерживающие протокол MAPI. После завершения миграции внесенные изменения можно отменить.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p108">Some O365_W14_2nd plans don’t support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="6d57c-151">Фаза исправления</span><span class="sxs-lookup"><span data-stu-id="6d57c-151">Remediate phase</span></span>

 <span data-ttu-id="6d57c-152">**Основные действия**</span><span class="sxs-lookup"><span data-stu-id="6d57c-152">**Key actions**</span></span>
  
- <span data-ttu-id="6d57c-153">FastTrack Center просматривает отчет оценки миграции и проверяет подробные сведения, указанные в анкете.</span><span class="sxs-lookup"><span data-stu-id="6d57c-153">FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>
    
- <span data-ttu-id="6d57c-154">Вам необходимо выполнить действия по исправлению, которые рекомендует FastTrack Center.</span><span class="sxs-lookup"><span data-stu-id="6d57c-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="6d57c-155">**Обязанности клиента**</span><span class="sxs-lookup"><span data-stu-id="6d57c-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="6d57c-156">Исправьте среду Domino согласно рекомендациям, предоставленным FastTrack Center (например, настройте все необходимые разрешения, отсутствующие в файлах почты).</span><span class="sxs-lookup"><span data-stu-id="6d57c-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>
    
- <span data-ttu-id="6d57c-157">Убедитесь, что размер почтовых ящиков Domino не превышает максимальный размер, разрешенный для миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    
    > [!NOTE]
    >  <span data-ttu-id="6d57c-158">Хотя FastTrack перенесет почтовые ящики, суммарный размер которых не превышает 85 % от разрешенного в целевой среде, при попытке перенести почтовые ящики размером более 2 ГБ возникают дополнительные риски, например:</span><span class="sxs-lookup"><span data-stu-id="6d57c-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="6d57c-p109">повышенная продолжительность миграции;    </span><span class="sxs-lookup"><span data-stu-id="6d57c-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="6d57c-p110">использование ресурсов, которые в противном случае использовались бы для миграции других почтовых ящиков;    </span><span class="sxs-lookup"><span data-stu-id="6d57c-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="6d57c-161">существенное повышение частоты ошибок.</span><span class="sxs-lookup"><span data-stu-id="6d57c-161">A considerable increase in error rates.</span></span> 
  
- <span data-ttu-id="6d57c-p111">Подготовьте базы данных входящей почты и соответствующие списки управления доступом (ACL) к миграции. Необходимо выполнить некоторые действия по исправлению, чтобы успешно перенести эти базы данных и их разрешения в общий почтовый ящик в Exchange Online. Некоторые из этих действий представлены ниже.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in MO_ExchangeOnline_2nd. A few of these steps are as follows:</span></span>
    
  - <span data-ttu-id="6d57c-165">Удалите имеющиеся записи баз данных входящей почты из каталога Domino и создайте новые записи данных о человеке.</span><span class="sxs-lookup"><span data-stu-id="6d57c-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
    
  - <span data-ttu-id="6d57c-p112">Создайте в локальной службе Active Directory универсальные группы безопасности, поддерживающие почту и синхронизированные с Azure AD в Office 365. Эти группы будут использоваться для настройки разрешений общего почтового ящика в Exchange Online. При этом набор разрешений переносится из базы данных входящей почты в общий почтовый ящик в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p112">Create mail-enabled universal security groups in the on-premises ActiveDirectory_2nd that are synchronized to O365_W14_2ndWindowsAzureAD_2nd and used to configure permissions on the shared mailbox in MO_ExchangeOnline_2nd. This transfers the permissions set on the mail-in database over to the shared mailbox in MO_ExchangeOnline_2nd.</span></span>
    
> [!NOTE]
> <span data-ttu-id="6d57c-168">Теперь можно начать подготовку конечных пользователей и обучение работе с новой системой обмена сообщениями и новым клиентом.</span><span class="sxs-lookup"><span data-stu-id="6d57c-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="6d57c-169">Фаза включения</span><span class="sxs-lookup"><span data-stu-id="6d57c-169">Enable phase</span></span>

 <span data-ttu-id="6d57c-170">**Основные действия**</span><span class="sxs-lookup"><span data-stu-id="6d57c-170">**Key actions**</span></span>
  
- <span data-ttu-id="6d57c-171">FastTrack Center настраивает среду миграции в Azure.</span><span class="sxs-lookup"><span data-stu-id="6d57c-171">FastTrack Center sets up the migration environment in WindowsAzure.</span></span>
    
- <span data-ttu-id="6d57c-172">FastTrack Center настраивает средства миграции на локальных рабочих станциях администраторов.</span><span class="sxs-lookup"><span data-stu-id="6d57c-172">FastTrack Center configures the migration tools on the on-premises admin workstations.</span></span>
    
- <span data-ttu-id="6d57c-173">FastTrack Center настраивает средство автоматического импорта и демонстрирует его использование.</span><span class="sxs-lookup"><span data-stu-id="6d57c-173">FastTrack Center configures and demonstrates how to use the Auto-Import tool.</span></span>
    
- <span data-ttu-id="6d57c-174">FastTrack Center выполняет проверку всех компонентов миграции и совершает тестовую миграцию.</span><span class="sxs-lookup"><span data-stu-id="6d57c-174">FastTrack Center conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="6d57c-175">**Обязанности клиента**</span><span class="sxs-lookup"><span data-stu-id="6d57c-175">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="6d57c-p113">Ваши сотрудники, ответственные за планирование миграции почтовых ящиков, должны знать, как использовать средство автоматического импорта. С помощью этого средства можно импортировать расписание миграции в базу данных планирования, которую FastTrack Center использует для выполнения действий перед миграцией.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database, which the FastTrack Center uses to perform pre-migration activities.</span></span>
    
- <span data-ttu-id="6d57c-178">Выполните действия перед миграцией, например импорт расписаний пользователей, анализ отчетов аудита, устранение проблем и повторный импорт проблемных учетных записей пользователей.</span><span class="sxs-lookup"><span data-stu-id="6d57c-178">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
    <span data-ttu-id="6d57c-p114">Действия перед миграцией координируются между вами и FastTrack Center. Репликация в Azure начинается после импорта пользовательского расписания миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to WindowsAzure begins after the user migration schedule is imported.</span></span> 
    
    > [!NOTE]
    > <span data-ttu-id="6d57c-p115">Время репликации зависит от количества данных. Затем FastTrack Center выполняет аудит, чтобы определить готовность к миграции. Результаты аудита предоставляются вам с учетом того, что обычно требуются последующие исправления. Все эти действия называются действиями отсчета, так как их необходимо выполнять до запланированной пользователем миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called “T-minus” activities because they must begin in advance of the users’ scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="6d57c-185">Фаза миграции</span><span class="sxs-lookup"><span data-stu-id="6d57c-185">Migrate phase</span></span>

 <span data-ttu-id="6d57c-186">**Основные действия**</span><span class="sxs-lookup"><span data-stu-id="6d57c-186">**Key actions**</span></span>
  
- <span data-ttu-id="6d57c-187">FastTrack Center выполняет пилотную и скоростную миграцию.</span><span class="sxs-lookup"><span data-stu-id="6d57c-187">The FastTrack Center performs pilot and velocity migrations.</span></span> 
    
- <span data-ttu-id="6d57c-188">FastTrack Center выполняет события миграции и действия отсчета.</span><span class="sxs-lookup"><span data-stu-id="6d57c-188">The FastTrack Center performs migration events and T-minus activities.</span></span>
    
- <span data-ttu-id="6d57c-189">FastTrack Center предоставляет поддержку после миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-189">The FastTrack Center provides post-migration support.</span></span>
    
 <span data-ttu-id="6d57c-190">**Обязанности клиента**</span><span class="sxs-lookup"><span data-stu-id="6d57c-190">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="6d57c-191">Определите и импортируйте расписания миграции за 21 день до миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-191">Identify and import migration schedules 21 days prior to migration.</span></span>
    
    > [!NOTE]
    > <span data-ttu-id="6d57c-p116">Эта задача критически важна, так как действия перед миграцией включают исправление и возможные повторные попытки создания реплик на разных этапах до дня фактической миграции (T-0). Пока переносятся некоторые из почтовых ящиков, на остальных выполняются действия отсчета. По этой причине надлежащие планирование и координация обязательны.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
  
- <span data-ttu-id="6d57c-195">Устраняйте неполадки, обнаруженные во время выполнения действий отсчета.</span><span class="sxs-lookup"><span data-stu-id="6d57c-195">Fix issues identified during T-minus activities.</span></span>
    
- <span data-ttu-id="6d57c-196">Определите и исправьте проблемы на сервере Domino, которые влияют на действия миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-196">Address and fix any Domino server issues that impact migration activities.</span></span>
    
- <span data-ttu-id="6d57c-197">Сообщите конечным пользователям дату предстоящей миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-197">Conduct end-user communications about the upcoming migration date.</span></span>
    
- <span data-ttu-id="6d57c-198">Проводите мероприятия для подготовки пользователей и обучения работе с новой системой обмена сообщениями и новым клиентом.</span><span class="sxs-lookup"><span data-stu-id="6d57c-198">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>
    
- <span data-ttu-id="6d57c-p117">Определяйте проблемы после миграции и сообщайте о них. FastTrack Center предоставляет помощь в течение 5 дней после миграции, после чего это становится вашей обязанностью. Вы можете вести журнал проблем после миграции, например отсутствующих сообщений, элементов календаря и контактов, а также дублированных элементов почтового ящика.</span><span class="sxs-lookup"><span data-stu-id="6d57c-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration support until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="6d57c-202">Преимущество FastTrack Center не распространяется на развертывание, плату за лицензирование и помощь, связанные с подготовкой каталогов (включая синхронизацию службы каталогов между Domino и Active Directory), надстройки ПО сосуществования для взаимодействия с приложением Notes, самостоятельной миграции или активной миграции.</span><span class="sxs-lookup"><span data-stu-id="6d57c-202">The FastTrack Center doesn't cover deployment, license fees, or support related to directory preparation (including Domino-to-AD directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  
